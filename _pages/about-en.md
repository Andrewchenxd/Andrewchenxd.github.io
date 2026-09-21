---
permalink: /en/
title: "Shuai Chen 陈帅"
author_profile: true
lang: en
---

<div class="lang-switch" markdown="0">
  <a class="btn btn--inverse" href="/" title="中文">中文 · Chinese</a>
</div>

# Shuai Chen 陈帅

**Algorithm Engineer** · Xiaomi Corporation · XiaoAI Algorithm Strategy (Multimodal LLM Team)

📧 [shuai_chen@stu.xidian.edu.cn](mailto:shuai_chen@stu.xidian.edu.cn) · 📍 Beijing, China  
🔗 [Google Scholar](https://scholar.google.com/citations?user=MfHFGkoAAAAJ&hl=en) · [GitHub](https://github.com/Andrewchenxd) · [CV](/en/cv/)

---

## About

I am **Shuai Chen**, an **Algorithm Engineer** at Xiaomi's XiaoAI team (full-time since **July 2026**). I am completing my M.S. in Computer Science & Technology (Discipline **A-**) at **Xidian University**, after a B.S. in Artificial Intelligence. From **February 2025 to September 2025**, I interned on the same team, working on **GUI multimodal content understanding** for XiaoAI.

My research and engineering focus includes:

- **Multimodal LLMs (M-LLM)**: fine-tuning, distillation, and reprogramming (GPT-2 / LLaMA-3.2 / BERT / Qwen2.5-VL)
- **Reinforcement Learning (RL)**: GRPO and off-policy improvements; reward and loss design (ScreenR1-SFT / ScreenR1-COT)
- **Agents / System Prompt Learning**: GUI agents, system-prompt preloading, and skill routing
- **Cognitive Radio Signal processing (RSC)**: signal classification, time–frequency feature fusion, and specific emitter identification

**Academic metrics**: **6 SCI papers** (several as student first author) · Google Scholar citations **77** · h-index **6** · i10-index **3** · **1 invention patent**

---

## Research Interests

| Area | Keywords |
|------|----------|
| **M-LLM** | Qwen2.5-VL, distillation, LoRA, signal / token reprogramming |
| **RL** | GRPO, off-policy RL, reward design, slow-thinking CoT |
| **Agent** | GUI agents, on-screen information extraction, System Prompt Learning |
| **RSC** | Cognitive radio, time–frequency fusion, modulation classification, emitter identification |
| **Applications** | Smart cockpit / on-screen assistants / electromagnetic foundation models / remote-sensing change detection |

---

## Experience

### Xiaomi Corporation · XiaoAI Algorithm Strategy (Multimodal LLM Team)

**Algorithm Engineer** · `Jul 2026 – present` (full-time)  
**Algorithm Intern** · `Feb 2025 – Sep 2025`

**Project: GUI Multimodal Content Understanding for XiaoAI**

In on-screen scenarios (smartphone, tablet, smart cockpit, etc.), extract **13 types** of information — address, phone number, email, flight number, delivery tracking, calendar events, and more — from **arbitrary UI screens**, empowering Super XiaoAI with multimodal large language models.

- **Problem analysis**: online error cases follow a long-tail distribution (structured-knowledge errors, semantic-topic drift, etc.); simply scaling SFT data yields limited gains
- **Scenario expansion**: extended from address/phone to **13 scenarios**; built training data via **OCR + multimodal model joint labeling**
- **Model optimization**: shifted from **SFT → RL**; distilled Qwen2.5-VL into **ScreenR1-SFT**, then used RL to obtain **ScreenR1-COT** with multimodal slow thinking; replaced on-policy GRPO with **off-policy** updates and continuous recovery of hard online samples
- **Business results**:
  - Phone call: 89% → **96.27%**
  - Navigation: 88% → **95.28%**
  - Pre-recognition: 90% → **95%**
- Related results written up and submitted to **ICLR 2026**

### China Electronics Technology Group (CETC) Intelligent Technology Research Institute

**Project: Construction Technology for Electromagnetic Foundation Models** · `Jan 2024 – Dec 2024`

- Signal reprogramming: encoded radio signals as tokens understandable by LLMs; used LLMs as backbones for downstream fine-tuning
- Pretraining task design, test-time scaling laws, data cleaning against contamination, and progressive scaling strategies
- Deployment: LoRA fine-tuning; **2×A100** half-precision pretraining → full-precision fine-tuning

### AVIC Xi'an Flight Automatic Control Research Institute

**Project: High-Precision Small-Target Detection System on UAV Platforms** · `Jun 2023 – Sep 2023`

- Hybrid classical CV + deep learning detection: coarse localization to reduce compute, INS-aided dynamic correction, then heatmap-based deep refinement
- CPU–GPU operator migration, pruning, and knowledge distillation
- Achieved industrial metrics of **28.4 ms** per frame and localization error **≤ 5 pixels**

---

## Education

| Period | University | Major | Degree |
|--------|------------|-------|--------|
| Sep 2023 – present | Xidian University (Project 211) | Computer Science & Technology (Discipline A-) | M.S. |
| Sep 2019 – Jun 2023 | Xidian University (Project 211) | Artificial Intelligence | B.S. |

**Honors**: Top 10% undergraduate GPA · National Scholarship · Nominee, Xidian University President's Award · First Prize, University Mathematical Modeling Contest · Huawei Industry–Education Scholarship · **National First Prize** (Physical Category), Beidou Cup National Youth Science & Technology Innovation Competition

**Campus experience**: academic exchange with the University of Tokyo (Mar 2023 – present) · mathematical modeling (university / national / MCM) · Xidian Stand-up Comedy Club · National College Student Innovation & Entrepreneurship Training Program (smart agriculture + hyperspectral analysis)

---

## Selected Publications

Full list: [Publications](/en/publications/) ｜ [Google Scholar](https://scholar.google.com/citations?user=MfHFGkoAAAAJ&hl=en)

1. **Learning Temporal–Spectral Feature Fusion Representation for Radio Signal Classification** — *IEEE Transactions on Industrial Electronics (TII)* (IF 11.8, SCI TOP 1), student first author, 2024
2. **A Generative Self-supervised Framework for Cognitive Radio Leveraging Time-Frequency Features and Attention-based Fusion** — *IEEE Transactions on Wireless Communications (TWC)* (IF 8.79, SCI TOP 1), student first author, 2024
3. **RadioLLM: Introducing Large Language Model into Cognitive Radio via Hybrid Prompt and Token Reprogrammings** — *under review at IEEE JSAC* (CCF-A) / arXiv:2501.17888, student first author
4. **Enhanced Prediction of Partial Nitrification-Anammox Process…** — *Journal of Environmental Management* (IF 7.9, SCI TOP 2), student first author, 2025
5. **ACPO: Adaptive Curriculum Policy Optimization for Aligning Vision-Language Models in Complex Reasoning** — arXiv:2510.00690, 2025 (in collaboration with Xiaomi XiaoAI)

---

## Patent

- **A Semi-supervised Building Change Detection Method and System Based on CutMix-ResNet** — student first author, `CN114494873` (invention patent)

---

## Awards

| Date | Award | Event |
|------|-------|-------|
| Aug 2024 | National Third Prize | Competition on emitter recognition under complex electromagnetic environments |
| May 2021 | **National First Prize** (Physical Category) | Beidou Cup National Youth Science & Technology Innovation Competition |

---

## Skills

- **Deep learning frameworks**: PyTorch · TensorFlow · MindSpore · HuggingFace
- **Programming languages**: Python · C++ · Matlab
- **LLM stack**: fine-tuning & reprogramming (GPT-2 / LLaMA-3.2 / BERT / Qwen2.5-VL) · data cleaning & curation · LoRA · RLHF / GRPO
- **Other**: academic writing & mathematical analysis
- **Languages**: English (CET-4 / CET-6; exempted in graduate school)
- **Interests**: fitness, hiking, swimming, stand-up comedy

---

<div class="lang-switch" markdown="0">
  <a class="btn btn--inverse" href="/" title="中文">← 中文版 Chinese</a>
</div>
