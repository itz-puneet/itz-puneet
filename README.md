<h1 align="center">Hi, I'm Puneet Deshwani 👋</h1>

<h3 align="center">Software engineer · backend &amp; retrieval systems · open source</h3>

<p align="center">
  <b>Ex-Intern @ Accenture · AEH, DevOps team (Summer 2026)</b> &nbsp;•&nbsp; <b>M.Tech CSE @ IIITM Gwalior</b>
</p>

<p align="center">
  <a href="https://linkedin.com/in/puneet-deshwani"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:puneet29.pro@gmail.com"><img src="https://img.shields.io/badge/Email-Reach%20me-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://leetcode.com/u/user0241XW/"><img src="https://img.shields.io/badge/LeetCode-1831-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
</p>

---

### 👨‍💻 About me

I build **backend and retrieval systems**, and I like the parts that have to hold up under a check: retrieval quality, data integrity, tests that fail when the bug comes back. This summer I interned at **Accenture** on a DevOps team, and I'm now back to my **M.Tech in CSE at ABV-IIITM Gwalior (CGPA 9.47/10)**, writing a thesis on label noise in software defect prediction.

I care about the hard parts: retrieval quality, grounding, evaluation, and shipping. I like taking a model from "works in a notebook" to a live app people can use.

### 🧑‍💻 Recently — Summer 2026 @ Accenture

- Built a **Python RAG assistant** with 3 other interns for an internal DevOps team, over its runbooks: past errors and their fixes, environment start-up steps and data-fetch queries (PDF + Excel).
- **Hybrid retrieval** with ChromaDB vectors and BM25 keywords, with chunking and ranking tuned on the team's test set.
- When the documents held no fix, the bot gave the dev team's contact instead of guessing one.

### 🔭 What I'm working on now

- **M.Tech thesis** — [quantifying SZZ label noise in just-in-time defect prediction](https://github.com/itz-puneet/thesis-later): six labelling variants scored against a human-annotated reference across 21 Apache projects (27,319 commits).
- **Open-source contributions**, merged so far:
  - [LadybugDB #1280](https://github.com/LadybugDB/ladybug/pull/1280) — the packed filtered-count plan now falls back to the regular aggregate instead of crashing when a predicate input is computed.
  - [LadybugDB](https://github.com/LadybugDB/ladybug/pull/943) (C++ graph database) — gated a count fast path in the query optimizer that could run on storage formats it does not support, with optimizer tests.
  - [Mnemosyne](https://github.com/mnemosyne-oss/mnemosyne/pull/930) (Python, SQLite) — made every memory delete path cascade its support rows, with regression tests.
  - [Sentry JavaScript SDK](https://github.com/getsentry/sentry-javascript/pull/24031) — tests asserting prompt and response content stays off spans when GenAI recording is disabled.
  - [stdlib-js](https://github.com/stdlib-js/stdlib/pull/14945) — moved the `ln` tests to ULP-based assertions.

---

### 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**GenAI & Machine Learning**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-Hybrid%20Retrieval-6E4AFF?style=for-the-badge)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge)
![BERT](https://img.shields.io/badge/BERT-NLP-11557C?style=for-the-badge)

**Web & APIs**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React%20Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

**Data & Vector Stores**

![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B6B?style=for-the-badge)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

### 🚀 Featured Projects

**🔎 [ABV-IIITM RAG Chatbot](https://github.com/itz-puneet/iiitm-rag-chatbot)** — `Python · FAISS · BM25 · ONNX · Gemini · Streamlit` · [live demo](https://iiitm-chatbot.streamlit.app/)
A public assistant that answers questions on institute policies, fees and curricula, citing the source PDF for every answer. Indexes 180 institutional PDFs; hybrid search fuses FAISS vectors and BM25 keywords with Reciprocal Rank Fusion, with an optional cross-encoder reranker. Embedding and reranking run on ONNX, so it needs no GPU or PyTorch.

**🎮 [E-Fantasy — Esports Fantasy App](https://github.com/itz-puneet/e-fantasy-app)** — `React Native (Expo) · TypeScript · Supabase (PostgreSQL)`
A cross-platform app where users draft fantasy esports rosters and join contests with virtual tokens (no real-money gambling). Game and wallet rules are enforced in the database: Row-Level Security on all 12 tables, PL/pgSQL functions for every wallet and contest write, and contest entry as a single row-locked transaction.

**📊 [M.Tech Thesis — Label Noise in Just-In-Time Defect Prediction](https://github.com/itz-puneet/thesis-later)** — `Python · scikit-learn · GitHub Actions`
Measures how mislabelled bug data distorts commit-level defect prediction across 21 Apache projects, with the experiment pipeline running in CI behind a gate that rejects stale labels.

**📝 [Take-Notes](https://github.com/itz-puneet/Take-Notes)** — `React · Tailwind CSS`
A small notes app for quick capture, built with React and Tailwind.

---

### 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=itz-puneet&show_icons=true&count_private=true&hide_border=true&theme=tokyonight" alt="Puneet's GitHub stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=itz-puneet&layout=compact&hide_border=true&theme=tokyonight" alt="Top languages"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=itz-puneet&hide_border=true&theme=tokyonight" alt="GitHub streak"/>
</p>

---

### 🏆 Achievements

- 🧠 **LeetCode contest rating 1831** (top 7.16%) · **235+ DSA problems** solved in C++
- 🌍 **Global Rank 3054** — TCS CodeVita Season 12
- 🏅 **Top 200** — Amazon ML Challenge 2026, in a team of four
- 🎯 **GATE CS 2025** — AIR 4646
- 🥈 **2nd place** in two consecutive university hackathons
- 🎓 **Executive Secretary, CS Students Council** — ran 3+ technical forums and events for 400+ participants (2022–2025)

---

### 📫 Let's connect

<p align="center">
  <a href="https://linkedin.com/in/puneet-deshwani">LinkedIn</a> &nbsp;•&nbsp;
  <a href="mailto:puneet29.pro@gmail.com">puneet29.pro@gmail.com</a> &nbsp;•&nbsp;
  <a href="https://leetcode.com/u/user0241XW/">LeetCode</a> &nbsp;•&nbsp;
  <a href="https://www.codechef.com/users/afler">CodeChef</a>
</p>

<p align="center"><i>Open to SDE, backend and GenAI engineering roles — reach out any time.</i></p>
