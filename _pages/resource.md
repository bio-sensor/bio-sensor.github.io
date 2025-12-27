---
layout: archive
title: "Resources for sharing"
permalink: /resources/
author_profile: false
---

<style>
  /* --- 全局布局与字体 --- */
  .resource-container {
    max-width: 1000px;
    margin: 0 auto;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  }

  /* 替代 <br> 的间距工具 */
  .section-spacer {
    margin-top: 60px;
    margin-bottom: 40px;
    border-bottom: 1px solid rgba(128, 128, 128, 0.2); /* 半透明分割线 */
  }

  /* --- 顶部导航栏 --- */
  .resource-nav {
    display: flex;
    justify-content: center;
    gap: 30px;
    margin: 30px 0;
    padding: 15px;
    background: rgba(128, 128, 128, 0.05); /* 极淡背景 */
    border-radius: 50px; /* 胶囊形状 */
  }

  .resource-nav a {
    text-decoration: none;
    color: #2f7f93; /* 品牌蓝 */
    font-weight: bold;
    font-size: 1.1em;
    padding: 5px 15px;
    border-radius: 20px;
    transition: all 0.3s;
  }

  .resource-nav a:hover {
    background-color: #2f7f93;
    color: #fff;
    transform: translateY(-2px);
  }

  /* --- 通用卡片样式 (用于软件和协议) --- */
  .resource-card {
    border: 1px solid rgba(128, 128, 128, 0.2);
    border-radius: 10px;
    padding: 25px;
    margin-bottom: 30px;
    background: rgba(128, 128, 128, 0.02); /* 微微的底色 */
    transition: transform 0.2s, box-shadow 0.2s, border-color 0.2s;
  }

  .resource-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(0,0,0,0.1);
    border-color: #2f7f93;
  }

  /* --- 标题样式 --- */
  h2 {
    color: inherit;
    border-bottom: 2px solid rgba(128, 128, 128, 0.2);
    padding-bottom: 10px;
    margin-top: 0;
    margin-bottom: 25px;
    display: inline-block;
    padding-right: 20px;
  }
  
  /* --- 表格美化 --- */
  .table-wrapper {
    overflow-x: auto; /* 防止小屏溢出 */
  }
  
  table {
    width: 100%;
    border-collapse: collapse;
    margin-bottom: 20px;
  }

  th, td {
    padding: 12px 15px;
    text-align: left;
    border-bottom: 1px solid rgba(128, 128, 128, 0.2);
  }

  tr:hover {
    background-color: rgba(47, 127, 147, 0.05); /* 悬停高亮 */
  }
  
  th {
    font-weight: 700;
    color: #2f7f93;
  }

  /* --- RIA 软件部分 --- */
  .ria-badges {
    margin: 10px 0 20px 0;
  }
  
  .ria-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
    margin-top: 20px;
  }
  
  /* --- 小软件网格布局 (Other Softwares) --- */
  .software-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); /* 响应式：自动排布 */
    gap: 25px;
  }

  .small-software-card {
    display: flex;
    flex-direction: column;
    height: 100%; /* 等高 */
  }

  .software-img-container {
    flex-grow: 1;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 15px 0;
    background: rgba(255,255,255,0.05); /* 图片背景 */
    padding: 10px;
    border-radius: 5px;
  }

  /* --- 图片与文字 --- */
  .responsive-img {
    max-width: 100%;
    height: auto;
    border-radius: 4px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  }

  .caption {
    display: block; 
    color: #888; /* 灰色文字 */
    font-size: 0.9em; 
    font-style: italic; 
    margin-top: auto; /* 推到底部 */
    text-align: center;
  }

  /* --- 协议列表样式 --- */
  .protocol-list {
    list-style: none;
    padding: 0;
  }

  .protocol-list li {
    padding: 10px 0;
    border-bottom: 1px dashed rgba(128, 128, 128, 0.2);
    display: flex;
    align-items: center;
  }
  
  .protocol-list li::before {
    content: "📄";
    margin-right: 10px;
  }

  /* --- 回到顶部按钮 --- */
  #back-to-top {
    position: fixed;
    bottom: 40px;
    right: 20px;
    padding: 10px 15px;
    font-size: 14px;
    background-color: #2f7f93;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.2);
    z-index: 1000;
    transition: background-color 0.3s ease;
    display: none;
  }

  #back-to-top:hover {
    background-color: #007bff;
  }
  
  /* 移动端适配 */
  @media (max-width: 768px) {
    .ria-grid {
      grid-template-columns: 1fr; /* 手机上单列 */
    }
    .resource-nav {
      flex-wrap: wrap;
      gap: 10px;
    }
  }
