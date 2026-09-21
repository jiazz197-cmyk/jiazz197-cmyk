<div align="center">

# 贾振宇 · Carl Jia

**FDE 方向 ｜ AI 应用落地 · Agentic RAG · 视觉检测**

上海海事大学 · 控制科学与工程 硕士在读 ｜ 上海

[![Email](https://img.shields.io/badge/Email-jiazz197%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:jiazz197@gmail.com)
[![npm](https://img.shields.io/badge/npm-%40carljia%2Fomd--dsh-CB3837?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/package/@carljia/omd-dsh)

*把需求模糊、资源受限的一线场景，推到产线可用。*
*From vague requirements in the field to production-ready systems.*

</div>

---

## 🔭 我在做什么 · What I'm Doing

| 方向 | 在做的事 |
|---|---|
| **Agentic RAG 工程** | 企业知识库从 0 到 1：异构数据接入 → 语义分块 → 双路召回 + RRF + Rerank → 引用溯源与权限隔离 |
| **视觉检测交付** | AOI 门板检测双平台：数据集 → 标注 → 预标三桶分流 → 训练发布 → 产线 ONNX 推理，跨机部署 |
| **开源与科研** | [omd-dsh](https://github.com/jiazz197-cmyk/omd-dsh) —— DSH 多模式智能体插件（MIT / [npm](https://www.npmjs.com/package/@carljia/omd-dsh)）· 工业故障诊断论文（IEEE TIM，中科院二区） |

## 🛠 技术栈 · Tech Stack

**AI 应用**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![RAG](https://img.shields.io/badge/Hybrid%20Retrieval-4B8BBE?style=flat-square&label=%E5%8F%8C%E8%B7%AF%E5%8F%AC%E5%9B%9E%20%2B%20RRF%20%2B%20Rerank)
![Rerank](https://img.shields.io/badge/BGE--M3-Embedding-4B8BBE?style=flat-square)
![LLM](https://img.shields.io/badge/Model%20Routing-FF6F00?style=flat-square&label=LLM%20%E8%B7%AF%E7%94%B1%20%E4%B8%8E%20Token%20%E6%B2%BB%E7%90%86)
![Agent](https://img.shields.io/badge/Agent-ReAct%20%2F%20Function%20Calling-FF6F00?style=flat-square)

**后端与架构**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django%20%2B%20DRF-092E20?style=flat-square&logo=django&logoColor=white)
![Vue](https://img.shields.io/badge/Vue%203-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![SQLServer](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)

**系统集成 · 部署**
![U8](https://img.shields.io/badge/ERP%20Integration-6E4C13?style=flat-square&label=%E7%94%A8%E5%8F%8B%20U8%20%2F%20PDM)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX%20Runtime-005CED?style=flat-square&logo=onnx&logoColor=white)
![Linux](https://img.shields.io/badge/On--site%20Delivery-FCC624?style=flat-square&logo=linux&logoColor=black&label=%E8%A3%B8%E6%9C%BA%E9%83%A8%E7%BD%B2%20%2F%20%E7%8E%B0%E5%9C%BA%E8%81%94%E8%B0%83)

## 📄 科研成果 · Research

**KD-MsGNet：面向港口门机驱动电机的跨工况故障诊断**
IEEE Transactions on Instrumentation & Measurement · 中科院二区 · 仪器测量 Top 期刊（`Early Accept`）

- 针对跨工况域偏移、故障样本不平衡、边缘算力受限三大工程难题，提出两阶段学习框架
- 教师模型 DWCL 用多尺度双向门控单元（MsBiGRU）+ 域差异引导的加权对比学习做跨工况特征学习
- 学生模型以**无标签知识蒸馏**迁移诊断能力：参数量 **4.34M → 127.78K**，FLOPs **1.578G → 59.74M**，体积 **16.57MB → 0.54MB**（约 30 倍）
- 平均准确率 **98.73% / 91.54%**，已在 Orange Pi 等边缘硬件实机验证现场实时推理

<details>
<summary><b>🎓 教育与经历 · Education & Experience</b></summary>

<br>

| 时间 | 经历 |
|---|---|
| 2024.09 - 至今 | **上海海事大学** · 控制科学与工程 · 硕士（一等 / 二等学业奖学金） |
| 2019.09 - 2023.07 | **西安建筑科技大学** · 电气工程及其自动化 · 本科 |
| 2026.08 - 2026.10 | 产线现场交付 · AOI 视觉检测模型迭代平台（训练平台负责人，3 人 22 天跑完四个里程碑并现场验收） |
| 2025.12 - 2026.07 | 企业级 AI 工作台 · 后端开发负责人（需求对接 → 原型 → 上线 → 业务方培训全链路交付） |

</details>

## 📫 联系我 · Contact

- 📧 **Email**：jiazz197@gmail.com
- 📍 **上海 · Shanghai**
- 💬 欢迎交流 AI 应用落地、Agentic RAG、视觉检测工程实践 —— 也欢迎 FDE / AI 应用开发方向的岗位沟通
