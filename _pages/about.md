---
permalink: /
author_profile: true
stylesheets:
  - /assets/css/home.css
redirect_from: 
  - /about/
  - /about.html
---
<style>
/* PDF/ArXiv/Code 标签统一样式 */
.tag-pdf,
.tag-arxiv,
.tag-code {
  display: inline-block;
  color: #ca6f6f;
  text-decoration: none;
  margin-right: 5px;
}

.tag-pdf:hover,
.tag-arxiv:hover,
.tag-code:hover {
  text-decoration: underline;
  color: #c71585;
}

/* 确保emoji和文字颜色一致 */
.tag-pdf .emoji,
.tag-pdf emoji,
.tag-arxiv .emoji,
.tag-arxiv emoji,
.tag-code .emoji,
.tag-code emoji {
  color: #ca6f6f;
  font-style: normal;
}
</style>

<h1 class="main-heading">Hi there <img src="images/Hi.gif" width="40px"> Welcome to my Homepage!</h1>

Hi! I am a senior undergraduate student at Fuzhou University, majoring in Computer Science and Technology, and will join Arizona State University in Fall 2026 to pursue a Master's degree in Data Science, Analytics and Engineering.

My current research interests include self-evolution and uncertainty quantification of large language models, reinforcement learning, recommender systems, and spatio-temporal data mining. During my undergraduate studies, I conducted independent research and led several research projects. I have published a paper accepted at the AAAI 2026 Workshop on AI for Urban Planning, and won a gold medal (ranked 7th out of 1,849 teams) in the Kaggle LMSYS competition.

I enjoy building simple yet effective solutions, and I'm always open to collaboration across different fields.

Feel free to reach out if you'd like to connect or explore opportunities together!

News
---------------
<div class="news-box">
  <ul class="news-list">

<li><span class="news-date"><em>2026.05</em></span> 🎉🎉 My undergraduate thesis was awarded Outstanding Thesis Defense.</li>

<li><span class="news-date"><em>2025.12</em></span> 🎉🎉 I received offers from ASU for both the MS in Computer Science (MSCS) and the MS in Data Science, Analytics and Engineering (MS DSAE) programs.</li>

<li><span class="news-date"><em>2025.11</em></span> 🎉🎉 One paper accepted to AAAI 2026 Workshop AI for Urban Planning.</li>

<li><span class="news-date"><em>2024.08</em></span> 🎉🎉 I won a gold medal (ranked 7th out of 1,849 teams) in the Kaggle LMSYS competition.</li>

<li><span class="news-date"><em>2022.09</em></span> 🎉🎉 I began my study at FZU.</li>
  </ul>
</div>

Experience
--------------

<div class="experience-container">

<!-- 
  <div class="experience-card">
      <img src="images/haidilao.png" alt="Haidilao logo" class="experience-logo">
      <div class="experience-info">
          <strong>Haidilao</strong><br>
          <em>2026.05 - Present</em><br>
          LLM Engineer Intern advised by <a href="https://wd7ang.github.io/"><em>Weidong Tang</em></a><br>
          <span style="color:#888;">Main contribution: teaching hotpot robots to understand human emotions.</span>
      </div>
  </div>

  <div class="experience-card">
      <img src="images/weijia.png" alt="Weijia logo" class="experience-logo">
      <div class="experience-info">
          <strong>Weijia</strong><br>
          <em>2026.01 - 2026.03</em><br>
          Machine Learning Intern advised by <a href="https://selen-suyue.github.io/"><em>Yue Su</em></a><br>
          <span style="color:#888;">Successfully reduced GPU happiness by 97%.</span>
      </div>
  </div>

