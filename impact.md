
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

/* 系統卡片樣式 */
.system-card {
    background: #fff;
    padding: 25px;
    margin-bottom: 25px;
    border-radius: 0 8px 8px 0;
    box-shadow: 0 2px 8px rgba(0,0,0,0.05);
    transition: transform 0.2s;
}
.system-card:hover {
    transform: translateY(-2px);
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}
.system-title {
    margin-top: 0;
    font-size: 1.4em;
    margin-bottom: 10px;
}
.tag {
    padding: 3px 10px;
    border-radius: 4px;
    font-size: 0.85em;
    margin-right: 5px;
    display: inline-block;
    margin-bottom: 5px;
}

/* 連結按鈕樣式 */
.link-btn {
    text-decoration: none;
    font-weight: bold;
    margin-right: 15px;
    display: inline-block;
    margin-top: 5px;
    transition: opacity 0.2s;
}
.link-btn:hover { opacity: 0.8; }

/* 書籍區塊樣式 */
.book-card {
    background: #fff;
    border: 1px solid #eee;
    border-radius: 8px;
    padding: 20px;
    text-align: center;
    box-shadow: 0 2px 5px rgba(0,0,0,0.05);
    height: 100%;
    box-sizing: border-box;
    display: flex;
    flex-direction: column;
    align-items: center;
}
.book-img {
    height: 180px;
    width: auto;
    margin-bottom: 15px;
    box-shadow: 3px 3px 8px rgba(0,0,0,0.15);
    transition: transform 0.2s;
}
.book-card:hover .book-img {
    transform: scale(1.05);
}
.buy-btn {
    display: inline-block;
    background: #fff;
    color: #e74c3c;
    border: 1px solid #e74c3c;
    padding: 5px 15px;
    border-radius: 20px;
    text-decoration: none;
    font-size: 0.85em;
    font-weight: bold;
    transition: all 0.2s;
    margin-top: auto; /* 推到底部 */
    margin-bottom: 15px;
}
.buy-btn:hover {
    background: #e74c3c;
    color: #fff;
}
/* 團購資訊區塊 */
.group-buy-info {
    width: 100%;
    background: #f8f9fa;
    border-top: 1px dashed #ddd;
    padding-top: 10px;
    font-size: 0.8em;
    color: #666;
    text-align: left;
    line-height: 1.4;
}
.group-buy-title {
    font-weight: bold;
    color: #555;
    margin-bottom: 3px;
    font-size: 0.9em;
}

/* 合作夥伴列表樣式 */
ul { padding-left: 20px; margin-top: 5px; }
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

<h1 style="text-align:center; color:#2c3e50; margin-bottom:10px;">Impact & Outreach</h1>
<p style="text-align:center; color:#666; max-width:800px; margin:0 auto 40px auto;">
We build deployable AI systems that translate research into real-world value—especially in <b>education</b>, <b>language learning</b>, and <b>humanities</b>—while actively promoting AI literacy through public media.
</p>

<!-- Public Outreach -->
<h2 class="section-title" style="margin-top:0;">🎬 Public Outreach: Media & Books</h2>

<!-- 影片專區 -->
<div style="background:#fff; border-radius:10px; padding:30px; box-shadow:0 4px 15px rgba(0,0,0,0.08); margin-bottom:40px; display:flex; flex-wrap:wrap; gap:30px; align-items:center;">
<div style="flex:1; min-width:280px;">
<img src="https://hackmd.io/_uploads/HJs4T6eHWg.png" alt="My AI Teammate Poster" style="width:100%; border-radius:8px; box-shadow:0 4px 12px rgba(0,0,0,0.2);">
</div>
<div style="flex:1.5; min-width:300px;">
<div style="margin-bottom:15px;">
<span style="background:#e74c3c; color:#fff; padding:4px 10px; border-radius:4px; font-weight:bold; font-size:0.85em;">2025 Golden Bell Award Nominee</span>
<span style="background:#f39c12; color:#fff; padding:4px 10px; border-radius:4px; font-weight:bold; font-size:0.85em; margin-left:5px;">NSTC Project</span>
</div>
<h3 style="margin:0 0 15px 0; color:#2c3e50; font-size:1.6em;">TV Series: My AI Teammate <br> (我的AI神隊友)</h3>
<p style="color:#555; font-size:1em; line-height:1.6; margin-bottom:20px;">
Hosted by <b>Prof. Richard Tzong-Han Tsai</b>, this 6-episode documentary series introduces how AI is being used across everyday domains in Taiwan. Each episode follows a “hands-on experience” format—bringing viewers into real labs/industry settings and using a layperson’s perspective to explain both the core ideas and the practical workflow behind the featured AI system.
</p>
<a href="#" target="_blank" style="display:inline-block; background:#c0392b; color:#fff; padding:10px 20px; border-radius:30px; text-decoration:none; font-size:0.95em; font-weight:bold; box-shadow:0 4px 10px rgba(192, 57, 43, 0.3);">▶️ Watch Intro Video</a>
</div>
</div>

