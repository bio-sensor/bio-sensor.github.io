---
layout: archive
title: "Our CNS Team"
permalink: /Team/
author_profile: false
---

<style>
  /* --- 布局样式 --- */
  
  /* 介绍文字样式 */
  .intro-text {
    font-size: 1.1em;
    line-height: 1.6;
    color: inherit; /* 继承主题文字颜色 */
    margin-bottom: 40px;
    border-left: 5px solid #2f7f93;
    padding-left: 20px;
    background: rgba(128, 128, 128, 0.05); /* 半透明背景 */
    padding: 15px 20px;
    border-radius: 0 5px 5px 0;
  }

  /* 章节标题 */
  .section-title {
    margin-top: 60px;
    margin-bottom: 30px;
    font-size: 1.8em;
    border-bottom: 2px solid rgba(128, 128, 128, 0.2); /* 半透明分割线 */
    padding-bottom: 10px;
    color: inherit; /* 继承主题文字颜色 */
  }

  /* 网格布局容器 */
  .team-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(350px, 1fr)); 
    gap: 25px; 
    margin-bottom: 40px;
  }

  /* 单个成员卡片 */
  .member-card {
    /* 半透明背景，兼容黑白模式 */
    background: rgba(128, 128, 128, 0.05); 
    border: 1px solid rgba(128, 128, 128, 0.2); 
    border-radius: 8px;
    padding: 25px;
    transition: all 0.3s ease;
    display: flex; 
    align-items: flex-start;
    position: relative; 
    
    /* 增加一点毛玻璃质感 */
    backdrop-filter: blur(5px);
    -webkit-backdrop-filter: blur(5px);
  }

  /* 悬停效果 */
  .member-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(0,0,0,0.1); /* 稍微加深阴影 */
    background: rgba(128, 128, 128, 0.1); /* 悬停时背景加深一点 */
    border-color: #2f7f93;
  }

  /* 成员图标/头像区域 */
  .member-icon {
    font-size: 3.5rem; 
    margin-right: 20px;
    flex-shrink: 0; 
    line-height: 1;
  }

  /* 成员信息区域 */
  .member-info {
    flex-grow: 1;
  }

  /* 名字 */
  .member-name {
    font-size: 1.3em;
    font-weight: bold;
    color: #2f7f93; /* 品牌色在黑白底上都清晰 */
    margin-bottom: 5px;
    display: block;
  }

  /* 时间/日期 */
  .member-date {
    font-size: 0.85em;
    color: #2f7f93; /* 改用品牌色，或者使用 inherit + opacity */
    opacity: 0.8;
    margin-bottom: 10px;
    display: block;
    font-family: monospace; 
  }

  /* 学校名称高亮 */
  .member-school {
    font-weight: bold;
    color: inherit; /* 跟随主题颜色 */
  }

  /* 描述文字 */
  .member-desc {
    font-size: 0.95em;
    color: inherit; /* 跟随主题颜色 */
    opacity: 0.85; /* 稍微淡一点 */
    line-height: 1.5;
    margin-top: 8px;
  }

  /* 锚点偏移修正 */
  .anchor-fix {
    position: absolute;
    top: -100px;
    visibility: hidden;
  }

  /* --- 照片相册样式 --- */
  .photo-gallery {
    display: flex;
    flex-direction: column;
    gap: 30px;
    margin-top: 50px;
    align-items: center;
  }

  .team-photo-frame {
    /* 稍微半透明的白色背景，模拟相纸，但在深色模式下不会太刺眼 */
    background: rgba(255, 255, 255, 0.9); 
    padding: 15px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.15);
    border-radius: 4px;
    transform: rotate(-1deg); 
    transition: transform 0.3s ease;
    max-width: 90%;
  }
  
  /* 深色模式下，让相框稍微暗一点，避免过于刺眼（可选，利用CSS混合模式） */
  @media (prefers-color-scheme: dark) {
      .team-photo-frame {
          background: rgba(255, 255, 255, 0.8);
      }
  }

  .team-photo-frame:nth-child(even) {
    transform: rotate(1deg); 
  }

  .team-photo-frame:hover {
    transform: rotate(0deg) scale(1.02); 
    z-index: 10;
  }

  .team-photo-frame img {
    width: 100%;
    border-radius: 2px;
    display: block;
  }
  
  /* 照片说明 */
  .photo-caption {
    text-align: center;
    margin-top: 10px;
    font-family: "Courier New", Courier, monospace;
    color: #333; /* 相框内部文字保持深色，因为相框底色是浅色 */
    font-size: 0.9em;
    font-weight: bold;
  }

  /* 回到顶部按钮 */
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
    display: none;
  }
  #back-to-top:hover { background-color: #007bff; }
</style>

<div class="intro-text">
  Since late 2024, I began recruiting young talents from across China and around the world to form the <strong>Chimeric Nano Sensor (CNS) research team</strong>, dedicated to advancing sensor development and in vivo imaging applications in animal models. 
  <br><br>
  Today, we’ve built a dynamic and collaborative team—highly capable, full of energy, and united by a shared passion for scientific discovery.
</div>

<h2 class="section-title">🌞 Students</h2>