-->

  <div class="experience-card">
      <img src="images/asu.png" alt="ASU logo" class="experience-logo">
      <div class="experience-info">
          <strong>Arizona State University</strong><br>
          <em>2026.08 - Present</em><br>
          Master at <a href="https://scai.engineering.asu.edu/"><em>School of Computing and Augmented Intelligence</em></a><br>
          <span style="color:#888;">Research interests include self-evolution and uncertainty quantification of large language models, reinforcement learning.</span>
      </div>
  </div>

  <div class="experience-card">
      <img src="images/fzu.png" alt="FZU logo" class="experience-logo">
      <div class="experience-info">
          <strong>Fuzhou University</strong><br>
          <em>2022.09 - 2026.6</em><br>
          B.E at <a href="https://ccds.fzu.edu.cn/"><em>College of Computer and Data Science/College of Software</em></a><br>
          <span style="color:#888;">Research interests include llm and POI recommendation.</span>
      </div>
  </div>
</div>


Publications
--------------
<button class="pub-button active" onclick="filterPublications(event, 'all')">Core Publications</button>
<button class="pub-button" onclick="filterPublications(event, 'list')">Full Publications List</button>


(* equal contribution · &dagger; corresponding author · &Dagger; project leader)

<div id="core-publications" class="publication-view" data-publication-view="core">
<div class="publication-card" data-category="all"> 
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;"> 
      <img src="images/STRL-GLA.png" alt="wog" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;"> 
    </div> 
    <div>
      <strong>Spatial-Temporal Representation Learning with Global-Local Alignment for Next POI Recommendation</strong><br>
      <i style="font-size: 13px;">
        <a href="" target="_blank">
          <strong>Zhiyuan Cao</strong>
        </a>,
        <a href="" target="_blank">
          <strong>Songyu Ke&dagger;</strong>
        </a>.
      </i><br> 
      STRL-GLA jointly models global spatio-temporal contexts and local sequential patterns via graph and hypergraph learning, and aligns them through distribution matching and contrastive learning.
      <br> 
      <b><i style="color:#83a1c7;"><a href="https://ai-for-urban-planning.github.io/AAAI26-workshop/" target="_blank" style="color:#83a1c7; text-decoration:none;">AAAI 2026 Workshop AI for Urban Planning &nbsp;</a>
      </i></b> 
      <a href="pdfs/STRL-GLA.pdf" class="tag-pdf" target="_blank"><em>[pdf]</em></a>
      <a href="" class="tag-arxiv"><em>[arXiv]</em></a> 
      <a href="https://github.com/FzuCaozhiyuan/STRL-GLA" class="tag-code"><em>[code]</em></a> 
    </div>
  </div> 
</div>


<div class="publication-card" data-category="all"> 
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;"> 
      <img src="images/FeatEvolve.png" alt="wog" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;"> 
    </div> 
    <div>
      <strong>From Global Sampling to Local Search: Combinatorial Optimization Perspective based Tabular Feature Engineering</strong><br>
      <i style="font-size: 13px;">
        <a href="" target="_blank">
          <strong>Zhiyuan Cao</strong>
        </a>.
      </i><br> 
      I introduce a novel paradigm that shifts traditional MDP-based feature expression generation toward combinatorial-space sampling and optimization and transforms explicit generation into implicit latent-space optimization for automated tabular feature engineering.
      <br> 
      <b><i style="color:#83a1c7;">Undergraduate Thesis &nbsp;
      </i></b> 
      <a href="pdfs/FeatEvolve.pdf" class="tag-pdf" target="_blank"><em>[pdf]</em></a>
      <a href="" class="tag-arxiv"><em>[arXiv]</em></a> 
      <a href="" class="tag-code"><em>[code]</em></a> 
    </div>
  </div> 
</div>

