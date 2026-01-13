
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
    max-width: 1100px; /* 首頁稍微寬一點以容納三欄佈局 */
    margin: 0 auto;
    padding: 40px 20px;
}

/* 標題樣式 */
.section-title {
    text-align: center;
    margin: 50px 0 30px 0;
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

/* 列表與文字樣式優化 */
ul { margin-top: 0; }
li { margin-bottom: 5px; }
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

<!-- Hero Section: 實驗室願景 -->
<table style="width:100%; border:none; border-collapse:collapse; margin-bottom:40px; background:linear-gradient(to right, #f8f9fa, #fff); border-radius:8px;">
<tr style="border:none;">
<td style="padding:40px 20px; text-align:center; border:none;">
<h1 style="margin:0 0 10px 0; font-size:2.2em; color:#2c3e50;">Intelligent Information Service Research Lab (IISR)</h1>
<div style="font-size:1.1em; color:#666; margin-bottom:25px; font-weight:300;">
Bridging <b>LLMs</b>, <b>Data-centric AI</b>, and <b>Humanities</b> for Practical Solutions
</div>
<div style="max-width:800px; margin:0 auto; line-height:1.6; color:#444; background:#fff; padding:20px; border-left:4px solid #3498db; border-radius:4px; box-shadow:0 2px 5px rgba(0,0,0,0.05); text-align:left;">
We develop <b>practical and verifiable AI systems</b>, combining <b>Retrieval (RAG)</b> and <b>Cross-domain Representation Learning</b> to solve challenges in biomedical texts, low-resource languages, and historical archives.
</div>
</td>
</tr>
</table>

<!-- Three Pillars: LLM (左) -> Bio (中) -> DH (右) -->
<table style="width:100%; border:none; border-collapse:separate; border-spacing:15px; margin-bottom:40px; table-layout: fixed;">
<tr style="border:none;">

<!-- Pillar 1 (Left): Localized LLMs -->
<td style="width:33%; vertical-align:top; background:#fff; border:1px solid #eee; border-radius:8px; padding:20px; box-shadow:0 2px 4px rgba(0,0,0,0.03);">
<div style="font-size:2em; margin-bottom:10px;">🇹🇼</div>
<h3 style="margin-top:0; color:#2980b9;">Localized LLMs</h3>
<div style="font-size:0.9em; color:#555; margin-bottom:15px; line-height:1.5;">
Efficient alignment for new languages, cultural benchmarks, and low-resource adaptation.
</div>
<div style="background:#e8f4fd; color:#2980b9; padding:5px 10px; border-radius:4px; font-size:0.85em; font-weight:bold; display:inline-block;">
📄 ACL / EMNLP
</div>
<ul style="padding-left:20px; margin-top:15px; color:#666; font-size:0.9em;">
<li>Chat Vector (Alignment)</li>
<li>TWBias (Cultural Benchmark)</li>
<li>Low-Resource (Hokkien)</li>
</ul>
</td>

<!-- Pillar 2 (Center): BioNLP -->
<td style="width:33%; vertical-align:top; background:#fff; border:1px solid #eee; border-radius:8px; padding:20px; box-shadow:0 2px 4px rgba(0,0,0,0.03);">
<div style="font-size:2em; margin-bottom:10px;">🧬</div>
<h3 style="margin-top:0; color:#27ae60;">Biomedical NLP</h3>
<div style="font-size:0.9em; color:#555; margin-bottom:15px; line-height:1.5;">
Data-centric, privacy-aware clinical text mining and evidence-grounded QA.
</div>
<div style="background:#eafaf1; color:#27ae60; padding:5px 10px; border-radius:4px; font-size:0.85em; font-weight:bold; display:inline-block;">
🏆 BioASQ Champion (6 yrs)
</div>
<ul style="padding-left:20px; margin-top:15px; color:#666; font-size:0.9em;">
<li>Relation Extraction</li>
<li>De-identification</li>
<li>Temporal Normalization</li>
</ul>
</td>

<!-- Pillar 3 (Right): Digital Humanities -->
<td style="width:33%; vertical-align:top; background:#fff; border:1px solid #eee; border-radius:8px; padding:20px; box-shadow:0 2px 4px rgba(0,0,0,0.03);">
<div style="font-size:2em; margin-bottom:10px;">🗺️</div>
<h3 style="margin-top:0; color:#c0392b;">Digital Humanities</h3>
<div style="font-size:0.9em; color:#555; margin-bottom:15px; line-height:1.5;">
Historical GIS, context-aware representation, and label-free map understanding.
</div>
<div style="background:#fdedec; color:#c0392b; padding:5px 10px; border-radius:4px; font-size:0.85em; font-weight:bold; display:inline-block;">
📄 IJGIS / EMNLP
</div>
<ul style="padding-left:20px; margin-top:15px; color:#666; font-size:0.9em;">
<li>MingOfficial (Context)</li>
<li>Map Understanding (UDA)</li>
<li>Long-document RAG</li>
</ul>
</td>

</tr>
</table>

<div style="text-align:right; margin-top:-20px; margin-bottom:40px;">
<a href="research.html" style="text-decoration:none; font-weight:bold; color:#3498db;">Explore Research Details →</a>
</div>

<!-- Selected Highlights -->
<h2 class="section-title">✨ Selected Highlights</h2>

<table style="width:100%; border:none; border-collapse:collapse; margin-bottom:30px;">
<tr style="border:none;">
<td style="border:none; padding:8px 0; vertical-align:top; width: 120px;">
<span style="background:#333; color:#fff; padding:3px 8px; border-radius:4px; font-size:0.75em; margin-right:10px; white-space:nowrap;">ACL 2024</span>
</td>
<td style="border:none; padding:8px 0;">
<b>Chat Vector:</b> A parameter-efficient alignment strategy to equip LLMs with instruction-following capabilities in new languages.
</td>
</tr>
<tr style="border:none;">
<td style="border:none; padding:8px 0; vertical-align:top;">
<span style="background:#333; color:#fff; padding:3px 8px; border-radius:4px; font-size:0.75em; margin-right:10px; white-space:nowrap;">EMNLP 2024</span>
</td>
<td style="border:none; padding:8px 0;">
<b>TWBias:</b> The first Taiwan cultural lens benchmark for detecting social bias in Traditional Chinese LLMs.
</td>
</tr>
<tr style="border:none;">
<td style="border:none; padding:8px 0; vertical-align:top;">
<span style="background:#333; color:#fff; padding:3px 8px; border-radius:4px; font-size:0.75em; margin-right:10px; white-space:nowrap;">IJGIS 2025</span>
</td>
<td style="border:none; padding:8px 0;">
<b>Label-free Map Understanding:</b> Unsupervised domain adaptation for cross-style/cross-year land-use understanding.
</td>
</tr>
<tr style="border:none;">
<td style="border:none; padding:8px 0; vertical-align:top;">
<span style="background:#333; color:#fff; padding:3px 8px; border-radius:4px; font-size:0.75em; margin-right:10px; white-space:nowrap;">npj DigMed</span>
</td>
<td style="border:none; padding:8px 0;">
<b>Clinical De-ID:</b> Discovery of inverse scaling in de-identification beyond 6B parameters and effective PEFT strategies (2025).
</td>
</tr>
<tr style="border:none;">
<td style="border:none; padding:8px 0; vertical-align:top;">
<span style="background:#e67e22; color:#fff; padding:3px 8px; border-radius:4px; font-size:0.75em; margin-right:10px; white-space:nowrap;">CHAMPION</span>
</td>
<td style="border:none; padding:8px 0;">
<b>BioASQ (2020–2025):</b> Six-year consecutive champion in biomedical semantic QA (Retrieval + Evidence-grounding).
</td>
</tr>
</table>

<!-- Impact & Partners -->
<h2 class="section-title">🌏 Impact & Partners</h2>
<p style="text-align:center; color:#666; margin-bottom:30px;">We collaborate with top-tier industry leaders and public sectors to deploy AI in real-world scenarios.</p>

<table style="width:100%; border:none; border-collapse:collapse; margin-top:20px; margin-bottom:30px;">
<tr style="border:none;">
<!-- Industry -->
<td style="width:33%; vertical-align:top; border:none; padding-right:20px;">
<h4 style="margin:0 0 10px 0; color:#555; border-bottom:2px solid #eee; padding-bottom:5px;">🏭 Industry</h4>
<ul style="padding-left:20px; color:#444; margin-top:10px; line-height:1.6;">
<li><b>TSMC:</b> Semiconductor LLMs</li>
<li><b>Google Research:</b> Award Recipient</li>
<li><b>Qualcomm:</b> Research Collaboration</li>
</ul>
</td>
<!-- Public Sector -->
<td style="width:33%; vertical-align:top; border:none; padding-right:20px;">
<h4 style="margin:0 0 10px 0; color:#555; border-bottom:2px solid #eee; padding-bottom:5px;">🏛️ Public Sector</h4>
<ul style="padding-left:20px; color:#444; margin-top:10px; line-height:1.6;">
<li><b>National Central Library:</b> AI Search</li>
<li><b>Taoyuan City Gov:</b> Smart City</li>
<li><b>NCHC / NARLabs:</b> Education AI</li>
</ul>
</td>
<!-- Healthcare -->
<td style="width:33%; vertical-align:top; border:none;">
<h4 style="margin:0 0 10px 0; color:#555; border-bottom:2px solid #eee; padding-bottom:5px;">🏥 Healthcare</h4>
<ul style="padding-left:20px; color:#444; margin-top:10px; line-height:1.6;">
<li><b>Cathay General Hospital</b></li>
<li><b>Landseed Int'l Hospital</b></li>
</ul>
</td>
</tr>
</table>

<!-- Latest News -->
<h2 class="section-title">📢 Latest News</h2>
<div style="background:#fff; padding:20px; border-radius:8px; border:1px solid #eee; box-shadow:0 2px 4px rgba(0,0,0,0.03);">
<ul style="list-style-type: none; padding-left: 0;">
<li style="margin-bottom:10px;"><strong>2025</strong> ｜ 🏆 <strong>BioASQ Champion</strong> (Six consecutive years, 2020–2025)</li>
<li style="margin-bottom:10px;"><strong>2025</strong> ｜ 🎖️ <strong>NSTC Future Tech Award</strong></li>
<li style="margin-bottom:10px;"><strong>2025</strong> ｜ 📄 <em>npj Digital Medicine</em> (Q1): LLMs for clinical de-id accepted.</li>
<li style="margin-bottom:10px;"><strong>2025</strong> ｜ 📄 <em>IJGIS</em> (Q1): Historical map understanding via UDA accepted.</li>
<li style="margin-bottom:10px;"><strong>2024</strong> ｜ 📄 <strong>ACL 2024</strong>: Chat Vector accepted.</li>
<li style="margin-bottom:10px;"><strong>2024</strong> ｜ 📄 <strong>EMNLP 2024</strong>: TWBias accepted.</li>
</ul>
<div style="margin-top:15px;">
<a href="news.html" style="color:#0366d6; font-weight:bold; text-decoration:none;">View All News →</a>
</div>
</div>

<!-- Quick Links -->
<h2 class="section-title">🔗 Quick Links</h2>
<div style="display:flex; gap:15px; margin-top:20px; justify-content:center; flex-wrap:wrap;">
<a href="publications.html" style="background:#f8f9fa; color:#333; padding:12px 25px; border-radius:30px; text-decoration:none; border:1px solid #ddd; font-weight:bold; transition:0.2s;">📚 Publications</a>
<a href="people.html" style="background:#f8f9fa; color:#333; padding:12px 25px; border-radius:30px; text-decoration:none; border:1px solid #ddd; font-weight:bold; transition:0.2s;">👥 People</a>
<a href="opportunities.html" style="background:#3498db; color:#fff; padding:12px 25px; border-radius:30px; text-decoration:none; font-weight:bold; box-shadow:0 4px 10px rgba(52, 152, 219, 0.3);">🚀 Join Us</a>
</div>

</div> <!-- content-wrapper end -->
</div> <!-- custom-body end -->