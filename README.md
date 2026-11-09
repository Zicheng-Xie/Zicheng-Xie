<div align="center">

<h1><img src="./assets/profile-name.svg" width="660" alt="Zicheng Xie" /></h1>

<p>
  <a href="https://github.com/DenverCoder1/readme-typing-svg"><img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&amp;size=22&amp;pause=1150&amp;color=B53980&amp;center=true&amp;vCenter=true&amp;width=580&amp;height=45&amp;lines=Building%20AI%20systems;LLM%20agents%20and%20retrieval;Applied%20machine%20learning;Open-source%20engineering" alt="AI systems, LLM agents and retrieval, applied machine learning, and open-source engineering" /></a>
</p>

<p>
  <a href="https://github.com/Zicheng-Xie"><img src="https://img.shields.io/badge/GitHub-24292F?style=flat-square&amp;logo=github&amp;logoColor=white" alt="GitHub" /></a>
  &nbsp;
  <a href="mailto:zichengxie2004@163.com"><img src="https://img.shields.io/badge/Email-A63860?style=flat-square&amp;logo=gmail&amp;logoColor=white" alt="Email" /></a>
  &nbsp;
  <a href="https://github.com/bytedance/deer-flow/pull/7150"><img src="https://img.shields.io/badge/DeerFlow-PR%20%237150-623BA0?style=flat-square&amp;logo=github&amp;logoColor=white" alt="DeerFlow merged pull request #7150" /></a>
</p>

