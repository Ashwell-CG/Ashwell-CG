<div align="center">

# Ashwell Cherian Giji

**Computer Science Undergraduate | Backend & AI Engineering**

B.Tech CSE (AI & ML) · Lovely Professional University · Class of 2028

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ashwell%20Cherian%20Giji-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ashwell-cherian-giji-413bb1312/)

</div>

---

### About

I build backend systems and machine learning applications, and I care about being clear on what a model can and cannot do. My recent work covers a FastAPI service that serves a tuned regression model in production, a research platform that analyses 23 years of gridded rainfall data, and a file system written from scratch in C.

I am working towards Software Development Engineering, Backend Engineering, AI Engineering and Forward Deployed Engineering roles.

---

### Featured Projects

#### [MonsoonIQ](https://github.com/Ashwell-CG/MoonsoonIQ) — Monsoon onset analysis and regime-aware sowing advisory

Finds recurring monsoon onset patterns across Maharashtra and turns them into a cautious, rule-based sowing advisory. It runs as a historical replay, not a forecast.

- Processed 23 years (2001–2023) of IMD 0.25° gridded daily rainfall across 419 land cells
- Sustained-onset detection using a 5-day accumulation threshold and a 20-day verification window: 9,606 confirmed onset events
- Found four onset regimes with K-Means clustering on 9 onset-dynamics features
- Advisory state machine with regime-specific rules, a dry-spell reset, and no "safe to sow" claims
- Streamlit + Plotly dashboard with an interactive 419-cell map; 182 automated tests
- Research paper in preparation

`Python` `xarray` `NetCDF` `pandas` `scikit-learn` `Streamlit` `Plotly` `pytest`

#### [AirfareIndex](https://github.com/Ashwell-CG/AirfareIndex) — Supervised ML airfare estimation · [Live demo](https://airfare-index-puce.vercel.app)

Estimates Indian domestic airfares from historical listed fares and serves them through a validated API and a React interface.

- Final model: a log-space blend of a tuned Random Forest (0.75) and a route-median lookup (0.25)
- Train/test splits by journey-date blocks and held-out flights, so evaluation is not on seen rows
- Historical held-out results on unseen flights, over 10 seeds: MAE ₹3,154 ± 185, R² 0.918, MdAPE 11.4%
- Real-world accuracy has not been measured yet. The validation pipeline is built, but verified fare data is still being collected
- FastAPI backend with strict input validation, in Docker on Render; frontend on Vercel
- 102 backend tests, 60 frontend tests, and 40/40 production browser checks

`Python` `FastAPI` `Pydantic` `scikit-learn` `XGBoost` `React` `Vite` `Docker`

#### [PromoPulse](https://github.com/Ashwell-CG/Promopulse) — Campaign and coupon management backend

A web application for businesses to run marketing campaigns and issue digital coupons.

- User registration and login with bcrypt password hashing and auth middleware on protected routes
- Campaign CRUD, random coupon code generation, and validation (valid / expired / already used)
- Usage dashboard and analytics charts

`Node.js` `Express` `MongoDB` `Mongoose` `EJS` `Chart.js`

#### [File System Recovery & Optimization Simulator](https://github.com/Ashwell-CG/File-System-Recovery-and-Optimization-Tool) — Systems programming in C

A virtual file system built from scratch in C11 on a 10 MB disk image.

- Inode-based metadata, a bitmap block allocator, and a hierarchical directory tree
- Write-ahead journal, metadata checkpoints and full-disk backups for crash recovery
- 64-slot LRU write-back cache, defragmentation, and read/write and cache-hit metrics

`C` `Make`

<details>
<summary><b>Other projects</b></summary>
<br>

- [Fake News Detection](https://github.com/Ashwell-CG/Fake-News-Detection-Using-NLP) — TF-IDF features and a comparison of supervised classifiers
- [Weatherly](https://github.com/Ashwell-CG/Weatherly) — Flask app with OpenWeatherMap data and a Gemini-powered weather chat
- [Flightly](https://github.com/Ashwell-CG/Flightly) — Python flight search using the Amadeus API
- [LeetCode Solutions](https://github.com/Ashwell-CG/LeetCode-Solutions) — DSA practice in Java and C++

</details>

---

### Technical Skills

| Area | Tools |
|---|---|
| **Languages** | Python · Java · C · C++ · JavaScript |
| **Backend** | FastAPI · Pydantic · Flask · Node.js · Express · REST APIs |
| **AI / ML** | scikit-learn · XGBoost · pandas · NumPy · xarray · SHAP · NLP (TF-IDF) |
| **Databases** | MongoDB (Mongoose) |
| **Cloud & DevOps** | Docker · Render · Vercel |
| **Frontend & Visualisation** | React · Vite · Tailwind CSS · Streamlit · Plotly |
| **Tools** | Git · GitHub · pytest · Vitest · LaTeX |

---

### Currently Learning

- **Spring Boot** and Java backend development
- **Data Structures & Algorithms** in Java and C++

Next on my list: **AWS** and cloud computing.

---

### Connect

[LinkedIn](https://www.linkedin.com/in/ashwell-cherian-giji-413bb1312/)