</style>

<div class="resource-container">

  <nav class="resource-nav">
    <a href="#plasmids">🧬 Plasmids</a>
    <a href="#software">🖥️ Software</a>
    <a href="#protocols">📋 Protocols</a>
  </nav>

  <div class="section-spacer"></div>
  <h2 id="plasmids">Expression vector maps for biosensors</h2>

  <p>For detailed usage of these biosensors in imaging, or for plasmid requests, please contact <a href="mailto:wangk@ion.ac.cn" style="color: #2f7f93; font-weight: bold;">Dr. Kui Wang</a>.</p>

  <div class="table-wrapper">
    <table>
      <thead>
        <tr>
          <th>ID</th>
          <th>Vector</th>
          <th>Description</th>
          <th>Reference</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><a href="/files/plasmid/K140.dna">K2</a></td>
          <td>pcDNA-GRIT</td>
          <td>Tryptophan sensor expressed in mammalian cell</td>
          <td><a href="/publication/2023-10-31-Tryptophan-sensor">Cell Disc, 2023</a></td>
        </tr>
        <tr>
          <td><a href="/files/plasmid/K140.dna">K3</a></td>
          <td>pcDNA-GRITol</td>
          <td>Tryptophan control sensor expressed in mammalian cell</td>
          <td><a href="/publication/2023-10-31-Tryptophan-sensor">Cell Disc, 2023</a></td>
        </tr>
        <tr>
          <td><a href="/files/plasmid/K140.dna">K4</a></td>
          <td>pcDNA-mito-GRIT</td>
          <td>Mitochondrial Tryptophan sensor expressed in mammalian cell</td>
          <td><a href="/publication/2024-11-14-Tryptophan-imaging">BMC Biol, 2024</a></td>
        </tr>
        <tr>
          <td><a href="/files/plasmid/K140.dna">K5</a></td>
          <td>pcDNA-mito-GRITol</td>
          <td>Mitochondrial Tryptophan control sensor expressed in mammalian cell</td>
          <td><a href="/publication/2024-11-14-Tryptophan-imaging">BMC Biol, 2024</a></td>
        </tr>
        <tr>
          <td><a href="/files/plasmid/PLACEHOLDER.dna">K6</a></td>
          <td>✨GEM<sub>CPPU</sub>1.0 Sensor</td>
          <td>Ratiometric biosensor for detecting Forchlorfenuron (CPPU)</td>
          <td>Manuscript in preparation</td>
        </tr>
        <tr>
          <td><a href="/files/plasmid/PLACEHOLDER.dna">K7</a></td>
          <td>✨GEM<sub>TrpA</sub>1.0 Sensor</td>
          <td>Novel sensor for monitoring Tryptamine dynamics <em>in vivo</em></td>
          <td>Under revision</td>
        </tr>
      </tbody>
    </table>
  </div>


  <div class="section-spacer"></div>
  <h2 id="software">Ratio Imaging Analyzer (RIA)</h2>

  <div class="resource-card">
    <div style="margin-bottom: 15px;">
      <strong>Ratio Imaging Analyzer (RIA)</strong> is a lightweight, user-friendly tool designed for processing dual-channel ratiometric fluorescence data (e.g., Calcium, FRET, NADH). It features automated alignment, smart background subtraction, and real-time ROI plotting.
    </div>

    <div class="ria-badges">
      <a href="https://github.com/Epivitae/RatioImagingAnalyzer"><img src="https://img.shields.io/badge/version-v1.7.5-blue" alt="Version"></a>
      <img src="https://img.shields.io/badge/license-MIT-green" alt="License">
      <img src="https://img.shields.io/badge/python-3.8%2B-yellow" alt="Python">
      &nbsp;
      <a href="https://github.com/Epivitae/RatioImagingAnalyzer" style="color:#2f7f93; font-weight:bold; margin-left: 10px;">View on GitHub →</a>
    </div>

    <div class="ria-grid">
      <div>
        <div style="font-weight: bold; text-align: center; margin-bottom: 5px;">Automated Workflow</div>
        <img src="/images/resource/analysis.gif" class="responsive-img">
        <span class="caption">Auto-alignment & ratiometric heatmap generation</span>
      </div>
      <div>
        <div style="font-weight: bold; text-align: center; margin-bottom: 5px;">Interactive Analysis</div>
        <img src="/images/resource/live-plot.gif" class="responsive-img">
        <span class="caption">Real-time ROI monitoring & curve plotting</span>
      </div>
    </div>
  </div>


  <h3>🖥️ Other Ready-to-Use Lab Software</h3>
  <br>

  <div class="software-grid">
    
    <div class="resource-card small-software-card">
      <div style="font-size: 1.1em; margin-bottom: 8px;">
        <strong>1. mProcess</strong>
      </div>
      <div style="margin-bottom: 10px; font-size: 0.95em;">
        A self-developed tool for microplate data preprocessing.
      </div>
      <div style="margin-bottom: 15px;">
        <a href="/files/app/mProcess%20V4.0.exe" style="text-decoration: none;">
          <img src="https://img.shields.io/badge/Download-mProcess_V4.0-007bff" alt="Download">
        </a>
        <img src="https://img.shields.io/badge/license-Freeware-green" alt="License">
      </div>
      <div class="software-img-container">
        <a href="/files/app/pic/mProcess.gif" target="_blank">
          <img src="/files/app/pic/mProcess.gif" alt="mProcess" class="responsive-img">
        </a>
      </div>
      <span class="caption">Figure 1: Batch data processing interface.</span>
    </div>

    <div class="resource-card small-software-card">
      <div style="font-size: 1.1em; margin-bottom: 8px;">
        <strong>2. zGrating</strong>
      </div>
      <div style="margin-bottom: 10px; font-size: 0.95em;">
        A self-developed visual stimulus generator.
      </div>
      <div style="margin-bottom: 15px;">
        <a href="/files/app/zGrating_V2.3.exe" style="text-decoration: none;">
          <img src="https://img.shields.io/badge/Download-zGrating_V2.3-007bff" alt="Download">
        </a>
        <img src="https://img.shields.io/badge/license-Freeware-green" alt="License">
      </div>
      <div class="software-img-container">
        <a href="/files/app/pic/zGrating.gif" target="_blank">
          <img src="/files/app/pic/zGrating.gif" alt="zGrating" class="responsive-img">
        </a>
      </div>
      <span class="caption">Figure 2: Radial grating pattern generation.</span>
    </div>

    <div class="resource-card small-software-card">
      <div style="font-size: 1.1em; margin-bottom: 8px;">
        <strong>3. zStimuli</strong>
      </div>
      <div style="margin-bottom: 10px; font-size: 0.95em;">
        Controls Arduino via serial communication for multimodal stimuli.
      </div>
      <div style="margin-bottom: 15px;">
        <a href="/files/app/zStimuli4.0.exe" style="text-decoration: none;">
          <img src="https://img.shields.io/badge/Download-zStimuli_V4.0-007bff" alt="Download">
        </a>
        <img src="https://img.shields.io/badge/license-Freeware-green" alt="License">
      </div>
      <div class="software-img-container">
        <a href="/files/app/pic/zStimuli.png" target="_blank">
          <img src="/files/app/pic/zStimuli.png" alt="zStimuli" class="responsive-img">
        </a>
      </div>
      <span class="caption">Figure 3: Control panel for experimental stimuli.</span>
    </div>

  </div>


  <div class="section-spacer"></div>
  <h2 id="protocols">Protocols in our hands</h2>

  <div class="resource-card">
    <ul class="protocol-list">
      <li>
        <a href="/files/protocol/K.WANG Molecular cloning Methods in our hands (V1.0).pdf">High-throughput recombinant DNA preparation</a>
      </li>
      <li>
        <a href="/files/protocol/K.WANG%20Tol2%20mRNA%20IVT%20protocol.pdf"><em>In vitro</em> transcription for mRNA preparation</a>
      </li>
      <li>
        Biosensor protein purification
      </li>
      <li>
        Fluorescent biosensor screening and modification
      </li>
    </ul>
  </div>

  <div class="section-spacer"></div>
  <h3>Useful codes</h3>
  <pre style="background: rgba(128,128,128,0.1); padding: 10px; border-radius: 5px;">bundle exec jekyll serve --livereload
jekyll clean</pre>

</div>

<button id="back-to-top" onclick="scrollToTop()">⬆️ Back to Top</button>

<script>
  var mybutton = document.getElementById("back-to-top");
  window.onscroll = function() {scrollFunction()};
  function scrollFunction() {
    if (document.body.scrollTop > 300 || document.documentElement.scrollTop > 300) {
      mybutton.style.display = "block";
    } else {
      mybutton.style.display = "none";
    }
  }
  function scrollToTop() {
    window.scrollTo({ top: 0, behavior: 'smooth' });
  }
</script>