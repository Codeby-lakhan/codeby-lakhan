# Lakhan Singh

**B.Tech CSE (AI & DS) · Generative AI & Full-Stack Engineer**

📍 Jaipur, India &nbsp;·&nbsp; 📧 [lakhansingh9138@gmail.com](mailto:lakhansingh9138@gmail.com) &nbsp;·&nbsp; 💼 [LinkedIn](https://www.linkedin.com/in/codeby-lakhan) &nbsp;·&nbsp; 🐙 [GitHub](https://github.com/codeby-lakhan)

---

## 👨‍💻 About Me

Computer Science undergraduate specialising in **agentic AI systems** and **full-stack development**. I've shipped four production-grade projects spanning LangGraph multi-agent pipelines, multimodal Gemini Vision, advanced RAG architectures (CRAG, Self-RAG), FAISS vector search, and a full-stack Node.js marketplace — including two hackathon entries (Google Vibe2Code 2026; Bharatiya Antariksh 2026, ISRO).

Currently applying PyTorch to build hands-on neural network projects. Strong foundation in DSA with **300+ problems solved** and hands-on internship experience.

---

## 🛠️ Technical Skills

**Languages**

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=java&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C](https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![HTML/CSS](https://img.shields.io/badge/-HTML%2FCSS-E34F26?style=flat-square&logo=html5&logoColor=white)

**AI & Agentic**

LangGraph · LangChain (LCEL) · Groq API (Llama 3.x) · Gemini 1.5 Pro Vision · Corrective RAG (CRAG) · Self-RAG · Multi-Agent Pipelines · Prompt Engineering

**ML & Data**

PyTorch · Supervised Learning · EDA · Feature Engineering · Pandas · NumPy · Matplotlib · Seaborn · Plotly

**Vector Search**

FAISS (multi-tenant) · Parent-Child Chunking · FastEmbed (BAAI/bge-small-en-v1.5, 384-dim) · gemini-embedding-2-preview

**Full Stack & DevOps**

Node.js · Express.js · MongoDB · MySQL · Passport.js · Cloudinary · Docker · REST APIs · Git · Streamlit · Render

---

## 🚀 Featured Projects

### AlignAgent — Agentic RAG Skill Gap Analyzer
*Python, LangGraph, Groq API, FAISS, FastEmbed, Streamlit*

- Built an **8-node autonomous LangGraph pipeline** (Groq/Llama-3.3-70B) for low-latency agentic inference, analysing resumes against job descriptions in real time; deployed on Streamlit Cloud.
- Engineered a **multi-tenant FAISS vector store** with parent-child chunking (1200/300 chars) and 384-dim FastEmbed (BAAI/bge-small-en-v1.5) embeddings for high-precision retrieval.
- Implemented **CRAG document grading** (batched N→1 LLM calls per workspace), DuckDuckGo web-search fallback, and a **Self-RAG reflection loop**; tenacity exponential backoff handles Groq free-tier rate limits without crashing mid-pipeline.
- Designed a neo-brutalist Streamlit UI (hard-shadow cards, zero border-radius, #FFE000 accent, hover-lift) with live agent streaming, Plotly charts (gauge, donut, skill map, Gantt), persistent progress tracker, and HTML/JSON export.

### CommunityHero — Civic Issue Reporting Platform
*LangGraph, Gemini 1.5 Pro Vision, SQLite, Folium, fpdf2, Streamlit*

- Built a **5-node LangGraph pipeline** (validate → deduplicate → enrich → draft → save) with conditional routing — invalid photos rejected at Node 1; duplicate reports within a 300m geofenced radius redirected to the existing issue. *Google Vibe2Code Hackathon 2026, solo.*
- Used **Gemini 1.5 Pro Vision** to extract issue category, severity, affected infrastructure, and immediate risk from a single citizen photo; same session drafts a formal JMC complaint letter and its Hindi translation via fpdf2.
- **Auto-escalation logic in SQLite** — critical issues unresolved past a 24h SLA trigger re-notification to the next authority level; priority feed ranked by severity×(1+upvotes)×days open.
- 6-page Streamlit app: report flow, multi-turn Hindi/English chatbot with live DB context, Folium map with severity-coloured markers across 30 Jaipur wards, Plotly ward heatmap, and password-gated Authority dashboard with CSV export.

### Wanderlust — Full-Stack Accommodation Marketplace
*Node.js, Express.js, MongoDB, EJS, Passport.js, Cloudinary*

- Full-stack property rental platform with RESTful routing, server-side pagination (9 listings/page), and regex search across title/location/country; category filter spanning 10 property types.
- **Passport.js session auth** with MongoDB-backed session persistence (connect-mongo) and role-based route guards (isOwner, isBookingOwner); flash-message feedback across all user flows.
- **Cloudinary** image storage via multer-storage-cloudinary; Nominatim reverse geocoding auto-stores GeoJSON coordinates on every create/update for interactive map rendering.
- Booking system with check-in/out date range, guest count, dynamic total price, and **Joi schema validation**; cascade review deletion on listing removal via Mongoose post-hook.

---

## 💼 Experience

**Full Stack Developer Intern — Cognifyz Technologies** · *Jun 2025 – Aug 2025 · Remote*
- Developed RESTful API endpoints in Express.js with JWT-based authentication and Mongoose schema validation; wired endpoints to React frontend components to deliver features end-to-end.
- Implemented protected route middleware, request input sanitisation, and centralised error handling across the API layer; designed MongoDB schemas with compound indexes to optimise query performance.

---

## 🎓 Education & Achievements

**Poornima University, Jaipur** — B.Tech in Computer Science & Engineering (AI & DS) · 2024–2028 · **GPA: 9.18/10** (Sem 1–4)

- 🧠 DSA: **300+ LeetCode problems** (Java) — trees, graphs, dynamic programming
- 📜 Certifications: Full Stack MERN (Apna College); Soft Skills (NPTEL)
- 🏆 Hackathons: Google Vibe2Code 2026 (CommunityHero); Bharatiya Antariksh 2026 (PlanetHunters, ISRO); Next Wave (state finalist); SIH (college round)

---

## 📫 Connect With Me

- 💼 [LinkedIn](https://www.linkedin.com/in/codeby-lakhan)
- 📧 [lakhansingh9138@gmail.com](mailto:lakhansingh9138@gmail.com)
- 🐙 [GitHub](https://github.com/codeby-lakhan)

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=codeby-lakhan&show_icons=true&theme=dark" alt="GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=codeby-lakhan&theme=dark" alt="GitHub Streak" />
</p>
