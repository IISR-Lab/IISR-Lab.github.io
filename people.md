
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

/* 成員卡片容器 */
.team-container {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: flex-start;
}

/* 成員卡片樣式 */
.person-card {
    background: #fff;
    border: 1px solid #eee;
    border-radius: 8px;
    padding: 25px;
    width: calc(50% - 10px);
    box-shadow: 0 2px 5px rgba(0,0,0,0.05);
    box-sizing: border-box;
    transition: transform 0.2s;
}
.person-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}
.person-name {
    font-size: 1.2em;
    font-weight: bold;
    color: #2c3e50;
    margin-bottom: 5px;
    border-bottom: 2px solid #3498db;
    display: inline-block;
    padding-bottom: 3px;
}
.person-role {
    font-size: 0.9em;
    color: #e67e22;
    font-weight: bold;
    margin-bottom: 10px;
    display: block;
}
.person-desc {
    font-size: 0.95em;
    color: #555;
    line-height: 1.5;
}

/* 手機版改為單欄 */
@media (max-width: 768px) {
    .person-card {
        width: 100%;
    }
}

/* Alumni 區塊樣式 */
.alumni-box {
    background: #fff;
    border-left: 5px solid #27ae60;
    padding: 30px;
    border-radius: 5px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.05);
    font-size: 1.05em;
    color: #444;
    line-height: 1.8;
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

<!-- PI Summary Card -->
<table style="width:100%; border:none; border-collapse:collapse; margin-bottom:40px; border-bottom:1px solid #eee; padding-bottom:30px; background:#fff; border-radius:10px; padding:20px; box-shadow:0 2px 10px rgba(0,0,0,0.05);">
<tr style="border:none; background:transparent;">
<td style="width:70%; vertical-align:top; border:none; padding:30px;">
<div style="color:#888; font-size:0.85em; font-weight:bold; letter-spacing:1px; margin-bottom:5px;">PRINCIPAL INVESTIGATOR</div>
<h2 style="margin:0 0 10px 0; border:none; font-size:2.2em; color:#2c3e50;">Richard Tzong-Han Tsai <span style="font-size:0.6em; color:#7f8c8d; font-weight:normal;">(蔡宗翰)</span></h2>
<div style="font-size:1em; color:#444; line-height:1.6; margin-bottom:20px;">
<div><b>Professor</b>, CSIE, National Central University</div>
<div><b>Joint Professor</b>, GIL, National Taiwan University</div>
<div><b>Joint Research Fellow</b>, RCHSS, Academia Sinica</div>
</div>

<!-- 研究領域 -->
<div style="margin-bottom:25px;">
<div style="font-weight:bold; margin-bottom:8px; font-size:0.9em; color:#555;">Research Areas:</div>
<span style="background:#f0f0f0; padding:4px 12px; border-radius:15px; font-size:0.85em; margin:0 5px 5px 0; display:inline-block; color:#444; border:1px solid #ddd;">LLM Benchmarking</span>
<span style="background:#f0f0f0; padding:4px 12px; border-radius:15px; font-size:0.85em; margin:0 5px 5px 0; display:inline-block; color:#444; border:1px solid #ddd;">Localized LLMs</span>
<span style="background:#f0f0f0; padding:4px 12px; border-radius:15px; font-size:0.85em; margin:0 5px 5px 0; display:inline-block; color:#444; border:1px solid #ddd;">Biomedical NLP</span>
<span style="background:#f0f0f0; padding:4px 12px; border-radius:15px; font-size:0.85em; margin:0 5px 5px 0; display:inline-block; color:#444; border:1px solid #ddd;">Digital Humanities</span>
</div>

<!-- 核心連結區 -->
<div style="display:flex; flex-wrap:wrap; gap:10px; align-items:center;">
<a href="mailto:thtsai@g.ncu.edu.tw" style="text-decoration:none; color:#333; border:1px solid #ddd; padding:6px 15px; border-radius:4px; font-size:0.9em; display:flex; align-items:center; background:#f9f9f9;">✉️ Email</a>
<a href="https://scholar.google.com/citations?user=iDz3gJ4AAAAJ&hl=zh-TW" target="_blank" style="text-decoration:none; color:#333; border:1px solid #ddd; padding:6px 15px; border-radius:4px; font-size:0.9em; display:flex; align-items:center; background:#f9f9f9;">🎓 Google Scholar</a>
<a href="pi.html" style="text-decoration:none; background:#2c3e50; color:#fff; border:1px solid #2c3e50; padding:6px 18px; border-radius:4px; font-size:0.9em; font-weight:bold; display:flex; align-items:center; box-shadow:0 2px 5px rgba(0,0,0,0.2);">👤 View Full Profile & CV →</a>
</div>

