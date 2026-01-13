
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

/* Thrust 標題樣式 */
.thrust-title {
    font-size: 1.5em;
    color: #2c3e50;
    margin-top: 60px;
    margin-bottom: 15px;
    border-bottom: 2px solid #eee;
    padding-bottom: 10px;
    font-weight: bold;
}

/* 標籤樣式 */
.tag-container {
    margin-bottom: 15px;
}
.tag {
    padding: 4px 10px;
    border-radius: 4px;
    font-weight: bold;
    font-size: 0.85em;
    margin-right: 5px;
    display: inline-block;
    margin-bottom: 5px;
}
.tag-blue { background: #e8f4fd; color: #0366d6; }
.tag-green { background: #eafaf1; color: #27ae60; }
.tag-red { background: #fff5f5; color: #c0392b; }
.tag-gray { background: #f2f2f2; color: #555; }

/* Impact Box 樣式 */
.impact-box {
    padding: 15px;
    border-radius: 4px;
    margin-top: 20px;
    font-size: 0.95em;
}
.impact-blue { background: #f0f7ff; border-left: 4px solid #0366d6; }
.impact-green { background: #f0fdf4; border-left: 4px solid #27ae60; }
.impact-red { background: #fff5f5; border-left: 4px solid #c0392b; }

/* 快速導覽按鈕 */
.quick-nav a {
    background: #fff;
    border: 1px solid #ddd;
    padding: 8px 15px;
    border-radius: 20px;
    color: #333;
    text-decoration: none;
    font-size: 0.9em;
    transition: all 0.2s;
    box-shadow: 0 2px 4px rgba(0,0,0,0.05);
}
.quick-nav a:hover {
    background: #f0f7ff;
    border-color: #0366d6;
    color: #0366d6;
    transform: translateY(-2px);
}

/* 列表樣式優化 */
ul { padding-left: 20px; margin-top: 10px; }
li { margin-bottom: 10px; }
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

<h1 style="text-align:center; color:#2c3e50; margin-bottom:10px;">Research Areas</h1>
<p style="text-align:center; color:#666; max-width:800px; margin:0 auto 30px auto;">
IISR advances intelligent information services through three major thrusts (2021–2025), integrating <b>LLMs</b>, <b>Retrieval (RAG)</b>, <b>Data-centric AI</b>, and <b>Cross-domain Representation Learning</b>.
</p>

<!-- 快速導覽按鈕 -->
<div class="quick-nav" style="display:flex; gap:10px; margin-bottom:40px; flex-wrap:wrap; justify-content:center;">
<a href="#thrust-1">🇹🇼 Localized LLMs</a>
<a href="#thrust-2">🧬 Biomedical NLP</a>
<a href="#thrust-3">🗺️ Digital Humanities</a>
</div>

<hr style="border:0; border-top:1px solid #eee; margin:40px 0;">

<!-- Thrust 1 -->
<a id="thrust-1"></a>
<h2 class="thrust-title">Thrust 1 — Taiwan-Localized LLMs & Low-Resource Languages</h2>

<div class="tag-container">
<span class="tag tag-blue">ACL 2024</span>
<span class="tag tag-blue">EMNLP 2024</span>
<span class="tag tag-blue">NAACL 2025</span>
<span class="tag tag-blue">COLING 2024</span>
</div>

<p><strong>Motivation:</strong> Mainstream LLMs often lack <strong>Traditional Chinese (Taiwan) cultural grounding</strong> and have limited coverage for local languages (e.g., Taiwanese Hokkien).</p>

<h3>🔑 Key Contributions</h3>
<ul>
<li>
<strong>Chat Vector (ACL 2024)</strong> <a href="https://aclanthology.org/2024.acl-long.590/" target="_blank">[📄 Paper]</a> <a href="https://github.com/aqweteddy/ChatVector" target="_blank">[💻 Code]</a><br>
A lightweight, economical alignment technique that transfers instruction-following ability using weight-space additivity—reducing dependence on expensive RLHF.
</li>
<li>
<strong>TWBias (EMNLP 2024)</strong> <a href="https://aclanthology.org/2024.findings-emnlp.507/" target="_blank">[📄 Paper]</a> <a href="https://github.com/hsinmosyi/TWBias" target="_blank">[💻 Code]</a><br>
The first benchmark for assessing social bias in Traditional Chinese LLMs <strong>through a Taiwan cultural lens</strong>, supporting trustworthy evaluation for Taiwan-localized models.
</li>
<li>
<strong>Hokkien NLP & Multimodal Learning</strong>
<ul>
<li>Standardizing and bridging multiple writing systems (<em>COLING 2024</em>). <a href="https://aclanthology.org/2024.lrec-main.538/" target="_blank">[📄 Paper]</a></li>
<li><strong>ATAIGI (NAACL 2025):</strong> A multimodal learning app leveraging generative models for low-resource Hokkien education. <a href="https://aclanthology.org/2025.naacl-demo.2/" target="_blank">[📄 Paper]</a> <a href="https://github.com/LeeLanguageLab/HokkienTranslation" target="_blank">[💻 Code]</a></li>
</ul>
</li>
</ul>

<!-- Impact Box -->
<div class="impact-box impact-blue">
<strong style="color:#0366d6;">Why it matters:</strong><br>
We build <b>methods + benchmarks + applications</b> as a complete stack for localization—going beyond simple "translation-only" pipelines to ensure cultural depth and practical usability.
</div>

<!-- Thrust 2 -->
<a id="thrust-2"></a>
<h2 class="thrust-title">Thrust 2 — Biomedical NLP (BioNLP): Data-Centric & Privacy-Aware</h2>

<div class="tag-container">
<span class="tag tag-green">🏆 BioASQ Champion (6 yrs)</span>
<span class="tag tag-gray">Briefings in Bioinformatics</span>
<span class="tag tag-gray">npj Digital Medicine</span>
<span class="tag tag-gray">Database (Oxford)</span>
</div>

<p><strong>Motivation:</strong> Biomedical data are often <strong>high-noise / low-resource</strong>, and clinical text requires strict privacy protection.</p>

<h3>🔑 Key Contributions</h3>
<ul>
<li>
<strong>BioASQ Biomedical QA (2020–2025)</strong> <a href="http://bioasq.org" target="_blank">[🌐 Project]</a><br>
Achieved <strong>six consecutive years as the top team</strong> in tasks involving evidence retrieval, semantic search, and evidence-grounded answering.
</li>
<li>
<strong>Relation Extraction: Survey & New Resource (PEDD)</strong> <a href="https://academic.oup.com/bib/article/25/3/bbae132/7644532" target="_blank">[📄 Paper]</a> <a href="https://drive.google.com/drive/folders/1BeFkvjdDMPAvY0zdBd59JECZBC-kqpb7" target="_blank">[💾 Data]</a><br>
Proposed <strong>PEDD</strong>, a high-quality document-level dataset originally developed for the <strong>AI CUP 2019</strong> competition, addressing critical inconsistencies in legacy benchmarks (<em>Briefings in Bioinformatics, 2024</em>).
</li>
<li>
<strong>Clinical De-identification & Temporal Normalization with LLMs</strong> <a href="https://www.nature.com/articles/s41746-025-01921-7" target="_blank">[📄 Paper]</a>
<ul>
<li>Discovery of <strong>inverse scaling</strong> beyond ~6B parameters without targeted adaptation (<em>npj Digital Medicine, 2025</em>).</li>
<li>Efficient solution via <strong>PEFT/LoRA</strong>, improving privacy protection while preserving clinical utility.</li>
</ul>
</li>
<li>
<strong>Data-centric Ensemble Learning</strong> <a href="https://doi.org/10.1093/database/baae127" target="_blank">[📄 Paper]</a><br>
<strong>Enhancing biomedical relation extraction through data-centric and preprocessing-robust ensemble learning approach</strong> (<em>Database, 2025</em>).
</li>
</ul>

<!-- Impact Box -->
<div class="impact-box impact-green">
<strong style="color:#27ae60;">Why it matters:</strong><br>
Many global BioNLP systems optimize model architectures on curated datasets; we emphasize <b>real-world robustness</b> and <b>privacy constraints</b>, addressing barriers to actual hospital deployment.
</div>

<!-- Thrust 3 -->
<a id="thrust-3"></a>
<h2 class="thrust-title">Thrust 3 — Digital Humanities & Historical GIS</h2>

<div class="tag-container">
<span class="tag tag-red">IJGIS 2025</span>
<span class="tag tag-red">EMNLP 2023</span>
<span class="tag tag-red">DSH 2025</span>
</div>

<p><strong>Motivation:</strong> Humanities data are frequently <strong>unstructured</strong>, <strong>archaic in language</strong>, and <strong>lack annotations</strong>, making standard supervised learning ineffective.</p>

<h3>🔑 Key Contributions</h3>
<ul>
<li>
<strong>Historical Maps Without Labels (IJGIS 2025)</strong> <a href="https://www.tandfonline.com/doi/full/10.1080/13658816.2024.2425668" target="_blank">[📄 Paper]</a> <a href="https://figshare.com/articles/software/MapStyleSeg_full_code/25560276/1?file=45532515" target="_blank">[💻 Code]</a><br>
<strong>Unsupervised domain adaptation (UDA)</strong> bridging modern labeled maps and historical unlabeled maps for land-use understanding.
</li>
<li>
<strong>MingOfficial (EMNLP 2023)</strong> <a href="https://aclanthology.org/2023.emnlp-main.266/" target="_blank">[📄 Paper]</a> <a href="https://data.depositar.io/dataset/ming_official" target="_blank">[💾 Data (Depository)]</a><br>
A historical context-aware representation learning framework embedding <strong>time, space, and events</strong> into career trajectory representations.
</li>
<li>
<strong>Computational Analysis of Ming Military Power</strong> <a href="https://doi.org/10.1093/llc/fqad088" target="_blank">[📄 Paper]</a> <a href="https://www.sinica.edu.tw/cp/697" target="_blank">[📰 Media (中文)]</a><br>
A digital humanities approach to analyzing the roles of Supreme Commanders and Grand Coordinators in <em>Ming Shilu</em> (<em>Digital Scholarship in the Humanities, 2025</em>).
</li>
<li>
<strong>LLM-based Long-document Analysis</strong><br>
Designing grounded RAG workflows with context fields (metadata + text) and human-in-the-loop benchmarks to improve traceability in historical sources.
</li>
</ul>

<!-- Impact Box -->
<div class="impact-box impact-red">
<strong style="color:#c0392b;">Why it matters:</strong><br>
Instead of applying generic tools, we develop <b>algorithmic methods</b> (like UDA and Context Embedding) that specifically overcome the fundamental "no-label" barrier in historical materials.
</div>

<hr style="border:0; border-top:1px solid #eee; margin:60px 0;">

<!-- Deployment Context -->
<h2 class="section-title" style="margin-top:0;">🚀 Selected Deployment Context</h2>

<table style="width:100%; border-collapse:collapse; margin-top:20px; background:#fff; box-shadow:0 2px 8px rgba(0,0,0,0.05); border-radius:8px; overflow:hidden;">
<tr style="border-bottom:1px solid #eee;">
<td style="padding:15px 20px; width:30%; vertical-align:top; background:#f9f9f9; font-weight:bold; color:#2c3e50;">Semiconductor</td>
<td style="padding:15px 20px;">Domain LLMs for fab operation (<b>TSMC</b>, 2025)</td>
</tr>
<tr style="border-bottom:1px solid #eee;">
<td style="padding:15px 20px; vertical-align:top; background:#f9f9f9; font-weight:bold; color:#2c3e50;">National Scale</td>
<td style="padding:15px 20px;">AI semantic search for theses/dissertations (<b>National Central Library</b>, 2025)</td>
</tr>
<tr style="border-bottom:1px solid #eee;">
<td style="padding:15px 20px; vertical-align:top; background:#f9f9f9; font-weight:bold; color:#2c3e50;">Public / Education</td>
<td style="padding:15px 20px;">Teacher co-planning support with <b>NARLabs / NCHC</b> (2025)</td>
</tr>
<tr style="border-bottom:1px solid #eee;">
<td style="padding:15px 20px; vertical-align:top; background:#f9f9f9; font-weight:bold; color:#2c3e50;">Healthcare</td>
<td style="padding:15px 20px;">Clinical collaborations with <b>Cathay General</b> & <b>Landseed Int'l Hospital</b> (2021–2025)</td>
</tr>
<tr>
<td style="padding:15px 20px; vertical-align:top; background:#f9f9f9; font-weight:bold; color:#2c3e50;">International</td>
<td style="padding:15px 20px;">East Asian multilingual model merging with <b>KISTI</b> (Korea, 2025)</td>
</tr>
</table>

<div style="text-align:center;margin-top:60px;">
<a href="index.html" style="background:#2c3e50;color:#fff;padding:12px 30px;border-radius:30px;text-decoration:none;font-weight:bold;box-shadow:0 4px 10px rgba(0,0,0,0.2);">← Back to Home</a>
</div>

</div> <!-- content-wrapper end -->
</div> <!-- custom-body end -->