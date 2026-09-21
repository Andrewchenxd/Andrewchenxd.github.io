---
permalink: /
title: "陈帅的个人主页"
author_profile: true
lang: zh
redirect_from:
  - /about/
  - /about.html
---

<div class="lang-switch" markdown="0">
  <a class="btn btn--inverse" href="/en/" title="English">EN · English</a>
</div>

# 陈帅 Shuai Chen

**算法工程师** · 小米集团 · 小爱算法策略

📧 [shuai_chen@stu.xidian.edu.cn](mailto:shuai_chen@stu.xidian.edu.cn) · 📍 北京  
🔗 [Google Scholar](https://scholar.google.com/citations?user=MfHFGkoAAAAJ&hl=zh-CN) · [GitHub](https://github.com/Andrewchenxd) · [简历 CV](/cv/)

---

## 关于我

我是**陈帅**，西安电子科技大学计算机科学与技术硕士，现任**小米小爱团队算法工程师**（2026 年 7 月入职，正式员工）。此前于 2025.02–2025.09 在小米小爱算法策略实习，参与小爱同学 GUI 多模态内容理解。

我的研究与工程方向集中在：

- **多模态大模型（M-LLM）**：微调、蒸馏与重编程（GPT-2 / LLaMA-3.2 / BERT / Qwen2.5-VL）
- **强化学习（RL）**：GRPO 及 off-policy 改进，奖励与损失设计（ScreenR1-SFT / ScreenR1-COT）
- **Agent / System Prompt Learning**：Agent自进化算法、Training Free Prompt Optimize
- **认知无线电（RSC）**：信号分类、时频特征融合、辐射源个体识别

**学术指标**：SCI 论文 6 篇（多篇学生一作）· Google Scholar 引用 **77** · h-index **6** · i10-index **3** · 发明专利 1 项

---

## 工作经历

### 小米集团 · 小爱

**算法工程师** · `2026.07 – 至今`（正式）  
**算法实习生** · `2025.02 – 2025.09`

**项目：小爱同学 GUI 多模态内容理解**

面向有屏场景（手机、Pad、智能座舱等），支持地址、电话、邮箱、航班号、快递、日程等 **13 类信息**在任意屏幕界面的抽取，以多模态大模型赋能超级小爱。

- **问题分析**：线上错误 case 呈长尾分布（结构化知识错误、语义主题偏离等），单纯扩大 SFT 数据收益有限
- **场景拓展**：从地址 / 电话拓展到 13 类场景，采用 OCR + 多模态模型联合标注构建训练样本
- **模型优化**：完成 **SFT → RL** 路线升级；基于 Qwen2.5-VL 蒸馏得到 **ScreenR1-SFT**，再经强化学习得到具备多模态慢思考能力的 **ScreenR1-COT**；针对 GRPO on-policy 局限改为 **off-policy**，持续回收线上困难样本
- **业务成果**：
  - 打电话：89% → **96.27%**
  - 导航：88% → **95.28%**
  - 预识别：90% → **95%**
- 相关成果整理成文，投稿 **ICLR 2026**

### 中国电科智能科技研究院

**《电磁基础模型构建技术》** · `2024.01 – 2024.12`

- 信号重编程：将无线电信号编码为 LLM 可理解的 token，引入 LLM 作为基座做下游微调
- 预训练任务设计、test-time scaling law、数据清洗防污染、渐进式缩放策略
- 部署：LoRA 微调；2×A100 半精度预训练 → 全精度微调

### 中航工业西安飞行自动控制研究所

**《无人机平台上的高精度小目标检测系统》** · `2023.06 – 2023.09`

- 传统 CV 与深度学习联合检测：先粗定位降低计算开销，惯导动态修正，热图深度精检
- CPU–GPU 算子迁移、剪枝与知识蒸馏
- 达成单帧 **28.4 ms**、定位误差 **≤ 5 像素** 的工业指标

---

## 教育背景

| 时间 | 学校 | 专业 | 学位 |
|------|------|------|------|
| 2023.09 – 至今 | 西安电子科技大学（211） | 计算机科学与技术（A-） | 硕士 |
| 2019.09 – 2023.06 | 西安电子科技大学（211） | 人工智能 | 本科 |

**荣誉**：本科 GPA Top 10% · 国家奖学金 · **西电校长奖提名** · 数学建模校赛特等奖 · 华为产教结合奖学金 · 北斗杯全国青少年科技创新大赛实物组**全国一等奖**

**校园经历**：东京大学学术合作交流（2023.03–2026.06）· 数学建模（校赛 / 国赛 / 美赛）· 西电脱口秀俱乐部 · 大学生创新创业训练计划（智能农业 + 高光谱分析）

---

## 代表论文

完整列表见 [论文 Publications](/publications/) ｜ [Google Scholar](https://scholar.google.com/citations?user=MfHFGkoAAAAJ&hl=zh-CN)

1. **Learning Temporal–Spectral Feature Fusion Representation for Radio Signal Classification** — *IEEE TII*（IF 11.8，SCI TOP 1 区），学生一作，2024
2. **A Generative Self-supervised Framework for Cognitive Radio Leveraging Time-Frequency Features and Attention-based Fusion** — *IEEE TWC*（IF 8.79，SCI TOP 1 区），学生一作，2024
3. **RadioLLM: Introducing Large Language Model into Cognitive Radio via Hybrid Prompt and Token Reprogrammings** — *JSAC 在投*（CCF-A）/ arXiv:2501.17888，学生一作
4. **Enhanced Prediction of Partial Nitrification-Anammox Process…** — *J. Environmental Management*（IF 7.9，SCI TOP 2 区），学生一作，2025
5. **ACPO: Adaptive Curriculum Policy Optimization for Aligning Vision-Language Models in Complex Reasoning** — arXiv:2510.00690，2025（与小米小爱合作）

---

## 授权专利

- **一种基于 CutMix-ResNet 的半监督建筑物变化检测方法及系统** — 学生一作，`CN114494873`（发明专利）

---

## 竞赛获奖

| 时间 | 奖项 | 赛事 |
|------|------|------|
| 2024.08 | 全国三等奖 | 复杂电磁环境下辐射源识别相关赛事 |
| 2021.05 | **全国一等奖**（实物组） | 北斗杯全国青少年科技创新大赛 |

---

## 技能

- **深度学习框架**：PyTorch · TensorFlow · MindSpore · HuggingFace
- **编程语言**：Python · C++ · Matlab
- **大模型技术栈**：微调与重编程（GPT-2 / LLaMA-3.2 / BERT / Qwen2.5-VL）· 数据清洗与筛选 · LoRA · RLHF / GRPO
- **其他**：论文写作与数学理论分析
- **语言**：英语（CET-4 / CET-6，读研免修）

---

<div class="lang-switch" markdown="0">
  <a class="btn btn--inverse" href="/en/" title="English">切换到英文版 English →</a>
</div>