[Open Source](#open-source) &nbsp;·&nbsp; [Selected Projects](#selected-projects) &nbsp;·&nbsp; [ML Competitions](#machine-learning-competitions) &nbsp;·&nbsp; [Skills](#skills)

</div>

---

## About

I'm a developer and researcher interested in the intersection of **AI systems, software engineering, and applied machine learning**. I enjoy building end-to-end prototypes, making model behavior measurable, and improving software through testing and iteration.

- **Education:** Incoming M.S. in Machine Learning & Data Science at **Northwestern University**; undergraduate degrees in Finance from **Shanghai University** and **University of Technology Sydney**.
- **Engineering interests:** LLM agents, retrieval-augmented generation, multimodal search, backend services, and AI infrastructure.
- **Approach:** Build useful systems, understand failure cases, and leave the codebase more reliable than I found it.

## Open Source

### [ByteDance / DeerFlow](https://github.com/bytedance/deer-flow) — Contributor

**[Merged PR #7150](https://github.com/bytedance/deer-flow/pull/7150)** · [View commits](https://github.com/bytedance/deer-flow/pull/7150/commits) · `Python` / `Agents` / `LangGraph` / `Testing`

DeerFlow is ByteDance's open-source long-horizon agent harness for complex, multi-step tasks. My contribution improves the reliability of document outlines consumed by agents.

- **Fixed Markdown heading corruption.** Uploaded headings with separate bold spans, such as `# **Revenue** and **Profit**`, could be incorrectly normalized into `Revenue** and **Profit`.
- **Made parsing boundary-aware.** Updated whole-title bold-marker cleanup to preserve independent bold spans, including mixed Chinese/English headings, across direct Markdown uploads and registered conversion companions.
- **Added regression coverage.** Introduced **19 outline test scenarios** covering nine heading patterns across upload sources, plus a regression for the actual `list_uploaded_files` tool output.
- **Verified the change.** Targeted test suites: **353 passed, 7 skipped**; Ruff lint and formatting checks passed. **4 files changed · +52 / −3 lines.**

> **Merged into `main` on October 20, 2026.** [Review the pull request →](https://github.com/bytedance/deer-flow/pull/7150)

## Selected Projects

| Project | Engineering focus |
| :--- | :--- |
| **[Occupational Fitness Platform](https://github.com/Zicheng-Xie/Occupational-Fitness-Platform)** | Traceable, local-LLM-assisted assessment with source-grounded hybrid RAG, deterministic rules, and FastAPI interfaces. |
| **[Agent-powered Financial Multimodal Report Generator](https://github.com/Zicheng-Xie/Agent-powered-Financial-Multimodal-Report-Generator)** | Automated financial research with data collection, iterative LLM-assisted analysis, charts, and Markdown/Word report generation. |
| **[E-commerce Multimodal Intelligent Content & Retrieval](https://github.com/Zicheng-Xie/E-commerce-Multimodal-Intelligent-Content-and-Retrieval-System)** | Multimodal product search and content-generation project spanning retrieval, fashion understanding, and system design. |

## Machine Learning Competitions

| Competition / Repository | Result | Methods |
| :--- | :--- | :--- |
| [Kaggle · Jane Street Real-Time Market Prediction](https://github.com/Zicheng-Xie/Zicheng_Xie-2025-Kaggle-Jane-Street-Real-Time-Market-Data-Forecasting-Competition-) | **Silver medal · 67 / 3,757** | Time-series features, GBDT, neural networks, ensembles |
| [Kaggle · Jigsaw Agile Community Rules](https://github.com/Zicheng-Xie/2025Kaggle-Jigsaw_Agile-Community-Rules-Classification) | **Bronze medal · 174 / 2,437** | LLM fine-tuning, contrastive embeddings, rank fusion |
| [Kaggle · Real Estate Demand Prediction](https://github.com/Zicheng-Xie/2025Kaggle-Real-Estate-Demand-Prediction) | **95 / 777** | Panel time series, CatBoost, feature engineering |

Also: **[ICBC Cup Financial Technology Innovation Competition](https://github.com/Zicheng-Xie/2023-ICBC_Cup-National-College-Financial-Technology-Creative-Design-Contest)** — Shanghai first prize.

<a id="skills"></a>

## 🛠️ Skills

| Property | Data |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white) ![Java](https://img.shields.io/badge/Java-A43E19?style=flat&logo=openjdk&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-45627E?style=flat) |
| **AI / Machine Learning** | ![PyTorch](https://img.shields.io/badge/PyTorch-B23C29?style=flat&logo=pytorch&logoColor=white) ![Transformers](https://img.shields.io/badge/Transformers-805B12?style=flat&logo=huggingface&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-2C687B?style=flat&logo=scikitlearn&logoColor=white) ![LightGBM](https://img.shields.io/badge/LightGBM-297348?style=flat) ![XGBoost](https://img.shields.io/badge/XGBoost-235789?style=flat) ![CatBoost](https://img.shields.io/badge/CatBoost-805B12?style=flat) |
| **Agents / Retrieval** | ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-405D82?style=flat&logo=langgraph&logoColor=white) ![RAG](https://img.shields.io/badge/RAG-6845A3?style=flat) ![FAISS](https://img.shields.io/badge/FAISS-265C9B?style=flat) ![Chroma](https://img.shields.io/badge/Chroma-85458C?style=flat) ![BM25](https://img.shields.io/badge/BM25-495E77?style=flat) ![Ollama](https://img.shields.io/badge/Ollama-24292F?style=flat&logo=ollama&logoColor=white) ![vLLM](https://img.shields.io/badge/vLLM-5848A8?style=flat) |
| **Backend / Engineering** | ![FastAPI](https://img.shields.io/badge/FastAPI-00796D?style=flat&logo=fastapi&logoColor=white) ![REST APIs](https://img.shields.io/badge/REST%20APIs-40647F?style=flat) ![Pytest](https://img.shields.io/badge/Pytest-226B91?style=flat&logo=pytest&logoColor=white) ![Ruff](https://img.shields.io/badge/Ruff-75541D?style=flat&logo=ruff&logoColor=white) ![Git](https://img.shields.io/badge/Git-A73928?style=flat&logo=git&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-1368A2?style=flat&logo=docker&logoColor=white) |
| **Data Processing** | ![Pandas](https://img.shields.io/badge/Pandas-382669?style=flat&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-356487?style=flat&logo=numpy&logoColor=white) |

<details>
<summary><strong>GitHub activity</strong></summary>

<p align="center">
  <img alt="GitHub activity summary" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Zicheng-Xie&theme=github_dark" />
</p>

</details>

---

<div align="center">

**Interested in collaborating on AI systems, agents, and applied ML?**

[Email](mailto:zichengxie2004@163.com) &nbsp;·&nbsp; [GitHub](https://github.com/Zicheng-Xie) &nbsp;·&nbsp; [DeerFlow PR #7150](https://github.com/bytedance/deer-flow/pull/7150)

<sub>Build thoughtfully. Test thoroughly. Keep learning.</sub>

</div>
