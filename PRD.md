# Product Requirement Document (PRD) - Advanced Multi-Agent Translation Lab
**Project Name:** yaelshir - Multi-Style Translation Chain & Semantic Drift Analytics
**Course:** Advanced AI Systems - Bar-Ilan University

---

## 1. Introduction & Background
[cite_start]This project demonstrates the "Broken Telephone" phenomenon in Large Language Models (LLMs) through an advanced multi-stage translation chain[cite: 18, 248]. [cite_start]Going beyond the basic requirements, this system serves as a comparative research tool that analyzes text degradation across a multi-agent pipeline and evaluates the efficiency of an automated linguistic self-correction loop[cite: 18, 252].

## 2. System Architecture (Level 3 - Specialized Multi-Agent)
[cite_start]The system deploys three distinct translation agents and a customized evaluation suite[cite: 258, 262]:
* [cite_start]**Agent 1 (En_to_Fr_Agent):** Utilizes `french_translator.md` skill to convert English to French[cite: 237, 258].
* [cite_start]**Agent 2 (Fr_to_He_Agent):** Utilizes `hebrew_translator.md` to convert intermediate French to Hebrew[cite: 238, 258].
* [cite_start]**Agent 3 (He_to_En_Agent):** Utilizes `english_translator.md` to return the text to final English[cite: 238, 258].
* [cite_start]**Advanced Analytics Tool:** Computes semantic vector distances and logs comparative degradation metrics[cite: 239, 262].

---

## 3. Creative & Advanced Features (Bonus Scope - Two-Phase Evaluation)
The system will run the translation experiment in two separate operational phases to isolate LLM behaviors:
* **Phase A (Standard Baseline):** A pure "Broken Telephone" simulation where text degrades naturally without intervention[cite: 248].
* **Phase B (Smart Agent Feedback Loop):** The agents activate a reflective validation mechanism, checking the intermediate translation against a dual-prompt verification step to correct semantic drift and optimize vector proximity back to the source text.
* **Comparative Drift Analytics:** The system automatically benchmarks three text styles (Academic, Slang, Technical) under both phases, rendering a comprehensive performance comparison.

---

## 4. Technical Specifications
* [cite_start]**Code Base:** Python 3.13[cite: 360].
* [cite_start]**Repository Layout:** Hosted on GitHub with clear documentation (README.md, PRD.md, PLAN.md, TODO.md).