
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
    max-width: 1200px;
    margin: 0 auto;
    padding: 40px 20px;
}

/* Hero Banner */
.hero-banner {
    background: linear-gradient(135deg, #2c3e50 0%, #34495e 100%);
    color: white;
    padding: 80px 20px;
    text-align: center;
    margin-bottom: 50px;
}
.tag {
    display: inline-block;
    background: rgba(255,255,255,0.15);
    padding: 5px 15px;
    border-radius: 20px;
    font-size: 0.9em;
    margin: 5px;
    border: 1px solid rgba(255,255,255,0.2);
}

/* 標題與卡片 */
.section-title {
    text-align: center;
    margin: 60px 0 40px 0;
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

/* 卡片容器設定 */
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
    min-width: 280px; /* 稍微縮小最小寬度以確保三欄並排 */
    border-top: 5px solid #ddd;
}
.project-img {
    width: 100%;
    height: 180px;
    object-fit: cover;
    border-radius: 6px;
    margin-bottom: 15px;
    border: 1px solid #eee;
}

/* 照片牆表格 */
.gallery-table {
    width: 100%;
    border-collapse: separate;
    border-spacing: 15px;
    margin-bottom: 40px;
    table-layout: fixed;
}
.gallery-td {
    vertical-align: top;
    padding: 0;
}
.gallery-img {
    width: 100%;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    display: block;
    margin-bottom: 10px;
}
.gallery-caption {
    text-align: center;
    font-size: 0.9em;
    color: #666;
    margin-bottom: 30px;
    font-style: italic;
}

/* 其他元件 */
.year-badge {
    background: #333;
    color: #fff;
    padding: 3px 10px;
    border-radius: 4px;
    font-size: 0.85em;
    font-weight: bold;
    vertical-align: middle;
    margin-right: 8px;
}
.btn-cta {
    display: inline-block;
    background: #e74c3c;
    color: white !important;
    padding: 12px 30px;
    border-radius: 30px;
    text-decoration: none;
    font-weight: bold;
    box-shadow: 0 4px 10px rgba(231, 76, 60, 0.3);
    transition: transform 0.2s;
}
.btn-cta:hover { transform: translateY(-2px); }
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
<div style="color:#f1c40f;font-weight:bold;letter-spacing:2px;margin-bottom:10px;text-transform:uppercase;font-size:0.9em;">NTU Graduate Institute of Linguistics</div>
<h1 style="margin:0 0 15px 0;font-size:2.8em;line-height:1.2;">Digital Humanities:<br>Technology and Applications</h1>
<p style="font-size:1.2em;color:#ecf0f1;line-height:1.6;max-width:800px;margin:0 auto 30px auto;font-weight:300;">
A flagship interdisciplinary course bridging <b>Humanities</b> and <b>Generative AI</b>.<br>
Training the next generation of "Bilingual Talents" who speak both Domain Knowledge and AI Logic.
</p>
<div>
<span class="tag">🤖 GenAI & LLMs</span>
<span class="tag">📜 RAG & Agents</span>
<span class="tag">🤝 Cross-Disciplinary</span>
</div>
</div>

<div class="content-wrapper">

<!-- Media Spotlight -->
<h2 class="section-title" style="margin-top:0;">📰 Media Spotlight</h2>
<div class="card-container">
<!-- 報導 1: 未來城市 EP.99 -->
<div class="card" style="border-top-color:#c0392b;">
<div style="color:#c0392b;font-weight:bold;margin-bottom:10px;font-size:0.9em;">CommonWealth Magazine (天下雜誌)</div>
<h3 style="margin:0 0 15px 0;font-size:1.3em;line-height:1.4;">
<a href="https://futurecity.cw.com.tw/article/3665" target="_blank" style="color:#2c3e50;text-decoration:none;">"Can only science students do AI? Prof. Tsai: Humanities' precision in language is key to AI development"</a>
</h3>
<p style="color:#666;font-size:0.95em;line-height:1.6;">
Featured in <i>Future City Podcast EP.99</i>. Prof. Tsai discusses how humanities students act as the "Tripitaka" (Tang Sanzang) guiding the AI journey, emphasizing that data curation, bias detection, and prompt engineering require humanistic sensitivity.
</p>
<div style="margin-top:20px;">
<a href="https://futurecity.cw.com.tw/article/3665" target="_blank" style="font-weight:bold;font-size:0.9em;color:#0366d6;">Read Full Story →</a>
</div>
</div>

<!-- 報導 2: 未來城市 Model Foundry -->
<div class="card" style="border-top-color:#c0392b;">
<div style="color:#c0392b;font-weight:bold;margin-bottom:10px;font-size:0.9em;">CommonWealth Magazine (天下雜誌)</div>
<h3 style="margin:0 0 15px 0;font-size:1.3em;line-height:1.4;">
<a href="https://futurecity.cw.com.tw/article/3512" target="_blank" style="color:#2c3e50;text-decoration:none;">"Building an 'AI TSMC' with Model Foundry! Prof. Tsai: A New Path for Liberal Arts in the AI Era"</a>
</h3>
<p style="color:#666;font-size:0.95em;line-height:1.6;">
Highlighting the concept of "Model Foundry" where humanities students fine-tune models for specific domains. The course demonstrates how students from History and Literature can build their own AI applications.
</p>
<div style="margin-top:20px;">
<a href="https://futurecity.cw.com.tw/article/3512" target="_blank" style="font-weight:bold;font-size:0.9em;color:#0366d6;">Read Full Story →</a>
</div>
</div>
</div>

<!-- Video Recap -->
<div style="background:#2c3e50;border-radius:12px;padding:40px 20px;margin:60px 0;text-align:center;color:white;box-shadow:0 10px 30px rgba(0,0,0,0.15);">
<h2 style="margin-top:0;color:#f1c40f;font-size:1.8em;margin-bottom:15px;">🎥 Course Recap Video</h2>
<p style="color:#ecf0f1;margin-bottom:30px;font-size:1.1em;">Watch the highlights and student presentations from our 2024 semester.</p>
<a href="http://xxx" target="_blank" class="btn-cta">▶️ Watch Video Highlights</a>
</div>

<!-- Philosophy -->
<h2 class="section-title">🏫 Course Philosophy</h2>
<div style="max-width:900px;margin:0 auto;text-align:center;margin-bottom:40px;">
<p style="font-size:1.2em;color:#555;line-height:1.8;">
In the era of GPT-5, we reject the "outsourcing mentality."<br>
<b>Domain Experts (Humanities)</b> must become the <b>Architects of AI</b>.
</p>
</div>

<div style="background:#fff;border-left:5px solid #2c3e50;padding:30px;border-radius:8px;box-shadow:0 2px 8px rgba(0,0,0,0.05);">
<h3 style="margin-top:0;color:#2c3e50;">🚀 The Technical Evolution</h3>
<p style="color:#555;margin-bottom:20px;">Our curriculum evolves with SOTA technology to ensure students learn the most relevant skills:</p>
<ul style="line-height:1.8;color:#444;">
<li style="margin-bottom:15px;">
<b>2025 Focus: RAG & Agentic Workflows</b><br>
Moving beyond fine-tuning. We focus on <b>Long Context Prompting</b>, <b>Retrieval-Augmented Generation (RAG)</b>, and designing <b>Agent SOPs</b> to solve complex logic tasks without catastrophic forgetting.
</li>
<li>
<b>2024 Focus: Instruction Fine-Tuning (SFT)</b><br>
Teaching students how to curate datasets to fine-tune open-source models (like Llama 3 / TAIDE) for specific tasks, emphasizing that "Data Quality is Key."
</li>
</ul>
</div>

<!-- Student Projects -->
<h2 class="section-title">🏆 Student Projects Showcase</h2>

<!-- 2025 Projects -->
<h3 style="color:#2c3e50;border-bottom:2px solid #eee;padding-bottom:10px;margin-bottom:20px;"><span class="year-badge">2025</span> RAG & Agentic Workflows</h3>

<!-- 這裡的 div 和下方的 div 都嚴格靠左，避免 HackMD 誤判 -->
<div class="card-container">
<!-- Project 1 -->
<div class="card" style="border-top-color:#3498db;">
<img src="https://hackmd.io/_uploads/BkSqgIlQbx.png" alt="Project 1" class="project-img">
<h4 style="margin:0 0 5px 0;color:#2c3e50;">History Exam Generator</h4>
<div style="font-size:0.9em;color:#666;">
<b>Team:</b> History & Bio-mechatronics<br>
An AI system that generates realistic history exam questions, mimicking the style and logic of official exams.
</div>
</div>
<!-- Project 2 -->
<div class="card" style="border-top-color:#3498db;">
<img src="https://hackmd.io/_uploads/BJrZZLxQWl.png" alt="Project 2" class="project-img">
<h4 style="margin:0 0 5px 0;color:#2c3e50;">Linguistics Olympiad Solver</h4>
<div style="font-size:0.9em;color:#666;">
<b>Team:</b> Translation, Library Sci, Design<br>
Modeling the logical flow to solve complex Linguistics Olympiad puzzles using Agentic workflows.
</div>
</div>
<!-- Project 3 -->
<div class="card" style="border-top-color:#3498db;">
<img src="https://hackmd.io/_uploads/rk8ObUlXbx.png" alt="Project 3" class="project-img">
<h4 style="margin:0 0 5px 0;color:#2c3e50;">Idiom Adventure Game</h4>
<div style="font-size:0.9em;color:#666;">
<b>Team:</b> Foreign Lang, Linguistics<br>
A situational adventure game for learning idioms, powered by GenAI to create dynamic storylines.
</div>
</div>
</div>

<!-- 2024 Projects -->
<h3 style="color:#2c3e50;border-bottom:2px solid #eee;padding-bottom:10px;margin-top:60px;margin-bottom:20px;"><span class="year-badge">2024</span> Instruction Fine-Tuning (SFT)</h3>
<div class="card-container">
<div class="card" style="border-top-color:#f1c40f;">
<img src="https://hackmd.io/_uploads/H1QJkzMqJl.jpg" alt="Project 2024-1" class="project-img">
<h4 style="margin:0 0 5px 0;color:#2c3e50;">Ancient Entity Linking</h4>
<div style="font-size:0.9em;color:#666;">
<b>Task:</b> Querying ancient figures' alternative names.<br>
<b>Input:</b> 李白 ➔ <b>Output:</b> 太白、詩仙
</div>
</div>
<div class="card" style="border-top-color:#f1c40f;">
<img src="https://hackmd.io/_uploads/BkyZCZz9yl.png" alt="Project 2024-2" class="project-img">
<h4 style="margin:0 0 5px 0;color:#2c3e50;">Coreference Resolution</h4>
<div style="font-size:0.9em;color:#666;">
<b>Task:</b> Resolving pronouns in classical Chinese texts.<br>
<b>Input:</b> 王陽明，其少也好學 ➔ <b>Output:</b> 王陽明...
</div>
</div>
</div>

<!-- Gallery (5 Photos, 2 Columns) -->
<h2 class="section-title">📸 Classroom Gallery</h2>
<table class="gallery-table">
<tr>
<!-- 左欄：3張照片 -->
<td class="gallery-td" style="width:50%;">
<img src="https://hackmd.io/_uploads/Sk2VvQgByg.jpg" class="gallery-img" alt="Teaching">
<div class="gallery-caption">Lecture & Concept Explanation</div>

<img src="https://hackmd.io/_uploads/rJGbumlHkx.jpg" class="gallery-img" alt="Discussion">
<div class="gallery-caption">Intensive Group Discussion</div>

<img src="https://hackmd.io/_uploads/ByZoQNeByx.jpg" class="gallery-img" alt="Moon Festival">
<div class="gallery-caption">Celebrating Moon Festival</div>
</td>

<!-- 右欄：2張照片 -->
<td class="gallery-td" style="width:50%;">
<img src="https://hackmd.io/_uploads/SJKRRlWHyg.jpg" class="gallery-img" alt="Engineer Pose">
<div class="gallery-caption">"Do we look like engineers?"</div>

<img src="https://hackmd.io/_uploads/H1xz3e-Skg.jpg" class="gallery-img" alt="Group Work">
<div class="gallery-caption">Breaking the Ice & Collaborating</div>
</td>
</tr>
</table>

<!-- Instructor & Guests -->
<h2 class="section-title">👨‍🏫 Instructor & Distinguished Guests</h2>
<div style="background:#fff;border-radius:10px;padding:40px;box-shadow:0 2px 10px rgba(0,0,0,0.05);border:1px solid #eee;">
<div style="text-align:center;margin-bottom:40px;border-bottom:1px solid #eee;padding-bottom:20px;">
<div style="font-size:1.5em;font-weight:bold;color:#2c3e50;">Instructor: Prof. Richard Tzong-Han Tsai (蔡宗翰)</div>
<div style="color:#7f8c8d;margin-top:5px;">Joint Professor, Graduate Institute of Linguistics, NTU</div>
</div>

<div style="display:flex;flex-wrap:wrap;gap:40px;">
<div style="flex:1;min-width:300px;">
<h4 style="color:#c0392b;border-bottom:2px solid #eee;padding-bottom:10px;margin-top:0;">
<span class="year-badge">2025</span> Final Presentation Judges
</h4>
<ul style="padding-left:20px;color:#444;font-size:0.95em;line-height:1.8;">
<li><b>Ms. Fang-Yu Chen (陳芳毓)</b>, Senior Director, <i>Future City</i>, CommonWealth Magazine</li>
<li><b>Prof. Kuan-Fei Chen (陳冠妃)</b>, Asst. Prof., Dept. of History, NTU</li>
<li><b>Ms. Hsiao-Ping Huang (黃小萍)</b>, Research Teacher, NAER (師鐸獎得主)</li>
<li><b>Dr. Yi-Chih Huang (黃意植)</b>, Associate Researcher, NARLabs</li>
</ul>
</div>
<div style="flex:1;min-width:300px;">
<h4 style="color:#2980b9;border-bottom:2px solid #eee;padding-bottom:10px;margin-top:0;">
<span class="year-badge">2024</span> Final Presentation Judges
</h4>
<ul style="padding-left:20px;color:#444;font-size:0.95em;line-height:1.8;">
<li><b>Prof. Yu-Yu Cheng (鄭毓瑜)</b>, Dean, College of Liberal Arts, NTU</li>
<li><b>Prof. Shu-Kai Hsieh (謝舒凱)</b>, Vice Dean, College of Liberal Arts, NTU</li>
<li><b>Ms. Fang-Yu Chen (陳芳毓)</b>, Senior Director, <i>Future City</i></li>
<li><b>Ms. Isabel Hou (侯宜秀)</b>, Secretary General, Taiwan AI Academy Foundation</li>
</ul>
</div>
</div>
</div>

<!-- Future Vision -->
<h2 class="section-title">🔮 Future Vision</h2>
<div style="text-align:center;max-width:800px;margin:0 auto;color:#555;font-size:1.1em;line-height:1.8;">
<p>We echo the global trend of top universities (UCL, Stanford, Cambridge) and advocate for the establishment of formal <b>Digital Humanities Degree Programs</b> at NTU, fostering the next generation of bilingual talents who can lead the AI era.</p>
</div>

<div style="text-align:center;margin-top:60px;">
<a href="pi.html" style="background:#2c3e50;color:#fff;padding:12px 30px;border-radius:30px;text-decoration:none;font-weight:bold;box-shadow:0 4px 10px rgba(0,0,0,0.2);">← Back to PI Profile</a>
</div>

</div> <!-- content-wrapper end -->
</div> <!-- custom-body end -->