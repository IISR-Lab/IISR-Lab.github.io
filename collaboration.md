
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
    max-width: 1100px;
    margin: 0 auto;
    padding: 40px 20px;
}

/* 標題設定 */
.section-title {
    text-align: center;
    margin-top: 60px;
    margin-bottom: 40px;
    font-size: 2em;
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

/* Hero Banner */
.hero-banner {
    background: linear-gradient(135deg, #003366 0%, #005b96 100%);
    color: white;
    padding: 80px 20px;
    text-align: center;
    margin-bottom: 50px;
}

/* 卡片與元件樣式 */
.featured-project {
    background: #fff;
    border-radius: 12px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.1);
    overflow: hidden;
    margin-bottom: 60px;
    border: 1px solid #eee;
    border-left: 6px solid #c0392b;
}
.featured-content {
    padding: 40px;
}

.industry-card {
    background: #fff;
    border-radius: 10px;
    padding: 30px;
    margin-bottom: 30px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.08);
    border: 1px solid #eee;
    display: flex;
    flex-wrap: wrap;
    gap: 30px;
    transition: transform 0.2s;
}
.industry-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 8px 20px rgba(0,0,0,0.1);
}
.industry-logo-area {
    flex: 0 0 150px;
    display: flex;
    align-items: center;
    justify-content: center;
    border-right: 1px solid #eee;
    padding-right: 30px;
}
/* 手機版調整 Logo 區域 */
@media (max-width: 768px) {
    .industry-logo-area {
        flex: 0 0 100%;
        border-right: none;
        border-bottom: 1px solid #eee;
        padding-right: 0;
        padding-bottom: 20px;
    }
}
.industry-content {
    flex: 1;
    min-width: 300px;
}

.outcome-tag {
    display: inline-block;
    background: #f0f7ff;
    color: #0366d6;
    padding: 3px 10px;
    border-radius: 4px;
    font-size: 0.85em;
    font-weight: bold;
    margin-right: 5px;
    margin-bottom: 5px;
}

.card-container {
    display: flex;
    flex-wrap: wrap;
    gap: 25px;
    justify-content: center;
}
.card {
    background: #fff;
    border-radius: 10px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.08);
    padding: 30px;
    flex: 1;
    min-width: 280px;
    border-top: 5px solid #ddd;
}

.btn-primary {
    display: inline-block;
    background: #c0392b;
    color: white !important;
    padding: 12px 30px;
    border-radius: 30px;
    text-decoration: none;
    font-weight: bold;
    box-shadow: 0 4px 10px rgba(192,57,43,0.3);
    transition: transform 0.2s;
}
.btn-primary:hover { transform: translateY(-2px); }

