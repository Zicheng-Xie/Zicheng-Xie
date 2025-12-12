<h1 align="center" style="color:#FF69B4;">Hey there! 👋 I'm Zicheng Xie</h1>
<h3 align="center" style="color:#1E90FF;">📈 Quant / ML Engineer | Kaggle Competitor | LLM + Time-Series Builder</h3>

<!-- 你可以换成自己的 header 图：建议 1280×320 -->
<!-- ![Header](https://your-image-link.png) -->

---

<p align="center">
  <img src="https://img.shields.io/badge/Kaggle-Silver%20Medal-FFD700" />
  <img src="https://img.shields.io/badge/Kaggle-Bronze%20Medal-CD7F32" />
  <img src="https://img.shields.io/badge/Quant-Time%20Series%20%26%20Factor%20Research-brightgreen" />
  <img src="https://img.shields.io/badge/LLM-RAG%20%7C%20LoRA%20%7C%20vLLM-ff69b4" />
  <img src="https://img.shields.io/badge/Stack-Python%20%7C%20C%2B%2B%20%7C%20ML-blue" />
</p>

---

## 🌟 About Me
- I build **robust forecasting & classification systems** for noisy, non-stationary real-world data (finance / text / panel time series).
- Strong focus on **feature engineering**, **model ensembling**, **LLM finetuning**, **production-friendly pipelines**.
- Motto: **Measure. Iterate. Ship.** 🚀

---

## 📌 Pinned Highlights (Top 4)

### 🥈 2025 Kaggle — Jane Street Real-Time Market Data Forecasting (Silver, 67/3757)
- **Goal:** precise prediction for `responder_6`, optimized for **Weighted Zero-Mean R²**
- **Pipeline:** lag features → GBDT/NN multi-model training → dynamic ensemble → output clipping & metric-aligned scaling  
- **Core Tech:** XGBoost / LightGBM / CatBoost, PyTorch, lag features, real-time inference, ensemble weighting

### 🥉 2025 Kaggle — Jigsaw Agile Community Rules Classification (Bronze, 174/2437)
- **Two-track approach:** (1) LLM instruction-tuned classifier (Llama 3.2 3B Instruct + LoRA) (2) sentence embedding similarity with contrastive learning  
- **Fusion:** rank-normalized weighted blending across models  
- **Core Tech:** LoRA, 4bit nf4 quant, Deepspeed, vLLM, sentence-transformers, TripletLoss, centroid distance scoring

### 🏆 ICBC Cup (Shanghai 1st Prize) — Digital Collectibles Sandbox (Blockchain + Data Structures, C++)
- Built **blockified resource & object management** with multi-level indexing
- Designed **hash-chained integrity verification** + JSON parsing + service loop integration
- **Core Tech:** C++, data structures, chained hashing, JSON, std::filesystem, service interface integration

### 🏠 2025 Kaggle — Real Estate Demand Prediction (Top 13%, 95/777)
- Built **(sector_id, time)** monthly panel (5y × 96 sectors), large-scale feature joins  
- Crafted **seasonality + holiday + lag/rolling** features  
- **Modeling:** 2-stage CatBoost (classifier gate + regressor) + time series CV + bounds control

---

## 🧰 Tech Stack & All Skills
### Core Languages
- **Python** (Pandas/NumPy), **C++** (STL, filesystem), SQL (SQLite usage)

### Machine Learning / Modeling
- **CatBoost**, **XGBoost**, **LightGBM**, **scikit-learn**
- **Time Series**: lag features, rolling stats, seasonal encoding (sin/cos), TimeSeriesSplit CV
- **Ensembling**: weighted blending, rank normalization, voting regressors, gating models

### Deep Learning / LLM
- **PyTorch**
- **LoRA finetuning**, **4-bit quant (nf4, bitsandbytes)**, **Deepspeed ZeRO**
- **vLLM inference**, logits constraint (multiple-choice), prompt engineering (template systems)

### NLP / Embeddings / RAG
- **sentence-transformers**, **BGE (base/large, bge-m3)**, **TripletLoss**
- **RAG retrieval**, embedding pipelines (local Ollama + HTTP/JSON)
- Rule-conditioned similarity, centroid-based scoring

### Data Engineering / Tooling
- **openpyxl** (large Excel chunk processing), CSV/JSON pipelines
- **SQLite vector storage (float32 BLOB)** / CSV embedding store
- Robust preprocessing: URL normalization, missing handling, dedupe keys, clipping/bounding

### Quant / Research
- Factor IC (Spearman), IR, macro regime tests (t-test), long-short backtesting, turnover & cost modeling

---

## 🧪 More Projects
- 🤖 **Agent-powered Financial Multimodal Report Generator** (LLM + RAG + templates + visualization pipeline)
- 📰 **WSJ News Sentiment + Human-in-the-loop Forecasting** (token-aware chunking, scoring dictionary, structured outputs)
- 📊 **Dynamic Quality Factor Research & Backtesting** (IC-driven rolling weights, macro sensitivity)

---

## 📫 Get in Touch
- Email: **axelsensheyjzhen@163.com**

---

---
