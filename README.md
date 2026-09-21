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
LangChain · LangGraph · Agentic RAG（双路召回 + RRF 融合 + Rerank 精排）· BGE-M3 向量 · ReAct / Function Calling · 多模型路由与 Token 成本治理

**后端与架构**
Python · FastAPI · Django + DRF · CA 分层架构 · Celery 异步任务 · PostgreSQL · Redis · SQL Server

**系统集成 · 部署**
用友 U8 / PDM 与 SQL Server 集成 · Docker 镜像交付 · ONNX Runtime 边缘推理 · 服务器裸机部署与现场联调

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
