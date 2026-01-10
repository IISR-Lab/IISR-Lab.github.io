
<style>
    body { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif; max-width: 1000px; margin: 0 auto; padding: 20px; line-height: 1.6; color: #333; }
    a { color: #0366d6; text-decoration: none; }
    a:hover { text-decoration: underline; }
    table { width: 100%; border-collapse: collapse; }
    img { max-width: 100%; }
</style>


[Home](index.html) ｜ [People](people.html) ｜ [Research](research.html) ｜ [Impact](impact.html) ｜ [Publications](publications.html) ｜ [News](news.html) ｜ [Join Us](joinus.html) ｜ [Contact](contact.html)

---

# Research

IISR advances intelligent information services through three major thrusts (2021–2025), integrating **LLMs**, **retrieval**, **data-centric AI**, and **cross-domain representation learning**.

---

## Thrust 1 — Biomedical NLP (BioNLP): Data-Centric, Noise-Robust, Privacy-Aware

**Motivation:** Biomedical data are often **high-noise / low-resource**, and clinical text requires strict privacy protection.

### Key Contributions
- **Data-centric ensemble learning** for biomedical relation extraction with preprocessing robustness  
  - Automated data augmentation and normalization; heterogeneous ensembles of biomedical pretrained models.
- **Clinical de-identification & temporal normalization with LLMs**  
  - Discovery of **inverse scaling** beyond ~6B parameters without targeted adaptation  
  - Efficient solution via **PEFT/LoRA**, improving privacy protection while preserving clinical utility.
- **BioASQ biomedical QA (2020–2025):** evidence retrieval + semantic search + evidence-grounded answering  
  - Achieved **six consecutive years as the top team**.

### Why it matters (vs. typical prior work)
Many global BioNLP systems optimize model architectures on curated datasets; we emphasize **real-world robustness** and **privacy constraints**, addressing practical deployment barriers.

---

## Thrust 2 — Taiwan-Localized LLMs & Low-Resource Languages (Hokkien)

**Motivation:** Mainstream LLMs often lack **Traditional Chinese (Taiwan) cultural grounding** and have limited coverage for local languages (e.g., Taiwanese Hokkien).

### Key Contributions
- **Chat Vector (ACL 2024)**  
  A lightweight, economical alignment technique that transfers instruction-following ability using weight-space additivity—reducing dependence on expensive RLHF.
- **TWBias (EMNLP 2024)**  
  The first benchmark for assessing social bias in Traditional Chinese LLMs **through a Taiwan cultural lens**, supporting trustworthy evaluation for Taiwan-localized models.
- **Hokkien NLP & multimodal learning**
  - Standardizing and bridging multiple writing systems (COLING 2024)
  - **ATAIGI (NAACL 2025):** a multimodal learning app leveraging generative models for low-resource Hokkien education.

### Why it matters
We build **methods + benchmarks + applications** as a complete stack for localization—beyond “translation-only” pipelines.

---

## Thrust 3 — Digital Humanities & Historical GIS: Context-Aware Methods for Unlabeled Data

**Motivation:** Humanities data are frequently **unstructured**, **archaic in language**, and **lack annotations**.

### Key Contributions
- **MingOfficial (EMNLP 2023)**  
  A historical context-aware representation learning framework embedding **time, space, and events** into career trajectory representations.
- **Historical maps without labels (IJGIS 2025)**  
  **Unsupervised domain adaptation** bridging modern labeled maps and historical unlabeled maps for land-use understanding.
- **LLM-based long-document analysis & grounded RAG workflows**  
  Designing context fields (metadata + text) and human-in-the-loop benchmarks to improve traceability and groundedness in historical sources.

### Why it matters
Instead of applying generic tools, we develop **algorithmic methods** that overcome the fundamental “no-label” barrier in historical materials.

---

## Selected Deployment Context
- Semiconductor: domain LLMs for fab operation (TSMC, 2025)
- National-scale search: AI semantic search for theses/dissertations (National Central Library, 2025)
- Public/education: teacher co-planning support with NARLabs/NCHC (2025)
- Healthcare: clinical collaborations with hospitals (2021–2025)
- International: collaboration with Korea (KISTI) on East Asian multilingual model merging (2025)