<!-- 書籍專區 -->
<div style="display:flex; flex-wrap:wrap; gap:20px; margin-bottom:60px;">
<!-- Book 1 -->
<div style="flex:1; min-width:250px;">
<div class="book-card">
<img src="https://hackmd.io/_uploads/H1-Pc6eSbl.png" alt="Book 1" class="book-img">
<div style="font-weight:bold; color:#333; font-size:1em; margin-bottom:5px;">AI Lessons for Elementary Students<br>(寫給小學生看的AI課)</div>
<a href="https://www.books.com.tw/products/0010957259" target="_blank" class="buy-btn">🛒 博客來購書</a>
<!-- 團購資訊 -->
<div class="group-buy-info">
<div class="group-buy-title">🏫 校園/團購窗口</div>
<div><b>Iris Pei</b></div>
<div><a href="mailto:iris_pai@suncolor.com.tw" style="color:#666;text-decoration:none;">iris_pai@suncolor.com.tw</a></div>
<div>(02)8797-1234 ext. 213</div>
</div>
</div>
</div>
<!-- Book 2 -->
<div style="flex:1; min-width:250px;">
<div class="book-card">
<img src="https://hackmd.io/_uploads/rJKq56er-x.png" alt="Book 2" class="book-img">
<div style="font-weight:bold; color:#333; font-size:1em; margin-bottom:5px;">AI Lessons for Middle Schoolers<br>(寫給中學生看的AI課)</div>
<div style="color:#e67e22; font-size:0.85em; font-weight:bold; margin-top:5px; margin-bottom:5px;">🏆 Wu Ta-You Pop Sci Award</div>
<a href="https://www.books.com.tw/products/0010957263" target="_blank" class="buy-btn">🛒 博客來購書</a>
<!-- 團購資訊 -->
<div class="group-buy-info">
<div class="group-buy-title">🏫 校園/團購窗口</div>
<div><b>Iris Pei</b></div>
<div><a href="mailto:iris_pai@suncolor.com.tw" style="color:#666;text-decoration:none;">iris_pai@suncolor.com.tw</a></div>
<div>(02)8797-1234 ext. 213</div>
</div>
</div>
</div>
<!-- Book 3 -->
<div style="flex:1; min-width:250px;">
<div class="book-card">
<img src="https://hackmd.io/_uploads/ByIXsagBWg.png" alt="Book 3" class="book-img">
<div style="font-weight:bold; color:#333; font-size:1em; margin-bottom:5px;">AI+AIoT 概論：<br>寫給大學生看的AI通識學習</div>
<a href="https://www.books.com.tw/products/0010961497" target="_blank" class="buy-btn">🛒 博客來購書</a>
</div>
</div>
</div>

<!-- Deployable AI Systems -->
<h2 class="section-title">🚀 Deployable AI Systems</h2>

<h3 style="color:#555; border-bottom:2px solid #eee; padding-bottom:10px; margin-bottom:20px;">1. Education & Language Learning</h3>

