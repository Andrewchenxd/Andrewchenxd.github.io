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

**Algorithm Engineer** · Xiaomi · XiaoAI Algorithm Strategy (Multimodal LLM Team)

📧 [shuai_chen@stu.xidian.edu.cn](mailto:shuai_chen@stu.xidian.edu.cn) · 📍 Beijing, China  
🔗 [Google Scholar](https://scholar.google.com/citations?user=MfHFGkoAAAAJ&hl=en) · [GitHub](https://github.com/Andrewchenxd) · [CV](/en/cv/)

---

## About

I am **Shuai Chen**, an Algorithm Engineer on Xiaomi's XiaoAI team (full-time since July 2026). I am completing my M.S. in Computer Science & Technology (Discipline A-) at Xidian University, after a B.S. in Artificial Intelligence. From February to September 2025 I interned on the same team, working on GUI multimodal content understanding for XiaoAI.

My research and engineering interests include:

- **Multimodal LLMs (M-LLM)**: fine-tuning, distillation, and reprogramming (GPT-2 / LLaMA-3.2 / BERT / Qwen2.5-VL)
- **Reinforcement Learning (RL)**: GRPO and off-policy improvements; reward and loss design (ScreenR1-SFT / ScreenR1-COT)
- **Agents / System Prompt Learning**: GUI agents, system-prompt preloading, and skill routing
- **Cognitive Radio Signal (RSC)**: signal classification, time–frequency fusion, emitter identification

**Metrics**: 6 SCI papers (several as student first author) · Google Scholar citations **77** · h-index **6** · i10-index **3** · 1 invention patent

---

## Research Interests

| Area | Keywords |
|------|----------|
| **M-LLM** | Qwen2.5-VL, distillation, LoRA, signal / token reprogramming |
| **RL** | GRPO, off-policy RL, reward design, slow-thinking CoT |
| **Agent** | GUI agents, on-screen information extraction, System Prompt Learning |
| **RSC** | Cognitive radio, time–frequency fusion, modulation classification, emitter ID |
| **Applications** | Smart cockpit / screen assistants / electromagnetic foundation models / remote sensing |

---

## Experience

### Xiaomi · XiaoAI Algorithm Strategy (Multimodal LLM Team)

**Algorithm Engineer** · `Jul 2026 – present` (full-time)  
**Research Intern** · `Feb 2025 – Sep 2025`

**Project: GUI Multimodal Content Understanding for XiaoAI**

On-screen scenarios (phone, tablet, smart cockpit, etc.): extract **13 types** of information — address, phone, email, flight number, delivery, calendar, and more — from arbitrary UI screens, empowering Super XiaoAI with multimodal LLMs.

- **Problem analysis**: online errors follow a long-tail distribution (structured-knowledge failures, semantic drift); simply scaling SFT data helps little
- **Scenario expansion**: from address/phone to 13 scenarios; OCR + multimodal joint labeling for training data
- **Modeling**: moved from **SFT → RL**; distilled Qwen2.5-VL into **ScreenR1-SFT**, then RL to **ScreenR1-COT** with multimodal slow thinking; replaced on-policy GRPO with **off-policy** updates and continuous hard-example replay
- **Online results**:
  - Phone call: 89% → **96.27%**
  - Navigation: 88% → **95.28%**
  - Pre-recognition: 90% → **95%**
- Results written up and submitted to **ICLR 2026**

### CETC Intelligent Technology Research Institute

**Electromagnetic Foundation Model Construction** · `Jan 2024 – Dec 2024`

- Signal reprogramming: encode radio signals as LLM tokens; adapt LLMs for downstream tasks
- Pretraining task design, test-time scaling laws, decontamination, progressive scaling
- Deployment: LoRA fine-tuning; 2×A100 half-precision pretraining → full-precision fine-tuning

### AVIC Xi'an Flight Automatic Control Research Institute

**High-Precision Small-Target Detection on UAV Platforms** · `Jun 2023 – Sep 2023`

- Hybrid classical CV + deep detection: coarse localization, INS-aided correction, heatmap refinement
- CPU–GPU operator migration, pruning, knowledge distillation
- Achieved **28.4 ms**/frame and localization error **≤ 5 pixels**

---

## Education

| Period | University | Major | Degree |
|--------|------------|-------|--------|
| Sep 2023 – present | Xidian University (211) | Computer Science & Technology (A-) | M.S. |
| Sep 2019 – Jun 2023 | Xidian University (211) | Artificial Intelligence | B.S. |

**Honors**: Top 10% GPA · National Scholarship · President Award Nominee · Provincial Math Modeling First Prize · Huawei Industry-Education Scholarship · **National First Prize** (Beidou Cup, physical category)

**Campus**: academic exchange with the University of Tokyo (2023.03–present) · math modeling contests · stand-up comedy club · innovation programs (smart agriculture + hyperspectral analysis)

---

## Selected Publications

Full list: [Publications](/en/publications/) ｜ [Google Scholar](https://scholar.google.com/citations?user=MfHFGkoAAAAJ&hl=en)

1. **Learning Temporal–Spectral Feature Fusion Representation for Radio Signal Classification** — *IEEE TII* (IF 11.8), student first author, 2024
2. **A Generative Self-supervised Framework for Cognitive Radio Leveraging Time-Frequency Features and Attention-based Fusion** — *IEEE TWC* (IF 8.79), student first author, 2024
3. **RadioLLM: Introducing Large Language Model into Cognitive Radio via Hybrid Prompt and Token Reprogrammings** — *under review at JSAC* (CCF-A) / arXiv:2501.17888, student first author
4. **Enhanced Prediction of Partial Nitrification-Anammox Process…** — *J. Environmental Management* (IF 7.9), student first author, 2025
5. **ACPO: Adaptive Curriculum Policy Optimization for Aligning Vision-Language Models in Complex Reasoning** — arXiv:2510.00690, 2025 (with Xiaomi XiaoAI)

---

## Patent

- **Semi-supervised building change detection based on CutMix-ResNet** — student first author, `CN114494873` (invention patent)

---

## Awards

| Date | Award | Event |
|------|-------|-------|
| Aug 2024 | National Third Prize | Emitter recognition under complex electromagnetic environments |
| May 2021 | **National First Prize** (physical) | Beidou Cup National Youth Science & Technology Innovation Competition |

---

## Skills

- **Deep learning**: PyTorch · TensorFlow · MindSpore · HuggingFace
- **Languages**: Python · C++ · Matlab
- **LLM stack**: fine-tuning & reprogramming (GPT-2 / LLaMA-3.2 / BERT / Qwen2.5-VL) · data curation · LoRA · RLHF / GRPO
- **Other**: academic writing & mathematical analysis
- **Languages**: English (CET-4 / CET-6)

---

<div class="lang-switch" markdown="0">
  <a class="btn btn--inverse" href="/" title="中文">← 中文版 Chinese</a>
</div>
