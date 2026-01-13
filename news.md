
<style>
    body { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif; max-width: 1000px; margin: 0 auto; padding: 20px; line-height: 1.6; color: #333; }
    a { color: #0366d6; text-decoration: none; }
    a:hover { text-decoration: underline; }
    table { width: 100%; border-collapse: collapse; }
    img { max-width: 100%; }
</style>


<!-- 全域樣式與重置 -->
<style>
/* 強制重置 HackMD 預設樣式，確保全寬 */
.container-fluid, #doc, .markdown-body {
    max-width: 100% !important;
    padding: 0 !important;
    margin: 0 !important;
}
.custom-body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f9f9f9;
    width: 100%;
    margin: 0;
    padding: 0;
}

/* 導覽列 */
.nav-bar {
    background: #fff;
    text-align: center;
    padding: 15px 20px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.05);
    font-size: 16px;
    white-space: nowrap;
    position: sticky;
    top: 0;
    z-index: 1000;
    overflow-x: auto;
}
.nav-bar a {
    color: #0366d6;
    text-decoration: none;
    margin: 0 8px;
    font-weight: 500;
}
.nav-bar a:hover {
    background-color: #f0f7ff;
    border-radius: 4px;
}
.nav-sep { color: #ccc; font-size: 14px; }

/* 內容容器 */
.content-wrapper {
    max-width: 1000px;
    margin: 0 auto;
    padding: 40px 20px;
}

/* 標題樣式 */
.section-title {
    text-align: center;
    margin: 60px 0 30px 0;
    font-size: 1.8em;
    color: #2c3e50;
    font-weight: bold;
    position: relative;
}
.section-title::after {
    content: "";
    display: block;
    width: 60px;
    height: 3px;
    background: #c0392b;
    margin: 15px auto 0;
}

/* 年份標題 */
.year-title {
    font-size: 1.5em;
    color: #0366d6;
    border-bottom: 2px solid #eee;
    padding-bottom: 10px;
    margin-top: 40px;
    margin-bottom: 20px;
    font-weight: bold;
}

/* 列表樣式 */
.news-list {
    list-style: none;
    padding-left: 10px;
}
.news-list li {
    margin-bottom: 12px;
    padding-left: 20px;
    position: relative;
}
.news-list li::before {
    content: "•";
    color: #c0392b;
    font-weight: bold;
    font-size: 1.2em;
    position: absolute;
    left: 0;
    top: -2px;
}

/* 標籤樣式 */
.tag {
    display: inline-block;
    padding: 2px 8px;
    border-radius: 4px;
    font-size: 0.85em;
    font-weight: bold;
    margin-left: 5px;
}
.tag-q1 { background: #e8f4fd; color: #0366d6; }
.tag-award { background: #fff5e6; color: #d35400; }

/* 媒體報導卡片 */
.news-card {
    background: #fff;
    border: 1px solid #eee;
    border-radius: 8px;
    padding: 25px;
    margin-bottom: 30px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.05);
    transition: transform 0.2s;
}
.news-card:hover {
    transform: translateY(-2px);
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}
.news-date {
    display: inline-block;
    background: #2c3e50;
    color: #fff;
    padding: 4px 10px;
    border-radius: 4px;
    font-size: 0.85em;
    font-weight: bold;
    margin-bottom: 10px;
}
.news-source {
    color: #7f8c8d;
    font-weight: bold;
    font-size: 0.9em;
    margin-bottom: 10px;
    display: block;
}
.news-title {
    font-size: 1.3em;
    color: #2c3e50;
    margin: 0 0 10px 0;
    line-height: 1.4;
}
.news-summary {
    color: #555;
    font-size: 0.95em;
    line-height: 1.6;
    margin-bottom: 15px;
}
.read-more-btn {
    display: inline-block;
    color: #0366d6;
    text-decoration: none;
    font-weight: bold;
    font-size: 0.9em;
    border: 1px solid #0366d6;
    padding: 5px 15px;
    border-radius: 20px;
    transition: all 0.2s;
}
.read-more-btn:hover {
    background: #0366d6;
    color: #fff;
}

</style>

<div class="custom-body">

<!-- 導覽列 -->
<div class="nav-bar">
<a href="index.html">Home</a> <span class="nav-sep">|</span>
<a href="pi.html">PI</a> <span class="nav-sep">|</span>
<a href="people.html">People</a> <span class="nav-sep">|</span>
<a href="research.html">Research</a> <span class="nav-sep">|</span>
<a href="impact.html">Impact</a> <span class="nav-sep">|</span>
<a href="collaboration.html">Collab</a> <span class="nav-sep">|</span>
<a href="publications.html">Pubs</a> <span class="nav-sep">|</span>
<a href="news.html">News</a> <span class="nav-sep">|</span>
<a href="opportunities.html">Opportunities</a>
</div>

<div class="content-wrapper">

<h1 style="text-align:center; color:#2c3e50; margin-bottom:10px;">News & Media Coverage</h1>
<p style="text-align:center; color:#666; max-width:800px; margin:0 auto 40px auto;">
Latest updates, awards, and media features from the IISR Lab.
</p>

<!-- Section 1: Academic & Achievement Highlights -->
<h2 class="section-title" style="margin-top:0;">🏆 Highlights</h2>

<div class="year-title">2025</div>
<ul class="news-list">
    <li><strong>BioASQ Champion (2020–2025)</strong> — six consecutive years as the top team.</li>
    <li><strong>NSTC Future Tech Award</strong> — award recipient. <span class="tag tag-award">Award</span></li>
    <li><em>npj Digital Medicine</em> — LLMs for clinical de-identification & temporal normalization. <span class="tag tag-q1">Q1</span></li>
    <li><em>IJGIS</em> — label-free historical map land-use understanding via unsupervised domain adaptation. <span class="tag tag-q1">Q1</span></li>
    <li><em>Digital Scholarship in the Humanities</em> — computational analysis of Ming Shilu. <span class="tag tag-q1">Q1</span></li>
    <li><em>Database</em> — data-centric ensemble learning for biomedical relation extraction. <span class="tag tag-q1">Q1</span></li>
    <li>Industry: <strong>TSMC</strong> — semiconductor-specific LLM for fab operation.</li>
    <li>Industry: <strong>Qualcomm</strong> — research collaboration agreement.</li>
    <li>Recognition: <strong>Google Research Award</strong> (2023–2024; continued impact into 2025 deployments).</li>
    <li>National-scale: <strong>National Central Library</strong> — AI semantic search engine for theses/dissertations.</li>
    <li>Public sector & education: teacher co-planning support with <strong>NARLabs/NCHC</strong>.</li>
    <li>Smart city: <strong>Taoyuan City Government</strong> pilot program.</li>
</ul>

<div class="year-title">2024</div>
<ul class="news-list">
    <li><strong>ACL 2024</strong> — Chat Vector.</li>
    <li><strong>EMNLP 2024</strong> — TWBias.</li>
    <li><strong>COLING 2024</strong> — Hokkien writing system standardization for dual translation.</li>
    <li><strong>Google Research Award</strong>. <span class="tag tag-award">Award</span></li>
    <li>Recognition: <strong>Taiwan AI 20</strong> (CommonWealth Magazine).</li>
    <li>Award: <strong>Wu Ta-You Pop Sci Award — Youth Special Prize</strong> (for the middle-school AI book). <span class="tag tag-award">Award</span></li>
</ul>

<div class="year-title">2023</div>
<ul class="news-list">
    <li><strong>EMNLP 2023</strong> — MingOfficial.</li>
    <li><strong>Google Research Award</strong>. <span class="tag tag-award">Award</span></li>
    <li>Continued BioASQ top performance.</li>
</ul>

<div class="year-title">2022</div>
<ul class="news-list">
    <li>Book published: 《寫給中學生看的AI課》.</li>
</ul>

<!-- Section 2: Media Coverage -->
<h2 class="section-title">📰 Media Coverage</h2>

<!-- News 1 -->
<div class="news-card">
    <div class="news-date">2025-12-27</div>
    <span class="news-source">財團法人中技社 (CTCI Foundation)</span>
    <h3 class="news-title">中技社AI創意競賽 第二名：Ataigi學台語App<br><span style="font-size:0.8em; color:#666; font-weight:normal;">Second Place in CTCI AI Creative Competition: Ataigi Hokkien Learning App</span></h3>
    <div class="news-summary">
        在2025年12月27日舉行的中技社AI創意競賽中，我們的Ataigi學台語App項目榮獲第二名。該應用旨在使用生成式AI技術協助台語學習，特別針對低資源語言處理做出突破。<br>
        <span style="color:#888; font-size:0.9em;">(Our project Ataigi Hokkien Learning App won second place, using GenAI to assist in learning Taiwanese Hokkien with breakthroughs in low-resource language processing.)</span>
    </div>
    <a href="https://www.ctci.org.tw/8838/talent/41184/46012/46132/" target="_blank" class="read-more-btn">Read Full Article →</a>
</div>

<!-- News 2 -->
<div class="news-card">
    <div class="news-date">2025-12-18</div>
    <span class="news-source">財團法人中技社 (CTCI Foundation)</span>
    <h3 class="news-title">生成式AI應用：從理解到落地 研討會紀要<br><span style="font-size:0.8em; color:#666; font-weight:normal;">Generative AI Applications: From Understanding to Implementation - Seminar Summary</span></h3>
    <div class="news-summary">
        中技社舉辦的生成式AI產業研討會邀請多位學界與業界專家分享技術趨勢與實務導入，其中蔡宗翰理事長（中華民國人工智慧學會）等專家出席並發表演講。<br>
        <span style="color:#888; font-size:0.9em;">(CTCI hosted a seminar on GenAI trends and implementation, featuring a speech by President Richard Tzong-Han Tsai of the Taiwan Association for AI.)</span>
    </div>
    <a href="https://www.ctci.org.tw/8838/research/9483/46229/" target="_blank" class="read-more-btn">Read Full Article →</a>
</div>

<!-- News 3 -->
<div class="news-card">
    <div class="news-date">2025-10-29</div>
    <span class="news-source">聯合新聞網 (United Daily News)</span>
    <h3 class="news-title">15秒就能改一篇！教育部Write AI系統助力評閱高中作文<br><span style="font-size:0.8em; color:#666; font-weight:normal;">15 Seconds to Improve an Essay! MOE's Write AI System Assists Grading</span></h3>
    <div class="news-summary">
        教育部推動人工智慧技術於教育領域創新應用，Write AI 評閱工具能在約15秒內為教師提供作文結構建議和語意分析。該系統由國立中央大學資訊工程系蔡宗翰教授團隊共同參與研發與推廣。<br>
        <span style="color:#888; font-size:0.9em;">(The MOE's Write AI tool, co-developed by Prof. Tsai's team at NCU, provides structural and semantic feedback on essays in 15 seconds, improving review efficiency.)</span>
    </div>
    <a href="https://udn.com/news/story/6885/9104622" target="_blank" class="read-more-btn">Read Full Article →</a>
</div>

<div style="text-align:center;margin-top:60px;">
<a href="index.html" style="background:#2c3e50;color:#fff;padding:12px 30px;border-radius:30px;text-decoration:none;font-weight:bold;box-shadow:0 4px 10px rgba(0,0,0,0.2);">← Back to Home</a>
</div>

</div> <!-- content-wrapper end -->
</div> <!-- custom-body end -->