</td>
<td style="width:30%; vertical-align:middle; border:none; text-align:center; padding:20px;">
<img src="https://hackmd.io/_uploads/HkpGJ4TVWl.jpg" style="width:100%; max-width:200px; border-radius:8px; box-shadow:0 4px 15px rgba(0,0,0,0.15); border:4px solid #fff;">
</td>
</tr>
</table>

<!-- Staff Section -->
<h2 class="section-title">Staff</h2>
<div class="team-container">
<!-- Herena Wang -->
<div class="person-card">
<div class="person-name">Herena Wang</div>
<span class="person-role">Lab Manager</span>
<div class="person-desc">
Responsible for the <b>Edu TAIDE</b> project. Herena plays a crucial role in managing the laboratory and overseeing the implementation of educational AI tools for teaching.
</div>
</div>

<!-- Jessie Chang -->
<div class="person-card">
<div class="person-name">Jessie Chang</div>
<span class="person-role">Program Manager</span>
<div class="person-desc">
Responsible for the <b>AI CUP</b> project. Jessie oversees Taiwan's largest AI competition, working with various academic institutions to foster AI talent.
</div>
</div>

<!-- Joy Han -->
<div class="person-card">
<div class="person-name">Joy Han</div>
<span class="person-role">Biomedical Research Lead</span>
<div class="person-desc">
Joy leads the lab's biomedical NLP initiatives, applying AI techniques to process and analyze biomedical data, and contributing to research in healthcare AI.
</div>
</div>
</div>

<!-- PhD Students Section -->
<h2 class="section-title">PhD Students</h2>
<div class="team-container">
<!-- Fan-Pin Tseng -->
<div class="person-card">
<div class="person-name">Fan-Pin Tseng</div>
<span class="person-role">Research Topic: Multimodal LLMs in Medicine</span>
<div class="person-desc">
Focuses on applying LLMs to the medical domain. His recent work (IW-DMRN 2024) integrates Longformer and CRF models to enhance patient privacy protection and time information normalization in EHRs.
</div>
</div>

<!-- Kevin Chun-Kai Wu -->
<div class="person-card">
<div class="person-name">Kevin Chun-Kai Wu</div>
<span class="person-role">Research Topic: End-to-end LLM Pretraining</span>
<div class="person-desc">
Researching methods for end-to-end pretraining of LLMs without pre-tokenization, aiming to improve LLM training efficiency and reduce processing time.<br>
<a href="https://orcid.org/0000-0003-4074-9094" target="_blank" style="font-size:0.85em; color:#A6CE39; text-decoration:none; font-weight:bold; margin-top:5px; display:inline-block;">🆔 ORCID</a>
</div>
</div>

<!-- Connyn Kang-Lin Chang -->
<div class="person-card">
<div class="person-name">Connyn Kang-Lin Chang</div>
<span class="person-role">Research Topic: Multimodal LLMs in Finance</span>
<div class="person-desc">
<b>Current Position:</b> Vice President, CTBC Bank (中國信託銀行)<br>
Kang-Lin focuses on applying multimodal LLMs to global financial markets by integrating deep learning, machine learning, and financial time-series data. She explores combining market data, textual disclosures, and macroeconomic signals to enhance trading strategies, risk management, and cross-asset decision-making.
</div>
</div>
</div>

<!-- Alumni Section -->
<h2 class="section-title">Alumni & Outcomes (2021–2025)</h2>
<div class="alumni-box">
<p style="margin:0;">
Our alumni have become key contributors in Taiwan’s AI ecosystem, joining R&D teams at 
<b style="color:#2c3e50;">Google, Qualcomm, TSMC, MediaTek, Delta Electronics, Quanta</b>, and 
<b style="color:#2c3e50;">Chunghwa Telecom Research Institute</b>. 
Many are also pursuing further studies abroad at top institutions such as 
<b style="color:#c0392b;">CMU, Cornell, UIUC, and NYU</b>.
</p>
</div>

<div style="text-align:center;margin-top:60px;">
<a href="index.html" style="background:#2c3e50;color:#fff;padding:12px 30px;border-radius:30px;text-decoration:none;font-weight:bold;box-shadow:0 4px 10px rgba(0,0,0,0.2);">← Back to Home</a>
</div>

</div> <!-- content-wrapper end -->
</div> <!-- custom-body end -->