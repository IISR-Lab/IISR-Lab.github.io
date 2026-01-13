
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

/* 標題與卡片 */
.section-title {
    text-align: center;
    margin: 60px 0 40px 0;
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

/* 列表容器樣式 */
.list-container {
    background: #fff;
    border-radius: 10px;
    padding: 40px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.08);
    border: 1px solid #eee;
    margin-bottom: 40px;
}

/* 論文列表樣式 */
.pub-list {
    padding-left: 20px;
    margin: 0;
}
.pub-item {
    margin-bottom: 25px;
    line-height: 1.7;
    color: #444;
}
.pub-title {
    font-weight: bold;
    color: #2c3e50;
    font-size: 1.05em;
    display: block;
    margin-bottom: 4px;
}
.pub-authors {
    color: #555;
    font-size: 0.95em;
    margin-bottom: 4px;
    display: block;
}
.pub-venue {
    font-style: italic;
    color: #c0392b;
    font-weight: 500;
}
.highlight-author {
    font-weight: bold;
    color: #000;
    text-decoration: underline;
    text-decoration-color: #ccc;
}

/* 其他元件 */
.tip-box {
    background-color: #f0f7ff;
    border-left: 5px solid #0366d6;
    padding: 15px;
    margin-top: 40px;
    color: #555;
    font-size: 0.9em;
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

<!-- 主標題 (替代 Hero Banner) -->
<h1 style="text-align:center; color:#2c3e50; margin-bottom:40px; font-size:2.5em;">
Publications <span style="font-size:0.6em; color:#7f8c8d; font-weight:normal; display:block; margin-top:10px;">(Selected, 2021–2025)</span>
</h1>

<!-- Journals / Top Conferences -->
<h2 class="section-title" style="margin-top:0;">Journals / Top Conferences</h2>
<div class="list-container">
<ol class="pub-list">
<li class="pub-item">
<span class="pub-title">Enhancing biomedical relation extraction through data-centric and preprocessing-robust ensemble learning approach</span>
<span class="pub-authors">Wilailack Meesawad, Jen-Chieh Han, Chun-Yu Hsueh, Yu Zhang, Hsi-Chuan Hung, <span class="highlight-author">Richard Tzong-Han Tsai*</span>.</span>
<span class="pub-venue">Database, 2025. (SCI, Q1)</span>
</li>

<li class="pub-item">
<span class="pub-title">Surveying biomedical relation extraction: a critical examination of current datasets and the proposal of a new resource</span>
<span class="pub-authors">Ming-Siang Huang, Jen-Chieh Han, Pei-Yen Lin, Yu-Ting You, <span class="highlight-author">Richard Tzong-Han Tsai*</span>, Wen-Lian Hsu.</span>
<span class="pub-venue">Briefings in Bioinformatics, 2024. (SCI, Q1)</span>
</li>

<li class="pub-item">
<span class="pub-title">Leveraging large language models for the deidentification and temporal normalization of sensitive health information in electronic health records</span>
<span class="pub-authors">Hong-Jie Dai, …, <span class="highlight-author">Richard Tzong-Han Tsai</span>, et al.</span>
<span class="pub-venue">npj Digital Medicine, 2025. (SCI, Q1)</span>
</li>

<li class="pub-item">
<span class="pub-title">Chat Vector: A Simple Approach to Equip LLMs with Instruction Following and Model Alignment in New Languages</span>
<span class="pub-authors">Shih-Cheng Huang, Pin-Zu Li, Yu-Chi Hsu, Kuang-Ming Chen, Yu-Tung Lin, Shih-Kai Hsiao, <span class="highlight-author">Richard Tzong-Han Tsai</span>, Hung-yi Lee.</span>
<span class="pub-venue">ACL 2024. (Top conference)</span>
</li>

<li class="pub-item">
<span class="pub-title">TWBias: A benchmark for assessing social bias in traditional Chinese large language models through a Taiwan cultural lens</span>
<span class="pub-authors">Hsin-Yi Hsieh, Shih-Cheng Huang, <span class="highlight-author">Richard Tzong-Han Tsai*</span>.</span>
<span class="pub-venue">EMNLP 2024. (Top conference)</span>
</li>

<li class="pub-item">
<span class="pub-title">Enhancing Taiwanese Hokkien Dual Translation by Exploring and Standardizing of Four Writing Systems</span>
<span class="pub-authors">Bo-Han Lu, Yi-Hsuan Lin, En-Shiun Annie Lee, <span class="highlight-author">Richard Tzong-Han Tsai*</span>.</span>
<span class="pub-venue">COLING 2024. (Top conference)</span>
</li>

<li class="pub-item">
<span class="pub-title">ATAIGI: An AI-Powered Multimodal Learning App Leveraging Generative Models for Low-Resource Taiwanese Hokkien</span>
<span class="pub-authors">Yun-Hsin Chu, Shuai Zhu, Shou-Yi Hung, Bo-Ting Lin, En-Shiun Annie Lee, <span class="highlight-author">Richard Tzong-Han Tsai*</span>.</span>
<span class="pub-venue">NAACL/HLT 2025. (Top conference)</span>
</li>

<li class="pub-item">
<span class="pub-title">MingOfficial: A Ming Official Career Dataset and a Historical Context-Aware Representation Learning Framework</span>
<span class="pub-authors">You-Jun Chen, Hsin-Yi Hsieh, Yu Lin, Yingtao Tian, Bert Chan, Yu-Sin Liu, Yi-Hsuan Lin, <span class="highlight-author">Richard Tzong-Han Tsai*</span>.</span>
<span class="pub-venue">EMNLP 2023. (Top conference)</span>
</li>

<li class="pub-item">
<span class="pub-title">Unsupervised domain adaptation for cross-style, cross-year land use understanding from historical maps</span>
<span class="pub-authors">Jun-Hua Wang, Andy Da-Yu Wang, Hsiung-Ming Liao, Ming-Ching Chang, <span class="highlight-author">Richard Tzong-Han Tsai*</span>.</span>
<span class="pub-venue">International Journal of Geographical Information Science, 2025. (SCI, Q1)</span>
</li>

<li class="pub-item">
<span class="pub-title">Digital humanities approach to analyzing the roles and military power of Supreme Commanders and Grand Coordinators in the Ming Dynasty: a computational analysis of Ming Shilu</span>
<span class="pub-authors"><span class="highlight-author">Richard Tzong-Han Tsai*</span>, Yu-Sin Liu, You-Jun Chen, Hsin-Yi Hsieh, Ya-Chi Chan.</span>
<span class="pub-venue">Digital Scholarship in the Humanities, 2025. (SSCI, Scopus Q1)</span>
</li>
</ol>
</div>

<!-- Books -->
<h2 class="section-title">Books (Popular Science)</h2>
<div class="list-container">
<ul class="pub-list">
<li class="pub-item">
<span class="pub-title">《寫給小學生看的AI課：看故事，輕鬆搞懂AI人工智慧》</span>
<span class="pub-authors"><span class="highlight-author">蔡宗翰</span> (2023). 三采文化.</span>
</li>
<li class="pub-item">
<span class="pub-title">《寫給中學生看的AI課：AI生態系需要文理兼具的未來人才》</span>
<span class="pub-authors"><span class="highlight-author">蔡宗翰</span> (2022). 三采文化.</span>
<span class="pub-venue" style="display:block; margin-top:5px; font-size:0.9em; color:#e67e22;">(Wu Ta-You Pop Sci Award — Youth Special Prize)</span>
</li>
</ul>
</div>

<!-- Competitions -->
<h2 class="section-title">Competitions (Selected)</h2>
<div class="list-container">
<ul class="pub-list">
<li class="pub-item">
<span class="pub-title">BioASQ International Biomedical QA Challenge</span>
<span class="pub-venue" style="font-weight:bold; color:#27ae60;">Champion (2020–2025, six consecutive years)</span>
</li>
<li class="pub-item">
<span class="pub-title">BioCreative VII (NIH)</span>
<span class="pub-venue" style="font-weight:bold; color:#27ae60;">1st place (Track 3), 2021</span>
</li>
</ul>
</div>

<!-- Tip -->
<div class="tip-box">
<strong>💡 Tip:</strong> Add PDF/Code links later by appending “｜[PDF](...)｜[Code](...)” to each entry.
</div>

<div style="text-align:center;margin-top:60px;">
<a href="index.html" style="background:#2c3e50;color:#fff;padding:12px 30px;border-radius:30px;text-decoration:none;font-weight:bold;box-shadow:0 4px 10px rgba(0,0,0,0.2);">← Back to Home</a>
</div>

</div> <!-- content-wrapper end -->
</div> <!-- custom-body end -->