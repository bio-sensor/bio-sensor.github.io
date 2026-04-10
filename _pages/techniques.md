---
layout: archive
title: ""
permalink: /techniques/
author_profile: false
---

<style>
  /* --- 页面容器 --- */
  .tech-container {
    /* 尝试设置为 100%，让它自动适应父容器的最大宽度 */
    width: 100%; 
    margin: 0 auto;
    padding: 20px 0;
    
    /* Flexbox 布局 */
    display: flex;
    flex-wrap: wrap; 
    justify-content: center; 
    gap: 30px; 
  }

  /* --- 技术卡片样式 --- */
  .tech-card {
    /* !!! 核心修改 !!! 
       原先是 500px，导致需要 1000px+ 的空间才能并排。
       现在改为 300px。
       逻辑：只要有 300+300+30=630px 的空间，它们就会并排。
       同时 flex-grow: 1 会让它们自动变宽，填满剩下的空间，保持“矮胖”效果。
    */
    flex: 1 1 300px; 
    
    /* 限制最大宽度，防止单张卡片在宽屏下过宽 */
    max-width: 600px; 
    
    /* 颜色逻辑 */
    background: rgba(128, 128, 128, 0.08); 
    backdrop-filter: blur(10px);
    -webkit-backdrop-filter: blur(10px);
    border: 1px solid rgba(128, 128, 128, 0.2); 
    border-radius: 12px;
    padding: 25px 30px; 
    box-shadow: 0 5px 20px 0 rgba(0, 0, 0, 0.05); 
    transition: all 0.3s ease;
    text-align: center;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }

  /* 悬停效果 */
  .tech-card:hover {
    transform: translateY(-5px);
    background: rgba(128, 128, 128, 0.12); 
    box-shadow: 0 10px 25px rgba(0,0,0,0.1);
    border-color: #2f7f93;
  }

  /* --- 标题样式 --- */
  .tech-title {
    color: inherit;
    font-size: 1.6em; 
    margin-top: 0;
    margin-bottom: 15px;
    font-weight: bold;
    border-bottom: 1px solid rgba(128, 128, 128, 0.15); 
    padding-bottom: 10px;
    line-height: 1.2;
  }

  /* --- 图片容器样式 --- */
  .tech-image-box {
    margin: 0 auto 15px auto;
    display: inline-block;
    padding: 5px; 
    background: rgba(255, 255, 255, 0.5); 
    border: 1px solid rgba(128, 128, 128, 0.2);
    box-shadow: 0 2px 8px rgba(0,0,0,0.05);
    border-radius: 6px;
    width: 100%; 
  }

  .tech-image-box img {
    width: 100%; 
    height: auto;
    display: block;
    border-radius: 4px;
  }

  /* --- 文本内容样式 --- */
  .tech-description {
    text-align: justify;
    margin: 0 auto;
    width: 100%;
    font-size: 0.95em; 
    line-height: 1.6;
    color: inherit;
    flex-grow: 1; 
  }

  /* --- 参考文献链接样式 --- */
  .tech-publications {
    margin-top: 15px; 
    padding-top: 12px;
    border-top: 1px dashed rgba(128, 128, 128, 0.3);
    font-size: 0.9em; 
    color: #2f7f93; 
  }
  
  .pub-icon {
    margin-right: 5px;
  }

  .tech-publications a {
    color: #2f7f93;
    font-weight: bold;
    text-decoration: none;
    margin: 0 5px;
    transition: opacity 0.2s;
  }
  
  .tech-publications a:hover {
    opacity: 0.7;
    text-decoration: underline;
  }

  /* --- 移动端适配 --- */
  @media (max-width: 768px) {
    .tech-card {
      /* 手机上强制 100% 宽度 */
      flex: 1 1 100%;
    }
  }
</style>

<div class="tech-container">

  <div class="tech-card">
    <div>
      <h1 class="tech-title">Advanced Biosensor Development</h1>
      
      <div class="tech-image-box">
        <img src="/images/tech/trp.gif" alt="Tryptophan Sensor GIF">
      </div>
      
      <div class="tech-description">
        <p>
          We are committed to developing advanced genetically encoded fluorescent indicators to achieve in vivo imaging of small molecular substances, such as metabolites and ions, in model organisms. These biosensors are designed to offer single-cell resolution and high temporal resolution.
        </p>
      </div>
    </div>

    <div class="tech-publications">
      <span class="pub-icon">📄</span> Related:
      <br>
      <a href="/publication/2023-10-31-Tryptophan-sensor" target="_blank">Cell Disc, 2023</a> | 
      <a href="/publication/2024-11-14-Tryptophan-imaging">BMC Biol, 2024</a>
    </div>
  </div>


  <div class="tech-card">
    <div>
      <h1 class="tech-title">Multiplexed Imaging in Behavioral Animals</h1>
      
      <div class="tech-image-box">
        <img src="/images/papers/haloda/science.jpg" alt="Multiplexed Imaging Science Paper">
      </div>
      
      <div class="tech-description">
        <p>
          Simultaneous detection of multiple chemical substances in living animals represents a key technological frontier. By expressing infrared, red, and green probes in zebrafish, we have achieved concurrent imaging of dopamine, calcium, and ATP, allowing dynamic monitoring during electrical stimulation and epileptic states.
        </p>
      </div>
    </div>

    <div class="tech-publications">
       <span class="pub-icon">📄</span> Related:
       <br>
       <a href="/publication/2025-03-21-HaloDA" target="_blank">Science, 2025</a> |
       <a href="/publication/2025-02-27-BD-dye" target="_blank">Nature Methods, 2025</a>
    </div>
  </div>


  <!-- Card 3: High-Throughput Screening (新增卡片) -->
  <div class="tech-card">
    <div>
      <h1 class="tech-title">High-Throughput Screening Platform</h1>
      
      <div class="tech-image-box">
        <!-- 记得把这里替换为你实际的图片或动图路径 -->
        <img src="/images/tech/hts.png" alt="High-Throughput Screening Platform">
      </div>
      
      <div class="tech-description">
        <p>
          We leverage high-throughput molecular biology techniques combined with a semi-automated fluorescent protein characterization platform to accelerate protein engineering. This streamlined workflow allows us to rapidly screen, evaluate, and optimize novel biosensor variants with high efficiency.
        </p>
      </div>
    </div>

    <div class="tech-publications">
       <span class="pub-icon">⚙️</span> Tools & Methods:
       <br>
       <a href="/resources/#software" target="_blank">mProcess</a> |
       <a href="/resources/#protocols" target="_blank">Lab Protocols</a>
    </div>
  </div>
  

</div>