.btn-secondary {
    display: inline-block;
    margin-top: 15px;
    color: #0366d6;
    font-weight: bold;
    border: 1px solid #0366d6;
    padding: 8px 20px;
    border-radius: 20px;
    text-decoration: none;
    transition: all 0.2s;
}
.btn-secondary:hover { background: #0366d6; color: white; }

ul { padding-left: 20px; color: #555; margin-top: 0; }
li { margin-bottom: 8px; }
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

<!-- Hero Section -->
<div class="hero-banner">
<h1 style="margin:0 0 15px 0;font-size:3em;line-height:1.2;">Global Research Network</h1>
<p style="font-size:1.3em;margin-top:20px;opacity:0.9;font-weight:300;color:#ecf0f1;">Bridging Taiwan with the World through AI Innovation</p>
</div>

<!-- 主要內容區 -->
<div class="content-wrapper">

<!-- 1. Academic Flagship -->
<div class="featured-project">
<div class="featured-content">
<div style="color:#c0392b;font-weight:bold;letter-spacing:1px;margin-bottom:10px;font-size:0.9em;">ACADEMIC FLAGSHIP</div>
<h2 style="margin-top:0;font-size:2em;color:#2c3e50;line-height:1.3;">TAP: Taiwan-Canada<br>AI Partnership</h2>
<p style="font-size:1.1em;color:#555;margin-bottom:25px;line-height:1.8;">
A multi-year collaboration between <b>IISR Lab (Taiwan)</b> and the <b>University of Toronto (Canada)</b>. We are building multimodal generative AI to revitalize low-resource languages, featuring the award-winning <b>ATAIGI</b> system.
</p>
<ul style="margin-bottom:30px;color:#666;">
<li><b>Partners:</b> University of Toronto, Ontario Tech University</li>
<li><b>Focus:</b> Neural Machine Translation, Multimodal Learning</li>
<li><b>Achievements:</b> NAACL 2025 System Demonstration, COLING 2024</li>
</ul>
<!-- 連結已更新為 tap.html -->
<a href="tap.html" class="btn-primary">Explore TAP Project →</a>
</div>
</div>

<!-- 2. Industry Research Highlights -->
<h2 class="section-title">🏭 Industry Research Highlights</h2>

<!-- Google -->
<div class="industry-card" style="border-left:5px solid #4285F4;">
<div class="industry-logo-area">
<img src="https://upload.wikimedia.org/wikipedia/commons/2/2f/Google_2015_logo.svg" style="width:100px;" alt="Google">
</div>
<div class="industry-content">
<h3 style="margin-top:0;color:#4285F4;">Google DeepMind / Google Research</h3>
<p style="color:#555;margin-bottom:15px;">
Collaborating on <b>Digital Humanities</b> and <b>Historical Big Data</b>. We utilize Semi-supervised Learning to decode the <i>Ming Shilu</i>, revealing 300 years of military secrets.
</p>
<div>
<span class="outcome-tag">🏆 Google Research Award</span>
<span class="outcome-tag">📄 EMNLP 2023</span>
<span class="outcome-tag">📄 DSH 2025</span>
</div>
<a href="research.html#thrust-3" class="btn-secondary">View Project: AI Historian →</a>
</div>
</div>

<!-- Qualcomm -->
<div class="industry-card" style="border-left:5px solid #3253dc;">
<div class="industry-logo-area">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fc/Qualcomm-Logo.svg/1280px-Qualcomm-Logo.svg.png" style="width:120px;" alt="Qualcomm">
</div>
<div class="industry-content">
<h3 style="margin-top:0;color:#3253dc;">Qualcomm AI Research</h3>
<p style="color:#555;margin-bottom:15px;">
Partnering on <b>Edge AI Optimization</b> for the <b>Write AI</b> project. We deploy quantized LLMs on Snapdragon® X Elite chips to enable offline, privacy-preserving essay grading in schools.
</p>
<div>
<span class="outcome-tag">📱 On-device AI</span>
<span class="outcome-tag">⚡ Model Quantization</span>
<span class="outcome-tag">🎓 MOE Project</span>
</div>
<a href="impact.html" class="btn-secondary">View Project: Write AI →</a>
</div>
</div>

<!-- 3. Global Network -->
<h2 class="section-title">🌐 Global & National Network</h2>
<div class="card-container">

<!-- Delta Research Center -->
<div class="card" style="border-top-color:#0082c8;">
<h3 style="margin-top:0;color:#0082c8;">🇹🇼 Delta Research Center</h3>
<p style="color:#555;font-size:0.95em;">
<b>Focus: Efficient Model Adaptation</b><br>
Researching cost-effective techniques to reduce the computational resources required for fine-tuning specialized LLMs.
</p>
</div>

<!-- TSMC -->
<div class="card" style="border-top-color:#ed1c24;">
<h3 style="margin-top:0;color:#ed1c24;">🇹🇼 TSMC (Taiwan Semiconductor)</h3>
<p style="color:#555;font-size:0.95em;">
<b>Focus: Domain-Specific LLMs</b><br>
Developing specialized LLMs for high-tech manufacturing (2025). Focusing on knowledge management and intelligent fab operation.
</p>
</div>

<!-- KISTI -->
<div class="card" style="border-top-color:#005AAB;">
<h3 style="margin-top:0;color:#005AAB;">🇰🇷 KISTI (South Korea)</h3>
<p style="color:#555;font-size:0.95em;">
<b>Focus: Multilingual Model Merging</b><br>
Joint research with the <i>Korea Institute of Science and Technology Information</i> on East Asian multilingual model alignment.
</p>
</div>

<!-- MPIWG -->
<div class="card" style="border-top-color:#FFCE00;">
<h3 style="margin-top:0;color:#b38f00;">🇩🇪 Max Planck Institute (MPIWG)</h3>
<p style="color:#555;font-size:0.95em;">
<b>Focus: Computer Vision in Digital Humanities</b><br>
Collaborating with <b>Shih-Pei Chen</b> on applying Deep Learning to classify illustrations in historical Chinese local gazetteers.
</p>
<div style="margin-top:10px;">
<span class="outcome-tag">📄 DSH 2024</span>
</div>
<a href="https://doi.org/10.1093/llc/fqad065" target="_blank" style="display:inline-block;margin-top:10px;font-weight:bold;font-size:0.9em;color:#b38f00;text-decoration:none;">View Publication →</a>
</div>

</div>

<!-- Footer -->
<div style="text-align:center;margin-top:60px;margin-bottom:40px;">
<p style="color:#666;margin-bottom:20px;">Interested in collaborating with us?</p>
<a href="opportunities.html" style="background:#2c3e50;color:#fff;padding:12px 30px;border-radius:30px;text-decoration:none;font-weight:bold;box-shadow:0 4px 10px rgba(0,0,0,0.2);">Contact for Partnership</a>
</div>

</div> <!-- content-wrapper end -->
</div> <!-- custom-body end -->