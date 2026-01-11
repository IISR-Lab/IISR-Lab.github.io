
<style>
    body { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif; max-width: 1000px; margin: 0 auto; padding: 20px; line-height: 1.6; color: #333; }
    a { color: #0366d6; text-decoration: none; }
    a:hover { text-decoration: underline; }
    table { width: 100%; border-collapse: collapse; }
    img { max-width: 100%; }
</style>


[Home](index.html) ｜ [People](people.html) ｜ [Research](research.html) ｜ [Impact](impact.html) ｜ [Publications](publications.html) ｜ [News](news.html) ｜ [Join Us](joinus.html) ｜ [Contact](contact.html)

---

# Research Areas

IISR advances intelligent information services through three major thrusts (2021–2025), integrating **LLMs**, **Retrieval (RAG)**, **Data-centric AI**, and **Cross-domain Representation Learning**.

<!-- 快速導覽按鈕 -->
<div style="display:flex; gap:10px; margin-bottom:40px; flex-wrap:wrap;">
<a href="#thrust-1" style="background:#f8f9fa; border:1px solid #ddd; padding:8px 15px; border-radius:20px; color:#333; text-decoration:none; font-size:0.9em;">🇹🇼 Localized LLMs</a>
<a href="#thrust-2" style="background:#f8f9fa; border:1px solid #ddd; padding:8px 15px; border-radius:20px; color:#333; text-decoration:none; font-size:0.9em;">🧬 Biomedical NLP</a>
<a href="#thrust-3" style="background:#f8f9fa; border:1px solid #ddd; padding:8px 15px; border-radius:20px; color:#333; text-decoration:none; font-size:0.9em;">🗺️ Digital Humanities</a>
</div>

---

<a id="thrust-1"></a>
## Thrust 1 — Taiwan-Localized LLMs & Low-Resource Languages

<div style="margin-bottom:15px;">
<span style="background:#e8f4fd; color:#0366d6; padding:4px 10px; border-radius:4px; font-weight:bold; font-size:0.85em; margin-right:5px;">ACL 2024</span>
<span style="background:#e8f4fd; color:#0366d6; padding:4px 10px; border-radius:4px; font-weight:bold; font-size:0.85em; margin-right:5px;">EMNLP 2024</span>
<span style="background:#e8f4fd; color:#0366d6; padding:4px 10px; border-radius:4px; font-weight:bold; font-size:0.85em; margin-right:5px;">NAACL 2025</span>
<span style="background:#e8f4fd; color:#0366d6; padding:4px 10px; border-radius:4px; font-weight:bold; font-size:0.85em; margin-right:5px;">COLING 2024</span>
</div>

**Motivation:** Mainstream LLMs often lack **Traditional Chinese (Taiwan) cultural grounding** and have limited coverage for local languages (e.g., Taiwanese Hokkien).

### 🔑 Key Contributions
- **Chat Vector (ACL 2024)** [📄 Paper](https://aclanthology.org/2024.acl-long.590/) [💻 Code](https://github.com/aqweteddy/ChatVector)  
  A lightweight, economical alignment technique that transfers instruction-following ability using weight-space additivity—reducing dependence on expensive RLHF.
- **TWBias (EMNLP 2024)** [📄 Paper](https://aclanthology.org/2024.findings-emnlp.507/) [💻 Code](https://github.com/hsinmosyi/TWBias)  
  The first benchmark for assessing social bias in Traditional Chinese LLMs **through a Taiwan cultural lens**, supporting trustworthy evaluation for Taiwan-localized models.
- **Hokkien NLP & Multimodal Learning**
  - Standardizing and bridging multiple writing systems (*COLING 2024*). [📄 Paper](https://aclanthology.org/2024.lrec-main.538/)
  - **ATAIGI (NAACL 2025):** A multimodal learning app leveraging generative models for low-resource Hokkien education. [📄 Paper](https://aclanthology.org/2025.naacl-demo.2/) [💻 Code](https://github.com/LeeLanguageLab/HokkienTranslation)

<!-- Impact Box -->
<div style="background:#f0f7ff; border-left:4px solid #0366d6; padding:15px; border-radius:4px; margin-top:20px;">
<strong style="color:#0366d6;">Why it matters:</strong><br>
We build <b>methods + benchmarks + applications</b> as a complete stack for localization—going beyond simple "translation-only" pipelines to ensure cultural depth and practical usability.
</div>

<br>
<hr>
<br>

<a id="thrust-2"></a>
## Thrust 2 — Biomedical NLP (BioNLP): Data-Centric & Privacy-Aware

<div style="margin-bottom:15px;">
<span style="background:#eafaf1; color:#27ae60; padding:4px 10px; border-radius:4px; font-weight:bold; font-size:0.85em; margin-right:5px;">🏆 BioASQ Champion (6 yrs)</span>
<span style="background:#f2f2f2; color:#555; padding:4px 10px; border-radius:4px; font-weight:bold; font-size:0.85em; margin-right:5px;">Briefings in Bioinformatics</span>
<span style="background:#f2f2f2; color:#555; padding:4px 10px; border-radius:4px; font-weight:bold; font-size:0.85em; margin-right:5px;">npj Digital Medicine</span>
<span style="background:#f2f2f2; color:#555; padding:4px 10px; border-radius:4px; font-weight:bold; font-size:0.85em; margin-right:5px;">Database (Oxford)</span>
</div>

**Motivation:** Biomedical data are often **high-noise / low-resource**, and clinical text requires strict privacy protection.

### 🔑 Key Contributions
- **BioASQ Biomedical QA (2020–2025)** [🌐 Project](http://bioasq.org)  
  Achieved **six consecutive years as the top team** in tasks involving evidence retrieval, semantic search, and evidence-grounded answering.
- **Relation Extraction: Survey & New Resource (PEDD)** [📄 Paper](https://academic.oup.com/bib/article/25/3/bbae132/7644532) [💾 Data](https://drive.google.com/drive/folders/1BeFkvjdDMPAvY0zdBd59JECZBC-kqpb7)  
  Proposed **PEDD**, a high-quality document-level dataset originally developed for the **AI CUP 2019** competition, addressing critical inconsistencies in legacy benchmarks (*Briefings in Bioinformatics, 2024*).
- **Clinical De-identification & Temporal Normalization with LLMs** [📄 Paper](https://www.nature.com/articles/s41746-025-01921-7)  
  - Discovery of **inverse scaling** beyond ~6B parameters without targeted adaptation (*npj Digital Medicine, 2025*).
  - Efficient solution via **PEFT/LoRA**, improving privacy protection while preserving clinical utility.
- **Data-centric Ensemble Learning** [📄 Paper](https://doi.org/10.1093/database/baae127)  
  **Enhancing biomedical relation extraction through data-centric and preprocessing-robust ensemble learning approach** (*Database, 2025*).

<!-- Impact Box -->
<div style="background:#f0fdf4; border-left:4px solid #27ae60; padding:15px; border-radius:4px; margin-top:20px;">
<strong style="color:#27ae60;">Why it matters:</strong><br>
Many global BioNLP systems optimize model architectures on curated datasets; we emphasize <b>real-world robustness</b> and <b>privacy constraints</b>, addressing barriers to actual hospital deployment.
</div>

<br>
<hr>
<br>

<a id="thrust-3"></a>
## Thrust 3 — Digital Humanities & Historical GIS

<div style="margin-bottom:15px;">
<span style="background:#fff5f5; color:#c0392b; padding:4px 10px; border-radius:4px; font-weight:bold; font-size:0.85em; margin-right:5px;">IJGIS 2025</span>
<span style="background:#fff5f5; color:#c0392b; padding:4px 10px; border-radius:4px; font-weight:bold; font-size:0.85em; margin-right:5px;">EMNLP 2023</span>
<span style="background:#fff5f5; color:#c0392b; padding:4px 10px; border-radius:4px; font-weight:bold; font-size:0.85em; margin-right:5px;">DSH 2025</span>
</div>

**Motivation:** Humanities data are frequently **unstructured**, **archaic in language**, and **lack annotations**, making standard supervised learning ineffective.

### 🔑 Key Contributions
- **Historical Maps Without Labels (IJGIS 2025)** [📄 Paper](https://www.tandfonline.com/doi/full/10.1080/13658816.2024.2425668) [💻 Code](https://figshare.com/articles/software/MapStyleSeg_full_code/25560276/1?file=45532515)  
  **Unsupervised domain adaptation (UDA)** bridging modern labeled maps and historical unlabeled maps for land-use understanding.
- **MingOfficial (EMNLP 2023)** [📄 Paper](https://aclanthology.org/2023.emnlp-main.266/) [💾 Data (Depository)](https://data.depositar.io/dataset/ming_official)  
  A historical context-aware representation learning framework embedding **time, space, and events** into career trajectory representations.
- **Computational Analysis of Ming Military Power** [📄 Paper](https://doi.org/10.1093/llc/fqad088) [📰 Media (中文)](https://www.sinica.edu.tw/cp/697)  
  A digital humanities approach to analyzing the roles of Supreme Commanders and Grand Coordinators in *Ming Shilu* (*Digital Scholarship in the Humanities, 2025*).
- **LLM-based Long-document Analysis**  
  Designing grounded RAG workflows with context fields (metadata + text) and human-in-the-loop benchmarks to improve traceability in historical sources.

<!-- Impact Box -->
<div style="background:#fff5f5; border-left:4px solid #c0392b; padding:15px; border-radius:4px; margin-top:20px;">
<strong style="color:#c0392b;">Why it matters:</strong><br>
Instead of applying generic tools, we develop <b>algorithmic methods</b> (like UDA and Context Embedding) that specifically overcome the fundamental "no-label" barrier in historical materials.
</div>

---

## 🚀 Selected Deployment Context

<table style="width:100%; border-collapse:collapse; margin-top:20px;">
<tr style="border-bottom:1px solid #eee;">
<td style="padding:10px 0; width:30%; vertical-align:top;"><b>Semiconductor</b></td>
<td style="padding:10px 0;">Domain LLMs for fab operation (<b>TSMC</b>, 2025)</td>
</tr>
<tr style="border-bottom:1px solid #eee;">
<td style="padding:10px 0; vertical-align:top;"><b>National Scale</b></td>
<td style="padding:10px 0;">AI semantic search for theses/dissertations (<b>National Central Library</b>, 2025)</td>
</tr>
<tr style="border-bottom:1px solid #eee;">
<td style="padding:10px 0; vertical-align:top;"><b>Public / Education</b></td>
<td style="padding:10px 0;">Teacher co-planning support with <b>NARLabs / NCHC</b> (2025)</td>
</tr>
<tr style="border-bottom:1px solid #eee;">
<td style="padding:10px 0; vertical-align:top;"><b>Healthcare</b></td>
<td style="padding:10px 0;">Clinical collaborations with <b>Cathay General</b> & <b>Landseed Int'l Hospital</b> (2021–2025)</td>
</tr>
<tr style="border-bottom:1px solid #eee;">
<td style="padding:10px 0; vertical-align:top;"><b>International</b></td>
<td style="padding:10px 0;">East Asian multilingual model merging with <b>KISTI</b> (Korea, 2025)</td>
</tr>
</table>