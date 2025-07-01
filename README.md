![Python](https://img.shields.io/badge/Python-3.10-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Conda](https://img.shields.io/badge/Env-Miniconda-yellow)
![Platform](https://img.shields.io/badge/Platform-DeepSeek--1.5B-red)

# 🚀 Nankai-Chinasoft-project

> 2025 年度夏季南开大学实训项目 · 基于国产大模型 DeepSeek 的小型训练与部署实践

本项目由南开大学密码与网络空间安全学院 2023 级四名同学在中软国际实训平台完成，在老师的指导下，旨在深入掌握大语言模型的基本原理，并使用国产开源模型 DeepSeek 实现小型 LLM 的微调与部署。

---

## 📚 项目背景

- **实训时间**：2025 年暑期（共 4 周）6.30——7.27
- **实训单位**：南开大学 × 北京中软国际信息技术有限公司
- **实训方向**：人工智能 · 大模型工程化
- **项目目标**：
  - 掌握 Transformer 与大语言模型原理
  - 探索 LoRA、BitsAndBytes 等微调技术
  - 实现模型训练 → 推理 → 评估 → 应用全流程

---
## 👥 团队成员

| 姓名   | 分工职责               | 学号     |
|--------|------------------------|----------|
| 肖俊涛 | 项目管理 & 模型训练    | 2313226  |
| 陈宇心 | 数据处理 & 微调实现    | 2311874  |
| 左智勤 | 推理部署 & CLI 接口    | 2312972  |
| 支恺健 | 模型评估 & 文档撰写    | 2312685  |

> 🧑‍🏫 **指导教师**：吴迪（中软国际教育指导老师）

---

## 🧰 技术栈与工具

| 分类 | 技术 |
|------|------|
| 语言 | Python 3.10 |
| 环境 | Miniconda + Jupyter |
| 模型 | DeepSeek 1.5B |
| 微调 | LoRA + PEFT |
| 量化 | BitsAndBytes（8-bit） |
| 工具库 | HuggingFace Transformers、Datasets、Accelerate |
| 运行平台 | 本地 GPU / 云服务器（可选） |

---

## 📅 项目进度安排

| 周数 | 任务内容                                  |
|--------|----------------------------------------------|
| 第 1 周 | 项目启动、理论学习、环境配置、模型理解       |
| 第 2 周 | 数据准备、LoRA 微调、训练脚本实现            |
| 第 3 周 | 模型训练实验、评估指标实现                   |
| 第 4 周 | 推理接口开发、总结报告撰写与展示             |

---

## 📁 项目结构
```text
Nankai-Chinasoft-project/
├── data/              # 数据集与预处理
├── models/            # 微调后模型保存路径
├── scripts/           # 训练 / 推理 / 评估脚本
├── notebooks/         # Jupyter 笔记本记录与分析
├── requirements.txt   # 所需依赖列表
├── README.md          # 项目说明文件
├── LICENSE            # 开源许可证
└── .gitignore         # Git 忽略配置
