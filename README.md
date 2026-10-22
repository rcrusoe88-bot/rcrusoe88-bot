<div align="center">

# Hi there, I'm Reginald Crusoe (余小莫) 👋

### 🚀 AI Agent Engineer · Biotech Tooling Builder · Full-Stack Explorer

<p align="center">
  <a href="https://github.com/rcrusoe88-bot">
    <img src="https://img.shields.io/github/followers/rcrusoe88-bot?label=Followers&style=flat-square&color=2ea44f" alt="Followers" />
  </a>
  <a href="https://github.com/rcrusoe88-bot?tab=repositories">
    <img src="https://img.shields.io/badge/Repositories-16-blue?style=flat-square" alt="Repos" />
  </a>
  <img src="https://img.shields.io/badge/Focus-AI_Agent_%7C_mRNA_CMC_%7C_Design_System-8a2be2?style=flat-square" alt="Focus Area" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="License" />
</p>

<p align="center">
  专注于 <b>LLM Agent 优化与专项技能构建</b> · <b>mRNA/LNP 生物医药数字化工具链</b> · <b>现代企业级设计系统与效率工程</b>
</p>

---

</div>

## 💡 About Me

- 🔬 **Biotech & mRNA CMC**：深耕 mRNA IVT、靶向 LNP、分析方法与 CMC 台账管理，主导打造了面向生产研发的 Materia ERP 及服务于**「信使引擎 (RNAscript)」公众号**的端到端自动化内容智能与学术情报工作流。
- 🤖 **AI Agent & Codex Skills**：设计严格遵循契约规范的即插即用 Agent 技能库与自动化工作流（涵盖学术文献挖掘、逆向分析、推文创作、PPT 需求对齐等）。
- 🎨 **Design System & Frontend**：主导高标准设计系统研发，主张“反 Slop 机械生成”，建立参数强约束的组件与契约层（`registry.json`）。
- 🛠️ **System Utilities**：追求轻量、高安全、免管理员提权的现代化桌面工具与脚本化工程。

---

## 🌟 Featured Project Matrix (精选项目矩阵)

### 🧬 1. 生物医药与 mRNA/LNP 数字化 ·「信使引擎」工具矩阵 (Biotech & CMC)
> 包含面向 mRNA/LNP 研发与生产的 **Materia ERP 全栈系统**，专为生物医药深度公众号**「信使引擎 (RNAscript)」**定制开发的内容生产闭环，以及用于学术文献挖掘与 PMC OA 全文批量采集的情报工具链（涵盖文献检索分层、全文下载、选题规划、长文创作、标题摘要提取、视觉封面生成与排版内联渲染）。

