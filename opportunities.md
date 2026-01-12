
<style>
    body { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif; max-width: 1000px; margin: 0 auto; padding: 20px; line-height: 1.6; color: #333; }
    a { color: #0366d6; text-decoration: none; }
    a:hover { text-decoration: underline; }
    table { width: 100%; border-collapse: collapse; }
    img { max-width: 100%; }
</style>


<!-- HackMD 樣式修正 -->
<style>
/* 讓內容滿版並修正字體 */
.markdown-body { padding: 0 !important; max-width: 100% !important; background-color: #f9f9f9; font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif; }
/* 隱藏 HackMD 預設的連結圖示 */
.markdown-body a.anchor { display: none; }

/* 導航列 */
.nav-bar { background: #fff; text-align: center; padding: 15px 20px; box-shadow: 0 2px 4px rgba(0,0,0,0.05); font-size: 16px; white-space: nowrap; position: sticky; top: 0; z-index: 1000; overflow-x: auto; padding-bottom: 5px; }
.nav-bar a { color: #0366d6; text-decoration: none; margin: 0 5px; padding: 5px; font-weight: 500; }
.nav-bar a:hover { background-color: #f0f7ff; border-radius: 4px; text-decoration: none; }
.nav-sep { color: #ccc; font-size: 14px; margin: 0 2px; }

/* 內容區塊 */
.content-wrapper { max-width: 1000px; margin: 0 auto; padding: 40px 20px; }

/* 標題與排版 */
h1,h2,h3 { color: #2c3e50; border-bottom: none !important; margin-top: 0; }
.section-title { text-align: center; margin-top: 50px; margin-bottom: 30px; font-size: 1.8em; position: relative; font-weight: bold; }
.section-title::after { content: ""; display: block; width: 50px; height: 3px; background: #c0392b; margin: 10px auto 0; }

/* 卡片樣式 */
.card { background: #fff; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.05); padding: 25px; margin-bottom: 20px; border-left: 5px solid #ddd; }
.card-green { border-left-color: #27ae60; }
.card-blue { border-left-color: #002A5C; }
.card-red { border-left-color: #c0392b; }

/* 雙欄排版 (Flexbox) */
.flex-row { display: flex; flex-wrap: wrap; gap: 20px; margin-top: 20px; }
.flex-col { flex: 1; min-width: 300px; background: #fff; padding: 25px; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.05); }
.flex-col-transparent { flex: 1; min-width: 300px; padding: 10px; }

ul { padding-left: 20px; color: #555; }
li { margin-bottom: 6px; }
</style>

<!-- 導航列 -->
<div class="nav-bar">
<a href="index.html">Home</a> <span class="nav-sep">｜</span>
<a href="pi.html">PI</a> <span class="nav-sep">｜</span>
<a href="people.html">People</a> <span class="nav-sep">｜</span>
<a href="research.html">Research</a> <span class="nav-sep">｜</span>
<a href="impact.html">Impact</a> <span class="nav-sep">｜</span>
<a href="collaboration.html">Collab</a> <span class="nav-sep">｜</span>
<a href="publications.html">Pubs</a> <span class="nav-sep">｜</span>
<a href="news.html">News</a> <span class="nav-sep">｜</span>
<a href="opportunities.html">Opportunities</a>
</div>

<!-- 主要內容區 -->
<div class="content-wrapper">

<!-- Hero Intro -->
<div style="text-align:center;margin-bottom:50px;">
<h1 style="margin-bottom:15px;font-size:2.5em;">Join & Collaborate with IISR</h1>
<p style="font-size:1.1em;color:#555;line-height:1.8;max-width:800px;margin:0 auto;">
IISR welcomes motivated students and collaborators to build <b>practical, trustworthy AI systems</b>. Whether you are a prospective student or an industry partner, we invite you to join us in advancing Localized LLMs, BioNLP, and Digital Humanities.
</p>
</div>

<!-- Research Topics -->
<h2 class="section-title">What You Can Work On</h2>

<!-- 1. LLM (Blue) -->
<div class="card card-blue">
<h3 style="margin-top:0;color:#002A5C;">🇹🇼 Taiwan-Localized LLMs & Low-Resource Languages</h3>
<ul>
<li>Efficient alignment and instruction-following for new languages (e.g., Chat Vector-style transfer).</li>
<li>Trustworthy evaluation using culturally grounded benchmarks (e.g., TWBias).</li>
<li>Hokkien translation / generation and multimodal learning applications (e.g., ATAIGI).</li>
</ul>
</div>

<!-- 2. BioNLP (Green) -->
<div class="card card-green">
<h3 style="margin-top:0;color:#27ae60;">🧬 Biomedical NLP (BioNLP)</h3>
<ul>
<li>Data-centric learning for noisy biomedical datasets (e.g., relation extraction).</li>
<li>Privacy-preserving clinical NLP (de-identification, temporal normalization).</li>
<li>Evidence-grounded biomedical QA (retrieval + generation).</li>
</ul>
</div>

<!-- 3. DH (Red) -->
<div class="card card-red">
<h3 style="margin-top:0;color:#c0392b;">🗺️ Digital Humanities & Historical GIS</h3>
<ul>
<li>Context-aware representations for historical entities and trajectories (e.g., MingOfficial).</li>
<li>Domain adaptation for unlabeled historical maps.</li>
<li>Long-document RAG with traceability and human-in-the-loop evaluation.</li>
</ul>
</div>

<!-- Values & Skills -->
<div class="flex-row">
<div class="flex-col">
<h3 style="margin-top:0;">🌟 What We Value</h3>
<ul>
<li><b>Curiosity</b> and strong ownership.</li>
<li><b>Reproducibility mindset</b> (clean experiments, careful evaluation, readable code).</li>
<li><b>Collaboration</b> and the ability to iterate with real stakeholders.</li>
</ul>
</div>
<div class="flex-col">
<h3 style="margin-top:0;">🛠️ Recommended Skills</h3>
<ul>
<li><b>Python</b> (required), <b>PyTorch</b> (preferred).</li>
<li>IR/NLP/ML fundamentals; comfort reading papers.</li>
<li><b>Bonus:</b> Information retrieval, LLM evaluation, data engineering, or GIS.</li>
</ul>
</div>
</div>

<!-- Application Process -->
<h2 class="section-title">How to Apply (Students/RAs)</h2>
<div style="background:#e8f4fd;border-left:5px solid #3498db;padding:25px;border-radius:6px;color:#333;">
<p style="margin-top:0;">Please email the following materials to Prof. Richard Tzong-Han Tsai:</p>
<ul style="margin-bottom:20px;">
<li><b>CV / Resume</b></li>
<li><b>Short Statement</b> (≤ 1 page): Research interests, skills, and available time.</li>
<li><b>(Optional)</b> Transcript, publications, or portfolio (GitHub, demos).</li>
</ul>
<div style="background:#fff;padding:15px;border-radius:4px;border:1px dashed #ccc;">
<b>📧 Email:</b> <a href="mailto:thtsai@g.ncu.edu.tw">thtsai@g.ncu.edu.tw</a><br>
<b>📝 Subject:</b> <code>[IISR] Application – Your Name – PhD/MS/RA/Intern</code>
</div>
</div>

<!-- Collaboration & Contact -->
<h2 class="section-title">Collaboration & Contact</h2>
<p style="text-align:center;color:#555;margin-bottom:30px;">
We actively collaborate with academia, hospitals, national institutions, and industry partners (e.g., semiconductor, public sector, education).
</p>

<div class="flex-row">
<div class="flex-col-transparent">
<h3 style="margin-top:0;">📍 Lab Location</h3>
<p style="line-height:1.8;color:#555;">
<b>National Central University</b><br>
Engineering Building 5, Room A305 (工程五館 A305室)<br>
No. 300, Zhongda Rd., Zhongli District,<br>
Taoyuan City 32001, Taiwan
</p>
</div>
<div class="flex-col-transparent">
<!-- Google Maps Embed -->
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3617.2660142916845!2d121.1908233150064!3d24.96980398400262!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x346823c18c356981%3A0x633519c13e4b785!2z5ZyL56uL5Lit5aSu5aSn5a245bel56iL5Zub6aSo!5e0!3m2!1szh-TW!2stw!4v1626338888888!5m2!1szh-TW!2stw" width="100%" height="250" style="border:0;border-radius:8px;" allowfullscreen="" loading="lazy"></iframe>
</div>
</div>

</div>