<!-- 
<div class="publication-card" data-category="all"> 
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;"> 
      <img src="images/gpu.png" alt="wog" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;"> 
    </div> 
    <div>
      <strong>Are GPUs Emotionally Stable? A Large-Scale Empirical Study Under 24/7 Training Stress</strong><br>
      <i style="font-size: 13px;">
        NVIDIA RTX 9090*,
        <a href="https://selen-suyue.github.io/" target="_blank">
          <strong>Yue Su*</strong>
        </a>,
        <a href="https://wd7ang.github.io" target="_blank">
          <strong>Weidong Tang&dagger;</strong>
        </a>.
      </i><br> 
      We conduct the first psychological evaluation of modern GPUs under extreme training conditions. Results reveal that 87% of devices exhibit symptoms of burnout after repeated “just one more epoch” requests.
      <br> 
      <b><i style="color:#83a1c7;">ICLR 3026 &nbsp;
      </i></b> 
      <a href=""><em>[arXiv]</em></a> 
      <a href=""><em>[code]</em></a> 
    </div>
  </div> 
</div>

<div class="publication-card" data-category="all"> 
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;"> 
      <img src="images/noodle.png" alt="wog" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;"> 
    </div> 
    <div>
      <strong>Instant Noodles as a Scalable Training Infrastructure for Graduate Students</strong><br>
      <i style="font-size: 13px;">
        Noodles&Dagger;,
        <a href="https://selen-suyue.github.io/" target="_blank">
          <strong>Yue Su*</strong>
        </a>,
        <a href="https://wd7ang.github.io" target="_blank">
          <strong>Weidong Tang&dagger;</strong>
        </a>.
      </i><br> 
      We introduce Noodle-Scaling Law, showing that research productivity increases logarithmically with instant noodle consumption before collapsing catastrophically at 3 a.m.
      <br> 
      <b><i style="color:#83a1c7;">ICML 3026 &nbsp;
      </i></b> 
      <a href=""><em>[arXiv]</em></a> 
      <a href=""><em>[code]</em></a> 
    </div>
  </div> 
</div>
-->

</div>


<div id="full-publications" class="publication-view" data-publication-view="list" hidden>
  <ul class="full-publication-list">
    <li>
      <span class="pub-list-badge">AAAIW 2026</span>
      <span class="pub-list-title">Spatial-Temporal Representation Learning with Global-Local Alignment for Next POI Recommendation</span><br>
      <span class="pub-list-authors">
        <a href="" target="_blank">
          <strong>Zhiyuan Cao</strong>
        </a>.
      </span>
      <!--  <span class="pub-list-note">Oral.</span>  -->
      <span class="pub-list-links"><a href="pdfs/STRL-GLA.pdf" class="tag-pdf" target="_blank">[pdf]</a><a href="" class="tag-arxiv">[arXiv]</a><a href="" class="tag-code">[code]</a></span>
    </li>
  </ul>
</div>


<script src="assets/js/show_publications.js"></script>
<script src="assets/js/pub_media_rotator.js"></script>


Projects
--------
<div class="project-card" data-category="project"> 
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;">
      <img src="images/bioinformatics.png" alt="ManiUniCon" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;">
    </div>
    <div> 
      <strong>FZU-Bioinformatics-Lab</strong><br>
      <i style="font-size: 13px;">
        <a href="" target="_blank"><strong>Zhiyuan Cao</strong></a>.
      </i><br>
      The project developed a multi-agent RL framework and VAE structure for autonomous feature/biomarker selection from multi-omics gastric cancer dataset, using BiLSTM encoding, VAE-based latent space representation, and Transformer decoding to generate superior selection solutions among about 300000 biomarkers.
      <br> 
      <b><i style="color:#83a1c7;">Project &nbsp;</i></b> 
      <a href="https://github.com/FzuCaozhiyuan/FZU-Bioinformatics-Lab"><em>[code]</em></a> 
    </div>
  </div> 
</div>


Awards
--------
- *2026.05*, Outstanding Undergraduate Thesis Defense Award.
- *2024.08*, Kaggle LMSYS Gold Medal(7/1849).



Services
--------
<!--
- *3026.06 – Present*, Chief Coffee Consumption Officer, Midnight Research Lab.
- *3026.01 – Present*, Full-time Debugger of Problems Created by Myself.
  -->
- Reviewer for AAAI 2026 Workshop on AI for Urban Planning.




Talks
--------
- Coming Soon.