| 项目 | 技术栈 / 规范 | 核心亮点与「信使引擎」定位 | 仓库链接 |
| :--- | :--- | :--- | :---: |
| **wsj-erp-system** | `React` `NestJS` `PostgreSQL` | **Materia ERP 物料管理系统**：面向 mRNA/LNP 生产的物料出入库、批次追溯与效期管理（全栈生产中枢） | [查看项目](https://github.com/rcrusoe88-bot/wsj-erp-system) |
| **lit-mining** | `Python` `Multi-Agent` `Workflow` | **文献挖掘完整工作流**：主题句 → 检索式拆解 → 命中量探测 → 人工审核 → 多源采集 → 打水分层 → 下载 OA 全文 → 分层报告。跨 Claude Code / ChatGPT / WorkBuddy | [查看项目](https://github.com/rcrusoe88-bot/lit-mining) |
| **pmc-oa-pdf** | `Python` `Stdlib` `PMC API` | **PMC OA PDF 批量下载引擎**：绕过 pmc.ncbi.nlm.nih.gov 工作量证明验证机制（PoW gate），纯标准库实现，98.7% 实测覆盖率 | [查看项目](https://github.com/rcrusoe88-bot/pmc-oa-pdf) |
| **rnascript-wechat** | `Claude Code` `Prompt` *(Private)* | **「信使引擎」深度推文创作 Skill**：面向 mRNA/LNP 领域的前沿论文拆解、主题创作与 Word 规范交付 | [查看项目](https://github.com/rcrusoe88-bot/rnascript-wechat) |
| **wechat-cmc-topic-planner** | `Python` `DOI Tracker` | **「信使引擎」选题台账规划器**：双轴价值打分模型、跨报告 DOI 唯一性校验与历史选题台账 | [查看项目](https://github.com/rcrusoe88-bot/wechat-cmc-topic-planner) |
| **wechat-title-summary** | `Shell` `Prompt Engineering` | **「信使引擎」标题与摘要生成**：医药领域深度定制，≤40字标题 + ≤120字精炼摘要 + 4套风格模板 | [查看项目](https://github.com/rcrusoe88-bot/wechat-title-summary) |
| **wechat-cover-design** | `Python` `AI Visual` | **「信使引擎」视觉封面设计 Skill**：13 套专业视觉主题体系，精准输出英文文生图 Prompt 与中文阐述 | [查看项目](https://github.com/rcrusoe88-bot/wechat-cover-design) |
| **wechat-article-html** | `Python` `Inline CSS` | **「信使引擎」公众号排版转换器**：Word 一键转微信兼容内联 CSS HTML，针对 mRNA 深度内容定制主题 | [查看项目](https://github.com/rcrusoe88-bot/wechat-article-html) |

### 🤖 2. AI 专项技能与 Agent Harness 工具链 (AI & Skills)
| 项目 | 适用环境 / 类型 | 核心亮点 | 仓库链接 |
| :--- | :--- | :--- | :---: |
| **ppt-requirements-discovery** | `Claude Code` `Codex` | **PPT 需求前置勘测 Skill**：对话式需求澄清协议，制作幻灯片前自动对齐并产出标准化 Brief | [查看项目](https://github.com/rcrusoe88-bot/ppt-requirements-discovery) |
| **rea** | `Multi-Agent` `Python` *(Fork)* | **智能体全栈逆向工程**：利用 Agent 驱动从应用高层行为到底层原生二进制的端到端逆向分析 | [查看项目](https://github.com/rcrusoe88-bot/rea) |
| **taste-skill** | `Prompt Engineering` *(Fork)* | **Taste-Skill 审美引擎**：给 AI 注入工业级审美意识，杜绝同质化与代码 Slop 生成 | [查看项目](https://github.com/rcrusoe88-bot/taste-skill) |

### 🎨 3. 设计系统与现代全栈生态 (Design & Full-Stack)
| 项目 | 技术栈 | 核心亮点 | 仓库链接 |
| :--- | :--- | :--- | :---: |
| **yuxiaomo-design-system** | `React` `Tailwind` `TypeScript` | **企业手册设计系统**：71 个 React 组件(14族) + 23 条审美规则 + registry.json 防漂移契约层 | [查看项目](https://github.com/rcrusoe88-bot/yuxiaomo-design-system) |
| **personal-resume** | `HTML5` `Print CSS` `Markdown` | **个人简历排版引擎**：Markdown/Word 一键生成 A4 级 HTML 简历，8 套模板 × 12 种配色 | [查看项目](https://github.com/rcrusoe88-bot/personal-resume) |
| **yuxiaomo-ai-notes** | `Next.js` `GitHub Pages` | **余小莫的 AI 学习笔记**：个人技术博客，沉淀 Agentic 编程心得与系统架构思考 | [查看项目](https://github.com/rcrusoe88-bot/yuxiaomo-ai-notes) |
| **star-observatory** | `HTML5` `Interactive UI` | **余小莫的星空观察台**：个人前端视觉交互与创意数据展厅 | [查看项目](https://github.com/rcrusoe88-bot/star-observatory) |

### 🛡️ 4. 系统效率与平台探索 (System Utilities & Platforms)
| 项目 | 技术栈 | 核心亮点 | 仓库链接 |
| :--- | :--- | :--- | :---: |
| **qingdaofu** | `PowerShell` `Go / Wails` | **清道夫 (Windows Cleaner)**：数据驱动的安全瘦身工具，82 条数据驱动规则，风险项入回收站，免管理员提权 | [查看项目](https://github.com/rcrusoe88-bot/qingdaofu) |

---

## 🛠️ Tech Stack & Tooling

<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white" />
  <br/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <br/>
  <img src="https://img.shields.io/badge/Claude_Code-D97706?style=for-the-badge&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenAI_Codex-412991?style=for-the-badge&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white" />
</p>

---

## 📊 GitHub Analytics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=rcrusoe88-bot&show_icons=true&theme=radical&hide_border=true&count_private=true" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=rcrusoe88-bot&layout=compact&theme=radical&hide_border=true" width="48%" />
</div>

<br/>

<div align="center">
  <sub>Stay hungry, stay foolish. Coding with rigor & aesthetics.</sub>
</div>