<!-- System 1: AI Mandarin Partner -->
<div class="system-card" style="border-left:5px solid #0366d6;">
<h3 class="system-title" style="color:#0366d6;">AI Mandarin Partner (AI華語拍檔)</h3>
<p style="color:#666; margin-bottom:15px;">A teacher-first AI co-pilot for Mandarin lesson design, aligned with Taiwan’s <b>TBCL</b> standards.</p>

<div style="margin-bottom:15px;">
<span class="tag" style="background:#e8f4fd; color:#0366d6;">MOE Program 2025</span>
<span class="tag" style="background:#f0f0f0; color:#555;">Built on TAIDE</span>
</div>

<ul style="color:#444; font-size:0.95em; line-height:1.6;">
<li>Generates TBCL level-controlled passages (Levels 1–5) and vocabulary lists.</li>
<li>Creates grammar examples and substitution drills for classroom use.</li>
<li>Feedback-driven iteration via teacher workshops.</li>
</ul>

<div style="margin-top:20px;">
<a href="ai-mandarin-partner.html" class="link-btn" style="color:#0366d6;">🔗 Project Page</a>
<a href="mailto:mandarin.ai.partner@gmail.com" class="link-btn" style="color:#666;">✉️ Contact</a>
</div>
</div>

<!-- System 2: Write AI -->
<div class="system-card" style="border-left:5px solid #27ae60;">
<h3 class="system-title" style="color:#27ae60;">Write AI (AI 寫作批改)</h3>
<p style="color:#666; margin-bottom:15px;">An AI-assisted essay review system designed to help teachers provide faster, more consistent feedback.</p>

<div style="margin-bottom:15px;">
<span class="tag" style="background:#eafaf1; color:#27ae60;">MOE National Initiative</span>
<span class="tag" style="background:#f0f0f0; color:#555;">Official Launch 2025</span>
</div>

<ul style="color:#444; font-size:0.95em; line-height:1.6;">
<li>Rapid structure suggestions and semantic analysis.</li>
<li>Reduces grading burden and improves feedback timeliness.</li>
</ul>

<div style="margin-top:20px;">
<a href="https://writeai.moe.edu.tw/" target="_blank" class="link-btn" style="color:#27ae60;">🔗 Official Site</a>
<a href="https://www.edu.tw/News_Content.aspx?n=9E7AC85F1954DDA8&s=EBFBEAF1C017C670" target="_blank" class="link-btn" style="color:#666;">📰 MOE Announcement</a>
<a href="https://udn.com/news/story/6885/9104622" target="_blank" class="link-btn" style="color:#666;">📰 Media (UDN)</a>
</div>
</div>

<!-- System 3: ATAIGI -->
<div class="system-card" style="border-left:5px solid #d35400;">
<h3 class="system-title" style="color:#d35400;">ATAIGI (臺語學習 App)</h3>
<p style="color:#666; margin-bottom:15px;">A multimodal, AI-powered learning app for <b>Taiwanese Hokkien</b>, co-developed by teams in Taiwan and Canada.</p>

<div style="margin-bottom:15px;">
<span class="tag" style="background:#fff5e6; color:#d35400;">NAACL 2025 Demo</span>
<span class="tag" style="background:#fff5e6; color:#d35400;">CTCI Award (2nd Place)</span>
</div>

<ul style="color:#444; font-size:0.95em; line-height:1.6;">
<li>Multimodal learning: definitions, images, romanization, and audio.</li>
<li>Built on generative AI for low-resource language preservation.</li>
</ul>

<div style="margin-top:20px;">
<a href="https://aclanthology.org/2025.naacl-demo.2/" target="_blank" class="link-btn" style="color:#d35400;">📄 ACL Anthology</a>
<a href="https://ncusec.ncu.edu.tw/news/press_content.php?P_ID=45313" target="_blank" class="link-btn" style="color:#666;">📰 News (NCU)</a>
</div>
</div>

<h3 style="color:#555; border-bottom:2px solid #eee; padding-bottom:10px; margin-top:50px; margin-bottom:20px;">2. Humanities Knowledge Discovery</h3>

