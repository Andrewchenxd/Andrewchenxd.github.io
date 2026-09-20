---
layout: archive
title: "简历 CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# 陈帅 Shuai Chen

**算法工程师 · 小米集团小爱算法策略（正式工，2026.07 起）**  
Algorithm Engineer · Xiaomi XiaoAI · Multimodal LLM / RL / Agent / RSC

📧 shuai_chen@stu.xidian.edu.cn · 📱 15324104859  
🔗 [Google Scholar](https://scholar.google.com/citations?user=MfHFGkoAAAAJ&hl=zh-CN) · [GitHub](https://github.com/Andrewchenxd)

---

## 工作经历 Work Experience

### 小米集团 Xiaomi · 小爱算法策略（大模型视觉多模态组）
**正式工 Full-time Algorithm Engineer** · 2026.07 – 至今 · Beijing  
**实习 Intern** · 2025.02 – 2025.09

**小爱同学 GUI 多模态内容理解**
- 有屏场景（手机 / Pad / 智能座舱）下 13 类信息（地址、电话、邮箱、航班号、快递、日程等）的任意界面信息抽取
- 从错误 case 长尾分析入手，拓展场景并构建 OCR + MLLM 联合标注数据
- 方法路线：Qwen2.5-VL 蒸馏 → **ScreenR1-SFT** → RL（改进 GRPO 为 off-policy）→ **ScreenR1-COT**（多模态慢思考）
- 线上指标：打电话 89%→**96.27%**；导航 88%→**95.28%**；预识别 90%→**95%**
- 相关论文投稿 **ICLR 2026**

### 中国电科智能科技研究院
《电磁基础模型构建技术》· 2024.01 – 2024.12
- 信号重编程 → LLM token；LLM 基座下游微调；预训练任务 + test-time scaling + 数据清洗
- LoRA + 2×A100 半精度预训练 / 全精度微调部署

### 中航工业西安飞行自动控制研究所
《无人机平台上的高精度小目标检测系统》· 2023.06 – 2023.09
- 传统 CV 粗定位 + 热图 DL 精检；CPU–GPU 算子迁移、剪枝与知识蒸馏
- 达成单帧 **28.4ms**、定位误差 **≤5 px** 工业标准

---

## 教育背景 Education

**西安电子科技大学（211）**  
- 硕士 · 计算机科学与技术（A-）· 2023.09 – 至今  
- 本科 · 人工智能 · 2019.09 – 2023.06  

主修课程：数据结构、微机原理、智能数据挖掘、离散数学、统计学、高等数学、复变函数、模式识别、机器学习、信息论、自然语言处理等。

**校园经历**：已发表 SCI 论文 6 篇 · 日本东京大学学术合作交流（2023.03–至今）· 数学建模培训（校/国/美赛）· 西电脱口秀俱乐部 · 大创（智能农业 + 高光谱分析）

---

## 荣誉奖项 Honors & Awards

- 本科 GPA **Top 10%**
- **国家奖学金**
- 西电**校长奖提名**
- 西电数学建模校赛**特等奖**（1 次）
- **华为**产教结合奖学金（1 次）
- 北斗杯全国青少年科技创新大赛本科生实物组 **全国一等奖**（2021.05）
- XX 杯复杂电磁环境对抗 全国三等奖（2024.08）

---

## 研究兴趣 Research Interests

多模态大模型（M-LLM）· 强化学习（RL）· GUI Agent / System Prompt Learning · 认知无线电（RSC）· 电磁大模型

---

## 技能 Skills

- **框架**：PyTorch / TensorFlow / MindSpore / HuggingFace  
- **语言**：Python / C++ / Matlab  
- **LLM**：GPT-2、LLaMA-3.2、BERT、Qwen2.5-VL 的重编程、微调与推理；数据清洗与筛选；LoRA；GRPO / off-policy RL  
- **语言能力**：英语 CET-4 / CET-6（读研免修）  
- **工具**：Office、剪映、PDF 编辑  

---

## 授权专利 Patents

- 学生一作，**CN114494873**：一种基于 CutMix-ResNet 的半监督建筑物变化检测方法及系统（发明专利）

---

## 论文 Publications

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

完整元数据与 PDF 链接见 [Publications](/publications/) 与 [Google Scholar](https://scholar.google.com/citations?user=MfHFGkoAAAAJ&hl=zh-CN)。

---

## 引用指标 Citation Metrics

| Metric | Value |
|--------|-------|
| Citations | 77 |
| h-index | 6 |
| i10-index | 3 |
| SCI Papers | 6+ |
