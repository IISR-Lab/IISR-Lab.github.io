
<style>
    body { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif; max-width: 1000px; margin: 0 auto; padding: 20px; line-height: 1.6; color: #333; }
    a { color: #0366d6; text-decoration: none; }
    a:hover { text-decoration: underline; }
    table { width: 100%; border-collapse: collapse; }
    img { max-width: 100%; }
</style>


<style>
/* --- 1. HackMD 專用暴力破解樣式 (必備) --- */
/* 強制將外層容器撐開至 100% 視窗寬度 */
.container-fluid, #doc, .markdown-body {
    max-width: 100% !important;
    width: 100% !important;
    min-width: 100% !important;
    padding: 0 !important;
    margin: 0 !important;
}
/* 隱藏 HackMD 可能產生的多餘捲軸 */
body {
    overflow-x: hidden;
}

/* --- 2. 您的網頁樣式 --- */
.custom-body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f9f9f9;
    width: 100%;
}

/* 導覽列 */
.nav-bar {
    background: #fff;
    text-align: center;
    padding: 15px 20px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.05);
    font-size: 0.95em;
    white-space: nowrap;
    position: sticky;
    top: 0;
    z-index: 9999; /* 確保在 HackMD 介面上層 */
}
.nav-bar a {
    color: #0366d6;
    text-decoration: none;
    margin: 0 10px;
    font-weight: 500;
}
.nav-bar a:hover { text-decoration: underline; }
.nav-sep { color: #ccc; }

/* Hero Banner - 滿版背景 */
.hero-banner {
    background: linear-gradient(135deg, #002A5C 0%, #c0392b 100%);
    color: white;
    padding: 80px 5%;
    text-align: center;
    border-radius: 0 0 20px 20px;
    margin-bottom: 40px;
    width: 100%;
    box-sizing: border-box;
}

/* 內容容器 - 置中核心 */
.content-wrapper {
    width: 100%;
    max-width: 1200px; /* 限制內容寬度 */
    margin: 0 auto;    /* 左右自動置中 */
    padding: 40px 20px;
    box-sizing: border-box;
    display: block; /* 確保是區塊元素 */
}

/* 元素樣式 */
.custom-body h1, .custom-body h2, .custom-body h3 { color: #2c3e50; margin-top: 1em; }
.section-title {
    text-align: center;
    margin-top: 60px;
    margin-bottom: 40px;
    font-size: 2em;
    position: relative;
    border-bottom: none !important;
}
.section-title::after {
    content: "";
    display: block;
    width: 60px;
    height: 3px;
    background: #c0392b;
    margin: 10px auto 0;
}

/* 卡片與網格系統 */
.card-container {
    display: flex;
    flex-wrap: wrap;
    gap: 30px;
    justify-content: center;
    width: 100%;
}
.card {
    background: #fff;
    border-radius: 12px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.08);
    padding: 30px;
    flex: 1 1 300px; /* Flex 設定確保不崩壞 */
    min-width: 300px;
    border-top: 5px solid #ddd;
    box-sizing: border-box;
}
.card-blue { border-top-color: #002A5C; }
.card-red { border-top-color: #c0392b; }

.team-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 20px;
    width: 100%;
}
.team-member {
    background: white;
    padding: 20px;
    border-radius: 8px;
    border: 1px solid #eee;
    text-decoration: none;
    color: inherit;
    display: block;
    box-sizing: border-box;
}
.team-member:hover {
    transform: translateY(-3px);
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    border-color: #3498db;
}
.role-badge {
    display: inline-block;
    padding: 2px 8px;
    border-radius: 4px;
    font-size: 0.8em;
    font-weight: bold;
    margin-bottom: 5px;
}
.role-pi { background: #e8f4fd; color: #002A5C; }
.role-coi { background: #fff5f5; color: #c0392b; }
.role-collab { background: #f0fdf4; color: #27ae60; }
.custom-body ul { padding-left: 20px; color: #555; text-align: left; }
</style>

<!-- 內容區：使用一個最外層 div 包裹所有內容，防止被 HackMD 分割 -->
<div class="custom-body">

<div class="nav-bar">
<a href="#">Home</a> <span class="nav-sep">|</span>
<a href="#">People</a> <span class="nav-sep">|</span>
<a href="#">PI Profile</a> <span class="nav-sep">|</span>
<a href="#">Research</a> <span class="nav-sep">|</span>
<a href="#">Impact</a> <span class="nav-sep">|</span>
<a href="#">Collab</a> <span class="nav-sep">|</span>
<a href="#">Pubs</a> <span class="nav-sep">|</span>
<a href="#">News</a> <span class="nav-sep">|</span>
<a href="#">Join</a> <span class="nav-sep">|</span>
<a href="#">Contact</a>
</div>

<div class="hero-banner">
<div style="font-weight:bold;letter-spacing:3px;margin-bottom:15px;opacity:0.9;">2025 UAAT TAIWAN-CANADA AFFINITY PROGRAM</div>
<h1 style="margin:0;font-size:3em;color:white;line-height:1.2;border-bottom:none;">Revitalising Taiwanese Hokkien through <br>Neural Language Technologies</h1>
<p style="font-size:1.5em;margin-top:20px;opacity:0.95;font-weight:300;">A Global Collaborative Approach to Educational Learning and Multimodal AI</p>
<div style="margin-top:30px;">
<span style="background:rgba(255,255,255,0.2);padding:5px 15px;border-radius:20px;font-weight:bold;margin:0 5px;">🇹🇼 Taiwan</span>
<span style="background:rgba(255,255,255,0.2);padding:5px 15px;border-radius:20px;font-weight:bold;margin:0 5px;">🇨🇦 Canada</span>
<span style="background:rgba(255,255,255,0.2);padding:5px 15px;border-radius:20px;font-weight:bold;margin:0 5px;">🤖 GenAI</span>
</div>
</div>

<div class="content-wrapper">

<div style="max-width:1000px;margin:0 auto 60px auto;text-align:center;">
<h2 style="color:#2c3e50;border-bottom:none;">Mission Statement</h2>
<p style="font-size:1.1em;color:#555;line-height:1.8;">
This multi-year project is co-led by <b>Prof. Richard Tzong-Han Tsai (Taiwan)</b> and <b>Prof. Annie En-Shiun Lee (Canada)</b> to combat the digital scarcity of low-resource languages. By uniting top institutions across both nations, we bridge the generational linguistic gap through high-quality machine translation resources and AI-powered multimodal learning tools like <b>ATAIGI</b>.
</p>
</div>

<h2 class="section-title">Core Research Thrusts</h2>
<div class="card-container">
<div class="card card-blue">
<h3 style="margin-top:0;color:#002A5C;border-bottom:none;">1. Improving Translation Quality</h3>
<p><b>Goal:</b> Overcoming data scarcity and "translationese" errors in Sinitic languages (Hokkien, Cantonese, Wu).</p>
<hr style="border:0;border-top:1px solid #eee;margin:15px 0;">
<ul>
<li><b>Hokkien MT Error Dataset:</b> Creating the first span-level error annotation dataset (MQM-derived) for fine-grained evaluation.</li>
<li><b>Dual Translation Models:</b> Developing models optimized for Hokkien (HAN/POJ) ↔ Mandarin/English using <b>TAIDE-7B</b> and <b>LLaMA</b>.</li>
<li><b>Corpus Standardization:</b> Leveraging orthographic similarities to standardize writing systems (HAN, POJ, HL).</li>
<li><b>Tools:</b> Deployment of <i>TRANSLATIONCORRECT</i> framework for rigorous annotation.</li>
</ul>
</div>
<div class="card card-red">
<h3 style="margin-top:0;color:#c0392b;border-bottom:none;">2. AI-Powered Language Learning</h3>
<p><b>Goal:</b> Creating an immersive, multimodal educational platform for language revitalization.</p>
<hr style="border:0;border-top:1px solid #eee;margin:15px 0;">
<ul>
<li><b>ATAIGI App:</b> A unified open-source app integrating translation, context generation, and transliteration.</li>
<li><b>Multimodal GenAI:</b> Generating contextual images (DALL-E 3) and audio to enhance vocabulary acquisition.</li>
<li><b>3D Avatar Chatbot:</b> Integrating ASR (Whisper) and TTS for scenario-based roleplay and pronunciation practice.</li>
<li><b>Pedagogical Validation:</b> Rigorous user studies with psycholinguistic measures.</li>
</ul>
</div>
</div>

<h2 class="section-title">The Collaborative Team</h2>
<div class="card-container" style="align-items:flex-start;">
<div style="flex:1;min-width:300px;">
<h3 style="text-align:center;color:#002A5C;margin-bottom:20px;border-bottom:none;">🇹🇼 Taiwan Team</h3>
<div class="team-grid">
<a href="#" class="team-member">
<span class="role-badge role-pi">Principal Investigator (Taiwan)</span>
<div style="font-weight:bold;font-size:1.1em;margin:5px 0;">Prof. Richard Tzong-Han Tsai</div>
<div style="font-size:0.85em;color:#666;">National Central University / Academia Sinica</div>
<div style="font-size:0.85em;margin-top:5px;"><i>NLP, Code-mixing, TAIDE Technical Lead</i></div>
</a>
<a href="#" class="team-member">
<span class="role-badge role-coi">Co-Investigator</span>
<div style="font-weight:bold;font-size:1.1em;margin:5px 0;">Prof. Chia-Lin Lee</div>
<div style="font-size:0.85em;color:#666;">NTU Linguistics/Psychology</div>
</a>
</div>
</div>
<div style="flex:1;min-width:300px;">
<h3 style="text-align:center;color:#c0392b;margin-bottom:20px;border-bottom:none;">🇨🇦 Canada Team</h3>
<div class="team-grid">
<a href="#" class="team-member">
<span class="role-badge role-pi">Principal Investigator (Canada)</span>
<div style="font-weight:bold;font-size:1.1em;margin:5px 0;">Prof. Annie En-Shiun Lee</div>
<div style="font-size:0.85em;color:#666;">University of Toronto / Ontario Tech U</div>
</a>
<a href="#" class="team-member">
<span class="role-badge role-coi">Co-Investigator</span>
<div style="font-weight:bold;font-size:1.1em;margin:5px 0;">Prof. Muhammad Usman</div>
<div style="font-size:0.85em;color:#666;">Ontario Tech University</div>
</a>
</div>
</div>
</div>

<h2 class="section-title">Impact & Milestones</h2>
<div class="card" style="background:#fff8e1;border-top:5px solid #f1c40f;">
<h3 style="margin-top:0;border-bottom:none;">🚀 Key Achievements</h3>
<ul>
<li><b>NAACL 2025 Demo Paper:</b> <i>"ATAIGI: An AI-Powered Multimodal Learning App Leveraging Generative Models for Low-Resource Taiwanese Hokkien"</i>.</li>
<li><b>LREC-COLING 2024:</b> <i>"Enhancing Taiwanese Hokkien Dual Translation by Exploring and Standardizing of Four Writing Systems"</i>.</li>
<li><b>SINITIC MT ERROR Dataset:</b> Publicly released for the Sinitic NLP research community.</li>
</ul>
</div>

<div style="text-align:center;margin-top:50px;color:#888;font-size:0.9em;">
Supported by the <b>UAAT Taiwan Affinity Program</b> and the <b>National Science and Technology Council (NSTC)</b>.
</div>

<div style="text-align:center;margin-top:40px;padding-bottom:60px;">
<a href="#" style="background:#333;color:#fff;padding:12px 30px;border-radius:30px;text-decoration:none;font-weight:bold;box-shadow:0 4px 10px rgba(0,0,0,0.2);">← Back to Collaborations</a>
</div>

</div> <!-- 結束 custom-body -->