<!-- System 4: TaihuCais -->
<div class="system-card" style="border-left:5px solid #8e44ad;">
<h3 class="system-title" style="color:#8e44ad;">TaihuCais (臺鵠開示)</h3>
<p style="color:#666; margin-bottom:15px;">A conversational knowledge discovery system for Taiwan humanities with evidence-grounded retrieval.</p>

<div style="margin-bottom:15px;">
<span class="tag" style="background:#f3e5f5; color:#8e44ad;">🏆 Future Tech Award 2025</span>
</div>

<ul style="color:#444; font-size:0.95em; line-height:1.6;">
<li>Natural-language querying for humanities resources.</li>
<li>Retrieval + evidence-oriented design for traceability.</li>
<li>Platform for education, research, and cultural institutions.</li>
</ul>

<div style="margin-top:20px;">
<a href="https://www.taihu-ai.com/" target="_blank" class="link-btn" style="color:#8e44ad;">🔗 Official Site</a>
<a href="https://taihu.ntu.edu.tw/" target="_blank" class="link-btn" style="color:#666;">🔗 NTU Project</a>
<a href="https://www.taih.ntnu.edu.tw/index.php/2025/10/22/post-10-28-02/" target="_blank" class="link-btn" style="color:#666;">📰 Award News</a>
</div>
</div>

<!-- Trusted by Industry & Government -->
<h2 class="section-title">🌏 Trusted by Industry & Government</h2>

<p style="text-align:center; color:#666; margin-bottom:30px;">
Our technologies are deployed in critical sectors, driving value for leading enterprises and public institutions.
</p>

<table style="width:100%; border:none; border-collapse:collapse; margin-top:20px; margin-bottom:30px;">
<tr style="border:none;">
<td style="width:33%; vertical-align:top; border:none; padding-right:20px;">
<h4 style="margin:0 0 10px 0; color:#555; border-bottom:3px solid #3498db; padding-bottom:8px;">🏭 Industry Deployment</h4>
<ul style="padding-left:20px; color:#444; margin-top:10px; font-size:0.95em; line-height:1.6;">
<li><b>TSMC:</b> Fab operation LLMs</li>
<li><b>Google Research:</b> Award Recipient</li>
<li><b>Qualcomm:</b> Edge AI Integration</li>
</ul>
</td>
<td style="width:33%; vertical-align:top; border:none; padding-right:20px;">
<h4 style="margin:0 0 10px 0; color:#555; border-bottom:3px solid #27ae60; padding-bottom:8px;">🏛️ Public Sector Adoption</h4>
<ul style="padding-left:20px; color:#444; margin-top:10px; font-size:0.95em; line-height:1.6;">
<li><b>National Central Library:</b> AI Search</li>
<li><b>Taoyuan City Gov:</b> Smart City</li>
<li><b>NCHC / NARLabs:</b> Education AI</li>
</ul>
</td>
<td style="width:33%; vertical-align:top; border:none;">
<h4 style="margin:0 0 10px 0; color:#555; border-bottom:3px solid #c0392b; padding-bottom:8px;">🏥 Clinical Implementation</h4>
<ul style="padding-left:20px; color:#444; margin-top:10px; font-size:0.95em; line-height:1.6;">
<li><b>Cathay General Hospital</b></li>
<li><b>Landseed Int'l Hospital</b></li>
</ul>
</td>
</tr>
</table>

<!-- 引導至完整 Collab 頁面的按鈕 -->
<div style="text-align:center; margin-bottom:40px;">
<a href="collaboration.html" style="display:inline-block; border:2px solid #2c3e50; color:#2c3e50; padding:10px 25px; border-radius:30px; text-decoration:none; font-weight:bold; transition:0.2s;">
View Full Collaboration Network & Funding Sources →
</a>
</div>

<div style="text-align:center;margin-top:60px;">
<a href="index.html" style="background:#2c3e50;color:#fff;padding:12px 30px;border-radius:30px;text-decoration:none;font-weight:bold;box-shadow:0 4px 10px rgba(0,0,0,0.2);">← Back to Home</a>
</div>

</div> <!-- content-wrapper end -->
</div> <!-- custom-body end -->