<div class="team-grid">

  <div class="member-card">
    <div id="Yiran" class="anchor-fix"></div> 
    <div class="member-icon">🦠</div>
    <div class="member-info">
      <span class="member-name">Yiran Zhao</span>
      <span class="member-date">Feb 2026 - Present</span>
      <div class="member-desc">
        M.Sc. graduate from <span class="member-school">Trinity College Dublin</span> (B.Sc. from UCD, UK). Currently an intern exploring the physiological significance of gut microbiota via <em>in vivo</em> metabolic imaging.
      </div>
    </div>
  </div>

  <div class="member-card">
    <div id="Zhengyuan" class="anchor-fix"></div>
    <div class="member-icon">🧬</div>
    <div class="member-info">
      <span class="member-name">Zhengyuan Pan</span>
      <span class="member-date">2025 - Present</span>
      <div class="member-desc">
        M.Sc. graduate from <span class="member-school">Johns Hopkins University</span> (B.SC. from SUNY Cobleskill, USA). She has significantly accelerated the development of genetically encoded Pi probes, leading to substantial experimental breakthroughs.
      </div>
    </div>
  </div>

  <div class="member-card">
    <div id="Jie" class="anchor-fix"></div>
    <div class="member-icon">👩‍🔬</div>
    <div class="member-info">
      <span class="member-name">Jie Li</span>
      <span class="member-date">Aug 2024 - Present</span>
      <div class="member-desc">
        M.Sc. candidate from <span class="member-school">Shanghai Ocean University</span>. Developing genetically encoded thermometers for zebrafish. He is currently preparing a first-author manuscript regarding <em>in vivo</em> imaging of CPPU sensor.
      </div>
    </div>
  </div>

  <div class="member-card">
    <div id="Jia" class="anchor-fix"></div>
    <div class="member-icon">🌿</div>
    <div class="member-info">
      <span class="member-name">Jia Qian</span>
      <span class="member-date">June 2025 - Present</span>
      <div class="member-desc">
        B.Sc. candidate from <span class="member-school">Shanghai Normal University</span>. Her research focuses on genetically encoded auxin biosensors, integrating plant physiology with molecular probe design.
      </div>
    </div>
  </div>

  <div class="member-card">
    <div id="Yuanhua" class="anchor-fix"></div>
    <div class="member-icon">🐟</div>
    <div class="member-info">
      <span class="member-name">Yuanhua Wang</span>
      <span class="member-date">July 2025 - Present</span>
      <div class="member-desc">
        Undergraduate from <span class="member-school">Southwest University</span>. Working on <em>in vivo</em> imaging in zebrafish and functional validation of real-time biological sensing tools.
      </div>
    </div>
  </div>

  <div class="member-card">
    <div id="Yihan" class="anchor-fix"></div>
    <div class="member-icon">🧪</div>
    <div class="member-info">
      <span class="member-name">Yihan Zhou</span>
      <span class="member-date">July 2025 - Present</span>
      <div class="member-desc">
        Undergraduate from <span class="member-school">Shanghai University</span>. Joining as a summer intern to explore molecular probe technologies and assist in biosensor experiments.
      </div>
    </div>
  </div>

  <div class="member-card">
      <div id="Yichen" class="anchor-fix"></div> 
      <div class="member-icon">🧠</div>
      <div class="member-info">
        <span class="member-name">Yichen Yang</span>
        <span class="member-date">Feb 2026 - Present</span>
        <div class="member-desc">
          Undergraduate from <span class="member-school">Zhiyuan College, Shanghai Jiao Tong University</span>. A Shanghai native exploring the intersection of molecular biology and neuroscience.
        </div>
      </div>
    </div>
</div>

<h2 class="section-title">🎓 Alumni</h2>

<div class="team-grid">

  <div class="member-card">
    <div id="Yongkang" class="anchor-fix"></div>
    <div class="member-icon">🧬</div>
    <div class="member-info">
      <span class="member-name">Yongkang Che</span>
      <span class="member-date">July 2025 - Sep 2025</span>
      <div class="member-desc">
        Undergraduate from <span class="member-school">University of Glasgow</span>. Focused on in vitro detection of biosensors and developed core molecular biology techniques.
      </div>
    </div>
  </div>

  <div class="member-card">
    <div id="Yun" class="anchor-fix"></div>
    <div class="member-icon">🎨</div>
    <div class="member-info">
      <span class="member-name">Yun Wang</span>
      <span class="member-date">June 2025 - Aug 2025</span>
      <div class="member-desc">
        Undergraduate from <span class="member-school">Shanghai Jiao Tong University</span>. Blended synthetic biology with creative expression by working on bacterial art using color-engineered <em>E. coli</em>.
      </div>
    </div>
  </div>

  <div class="member-card">
    <div id="Lexin" class="anchor-fix"></div>
    <div class="member-icon">🧫</div>
    <div class="member-info">
      <span class="member-name">Lexin Chang</span>
      <span class="member-date">Aug 2025 - Aug 2025</span>
      <div class="member-desc">
        Undergraduate from <span class="member-school">Jiangxi Normal University</span>. Learned molecular biology experiments and built essential lab skills for future research in synthetic biology.
      </div>
    </div>
  </div>



</div>

<h2 class="section-title">🖼️ Captured Moments</h2>
<div class="photo-gallery">
  
  <div class="team-photo-frame">
    <img src="/images/team/team1.PNG" alt="CNS Team Photo 1">
    <div class="photo-caption">The CNS Team - Exploring the Microscopic World</div>
  </div>

  <div class="team-photo-frame">
    <img src="/images/team/team2.PNG" alt="CNS Team Photo 2">
    <div class="photo-caption">Collaboration & Innovation in the Lab</div>
  </div>

</div>

<br><br><br>

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