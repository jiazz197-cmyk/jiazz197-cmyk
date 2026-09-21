<div align="center">

# 贾振宇 · Carl Jia

**FDE 工程师 ｜ AI 应用落地 · Agentic RAG · 视觉检测**

上海海事大学 · 控制科学与工程 硕士在读 ｜ 上海

[![Email](https://img.shields.io/badge/Email-jiazz197%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:jiazz197@gmail.com)
[![npm](https://img.shields.io/badge/npm-%40carljia%2Fomd--dsh-CB3837?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/package/@carljia/omd-dsh)
[![Repos](https://img.shields.io/badge/13-181717?style=flat-square&logo=github&logoColor=white&label=%E5%BC%80%E6%BA%90%E4%BB%93%E5%BA%93)](https://github.com/jiazz197-cmyk?tab=repositories)

*把需求模糊、资源受限的一线场景，推到产线可用。*
*From vague requirements in the field to production-ready systems.*

</div>

---

## 🔭 我在做什么 · What I'm Doing

| 方向 | 在做的事 |
|---|---|
| **Agentic RAG 工程** | 企业知识库从 0 到 1：异构数据接入 → 语义分块 → 双路召回 + RRF + Rerank → 引用溯源与权限隔离 |
| **视觉检测交付** | AOI 门板检测双平台：数据集 → 标注 → 预标三桶分流 → 训练发布 → 产线 ONNX 推理，跨机部署 |
| **开源与科研** | [`omd-dsh`](https://github.com/jiazz197-cmyk/omd-dsh)（DSH 多模式智能体插件，MIT / [npm](https://www.npmjs.com/package/@carljia/omd-dsh)）· 工业故障诊断论文（IEEE TIM，中科院二区） |

## 🛠 技术栈 · Tech Stack

**AI 应用**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![RAG](https://img.shields.io/badge/Hybrid%20Retrieval-4B8BBE?style=flat-square&label=%E5%8F%8C%E8%B7%AF%E5%8F%AC%E5%9B%9E%20%2B%20RRF%20%2B%20Rerank)
![Rerank](https://img.shields.io/badge/BGE--M3-Embedding-4B8BBE?style=flat-square)
![LLM](https://img.shields.io/badge/Model%20Routing-FF6F00?style=flat-square&label=LLM%20%E8%B7%AF%E7%94%B1%20%E4%B8%8E%20Token%20%E6%B2%BB%E7%90%86)
![Prompt](https://img.shields.io/badge/Agent-ReAct%20%2F%20Function%20Calling-FF6F00?style=flat-square)

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

## 🚀 精选项目 · Featured Projects

### 1️⃣ [omd-dsh](https://github.com/jiazz197-cmyk/omd-dsh) · 多模式智能体插件 ![](https://img.shields.io/github/stars/jiazz197-cmyk/omd-dsh?style=flat-square&label=%E2%98%85&color=555)

> DeepSeek Harness（DSH）的多模式智能体插件：**7 个开箱即用的模式**，每个模式固定一套能力边界 + 一个模型路由。

- **强模型顶层 + 性价比模型做重复工作**：`omd_task` 按 tier 把重复调查委派给便宜模型、深度推理交给强模型
- preset 只做薄壳，复用 DSH 原生 `goal` / `workflow` / `ralph` / `subagent` / plan-mode，不重复造轮子
- MIT 开源，已发布 npm 包 [`@carljia/omd-dsh`](https://www.npmjs.com/package/@carljia/omd-dsh)

`TypeScript` `Agent Preset` `Model Routing` `npm`

### 2️⃣ [Enterprise-AI-sanitized](https://github.com/jiazz197-cmyk/Enterprise-AI-sanitized) · 企业级 AI 工作台 ![](https://img.shields.io/github/stars/jiazz197-cmyk/Enterprise-AI-sanitized?style=flat-square&label=%E2%98%85&color=555)

> 面向报价与订单一线业务的 AI 工作台（FastAPI + Vue 3 + LangChain），把散落在图纸、U8、PDM、Excel 与老员工经验里的环节，收敛成一个对话式入口。

- 报价流程：**3 天 → 15~30 分钟**；单任务最多展开 **1500 个 BOM 根件**，子件查询 **10000+ 条**
- BOM 并行展开默认 16 路 / 最高 **128 路**，IN 分批规避 SQL Server 2100 参数上限，故障隔离 + 熔断
- RAG 链路：意图路由 → Query 改写 → 稠密 + BM25 双路召回 → RRF 融合 → Rerank 精排；自建 200 条 Golden Set，**Recall@5 0.71 → 0.89**，引用出处覆盖率 **95%+**
- Route → UseCase → Port → Adapter 分层架构，CI 强制校验

`Python` `FastAPI` `LangChain` `RAG` `SQL Server`

### 3️⃣ [project_yamato_label2model](https://github.com/jiazz197-cmyk/project_yamato_label2model) · 标注到模型一体化平台 ![](https://img.shields.io/github/stars/jiazz197-cmyk/project_yamato_label2model?style=flat-square&label=%E2%98%85&color=555)

> 基于 Label Studio 二次开发的视觉模型全生命周期平台：打标签 → 模型训练 → 功能验证，串成一体化闭环并复用到后续产线交付。

- 训练调度由 **FastAPI 侧车**承接并注册进原项目状态机，隔离长时同步训练任务
- 编写 HuggingFace 与 sklearn 训练 adapter，区分不同训练路径；训练产物可导出至边缘端现场使用
- 项目立项合同 **50 万元+**

`Django 5.1` `DRF` `Celery` `React 18` `TypeScript`

### 4️⃣ [Project_NBHX_AOI](https://github.com/jiazz197-cmyk/Project_NBHX_AOI) · AOI 门板检测双平台

> 数据集 · 标注 · 训练 · 模型发布 · 产线推理的完整链路，跨机器部署、不共享存储，产线运行不受中心平台影响。

- **预标签三桶分流**：按置信度分高 / 中 / 低三桶，低置信强制人工复核
- **模型发布流水线**：`model.onnx + sha256 + model.yaml` → `FROM scratch` 单层镜像 → Registry v2 直推，digest 以仓库回执为准、同内容可复现
- 双平台接口由三份契约文档冻结，契约测试双端锁定，红则阻断合并

`Django` `FastAPI` `ONNX Runtime` `Celery` `Label Studio`

### 5️⃣ [Project_NBHX_RAGbot](https://github.com/jiazz197-cmyk/Project_NBHX_RAGbot) · 企业知识工作台

> 对话即检索，上传即建库：把制度文件、Excel 台账与员工经验，收敛成一个能对话、能溯源的工作入口。

- 混合检索：向量 + 词法双路召回，**RRF 融合重排**，输出流式且每条结论带引用
- 文档与 Excel 上传后自动解析、切分、向量化建库，随即可被对话检索引用
- 三个可独立部署的部分，各司其职

`Python` `FastAPI` `Vue 3` `Hybrid Retrieval` `Apache-2.0`

<details>
<summary><b>📦 其他公开仓库 · More repositories</b></summary>

<br>

| 仓库 | 说明 |
|---|---|
| [Token-Anatomy](https://github.com/jiazz197-cmyk/Token-Anatomy) | Token 结构与切分分析工具 |
| [awesome-dsh-plugin](https://github.com/jiazz197-cmyk/awesome-dsh-plugin) | DSH 插件精选列表（fork） |
| [DSH-better-sidebar](https://github.com/jiazz197-cmyk/DSH-better-sidebar) | DSH 侧边栏底座（fork） |

</details>

## 📄 科研成果 · Research

**[KD-MsGNet：面向港口门机驱动电机的跨工况故障诊断](https://github.com/jiazz197-cmyk)**
IEEE Transactions on Instrumentation & Measurement · 中科院二区 · 仪器测量 Top 期刊（Early Accept）

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

## 📊 GitHub

<div align="center">

[![Followers](https://img.shields.io/github/followers/jiazz197-cmyk?style=flat-square&label=Followers&color=0969da)](https://github.com/jiazz197-cmyk?tab=followers)
[![Stars](https://img.shields.io/github/stars/jiazz197-cmyk?style=flat-square&label=Total%20Stars&color=0969da)](https://github.com/jiazz197-cmyk?tab=repositories)
[![Commits](https://img.shields.io/github/commit-activity/y/jiazz197-cmyk?style=flat-square&label=Commits%2FYear&color=0969da)](https://github.com/jiazz197-cmyk)
[![Last Commit](https://img.shields.io/github/last-commit/jiazz197-cmyk/omd-dsh?style=flat-square&label=omd-dsh&color=0969da)](https://github.com/jiazz197-cmyk/omd-dsh)

</div>

## 📫 联系我 · Contact

- 📧 **Email**：jiazz197@gmail.com
- 📍 **上海 · Shanghai**
- 💬 欢迎交流 AI 应用落地、Agentic RAG、视觉检测工程实践 —— 也欢迎 FDE / AI 应用开发方向的岗位沟通

<div align="center">

![Visitors](https://komarev.com/ghpvc/?username=jiazz197-cmyk&color=0969da&style=flat-square&label=Profile%20Views)

</div>
