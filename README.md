<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF6B6B,50:7C3AED,100:00E5FF&height=160&section=header&fontColor=ffffff&fontSize=40&desc=ColorOS%2017%20Glass%20Edition&descAlignY=85&descSize=16" />
</div>

<!-- GLASS HERO CARD (inlined SVG — animations work on GitHub) -->
<div align="center">

<svg viewBox="0 0 980 330" width="100%" style="max-width:980px;border-radius:24px">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0" stop-color="#0a0a1f"/>
      <stop offset="0.5" stop-color="#101033"/>
      <stop offset="1" stop-color="#0a0a1f"/>
      <animate attributeName="x1" values="0;0.8;0" dur="12s" repeatCount="indefinite"/>
    </linearGradient>
    <linearGradient id="aurora1" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0" stop-color="#00E5FF" stop-opacity="0.55"/>
      <stop offset="1" stop-color="#7C3AED" stop-opacity="0.55"/>
    </linearGradient>
    <linearGradient id="aurora2" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0" stop-color="#FF6B6B" stop-opacity="0.45"/>
      <stop offset="1" stop-color="#00E5FF" stop-opacity="0.45"/>
    </linearGradient>
    <linearGradient id="borderGrad" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#00E5FF"/>
      <stop offset="0.5" stop-color="#7C3AED"/>
      <stop offset="1" stop-color="#FF6B6B"/>
      <animateTransform attributeName="gradientTransform" type="translate" values="0 0;800 0;0 0" dur="8s" repeatCount="indefinite"/>
    </linearGradient>
    <linearGradient id="titleGrad" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#00E5FF"/>
      <stop offset="0.5" stop-color="#A78BFA"/>
      <stop offset="1" stop-color="#FF6B6B"/>
      <animate attributeName="x2" values="0.2;1;0.2" dur="6s" repeatCount="indefinite"/>
    </linearGradient>
    <filter id="blur40"><feGaussianBlur stdDeviation="40"/></filter>
    <filter id="blur18"><feGaussianBlur stdDeviation="18"/></filter>
  </defs>

  <rect x="0" y="0" width="980" height="330" rx="24" fill="url(#bg)"/>

  <ellipse cx="180" cy="80" rx="240" ry="180" fill="url(#aurora1)" filter="url(#blur40)" opacity="0.7">
    <animateTransform attributeName="transform" type="translate" values="0 0;70 30;-40 -20;0 0" dur="18s" repeatCount="indefinite"/>
  </ellipse>
  <ellipse cx="820" cy="260" rx="260" ry="190" fill="url(#aurora2)" filter="url(#blur40)" opacity="0.6">
    <animateTransform attributeName="transform" type="translate" values="0 0;-60 20;40 -30;0 0" dur="15s" repeatCount="indefinite"/>
  </ellipse>
  <ellipse cx="500" cy="40" rx="160" ry="90" fill="#7C3AED" filter="url(#blur18)" opacity="0.35">
    <animateTransform attributeName="transform" type="translate" values="0 0;80 0;0 0" dur="10s" repeatCount="indefinite"/>
  </ellipse>

  <g opacity="0.9">
    <circle cx="120" cy="50" r="2.5" fill="#00E5FF"><animate attributeName="opacity" values="0.2;1;0.2" dur="3s" repeatCount="indefinite"/></circle>
    <circle cx="880" cy="40" r="2" fill="#FF6B6B"><animate attributeName="opacity" values="1;0.2;1" dur="4s" repeatCount="indefinite"/></circle>
    <circle cx="750" cy="300" r="2" fill="#A78BFA"><animate attributeName="opacity" values="0.3;1;0.3" dur="3.6s" repeatCount="indefinite"/></circle>
    <circle cx="300" cy="290" r="1.8" fill="#00E5FF"><animate attributeName="opacity" values="1;0.2;1" dur="2.8s" repeatCount="indefinite"/></circle>
  </g>

  <rect x="16" y="16" width="948" height="298" rx="20" fill="#ffffff" opacity="0.05"/>
  <rect x="16" y="16" width="948" height="298" rx="20" fill="none" stroke="url(#borderGrad)" stroke-width="1.5" opacity="0.8"/>
  <rect x="16" y="16" width="948" height="298" rx="20" fill="url(#borderGrad)" opacity="0" stroke="url(#borderGrad)" stroke-width="3" stroke-dasharray="900 1400">
    <animate attributeName="stroke-dashoffset" values="2250;0" dur="7s" repeatCount="indefinite"/>
  </rect>

  <text x="490" y="120" text-anchor="middle" font-family="Segoe UI, system-ui, sans-serif" font-size="56" font-weight="800" fill="url(#titleGrad)">Lakhan Singh</text>

  <text x="490" y="168" text-anchor="middle" font-family="Segoe UI, system-ui, sans-serif" font-size="20" fill="#C4B5FD" opacity="0.95">B.Tech CSE (AI &amp; DS) · Generative AI &amp; Full-Stack Engineer</text>
  <text x="490" y="204" text-anchor="middle" font-family="Segoe UI, system-ui, sans-serif" font-size="15" fill="#94A3B8">📍 Jaipur, India</text>
  <text x="490" y="228" text-anchor="middle" font-family="Segoe UI, system-ui, sans-serif" font-size="15" fill="#94A3B8" opacity="0">Agentic AI · RAG · LLM Systems</text>

  <g font-family="Segoe UI, system-ui, sans-serif" font-size="12" fill="#E0E7FF">
    <rect x="150" y="262" width="110" height="30" rx="15" fill="#ffffff" opacity="0.08" stroke="#7C3AED" stroke-width="1">
      <animate attributeName="opacity" values="0.08;0.16;0.08" dur="4s" repeatCount="indefinite"/>
    </rect>
    <text x="205" y="281" text-anchor="middle">✨ LangGraph</text>

    <rect x="270" y="262" width="110" height="30" rx="15" fill="#ffffff" opacity="0.08" stroke="#00E5FF" stroke-width="1">
      <animate attributeName="opacity" values="0.08;0.16;0.08" dur="4.6s" repeatCount="indefinite"/>
    </rect>
    <text x="325" y="281" text-anchor="middle">🤖 FAISS + RAG</text>

    <rect x="390" y="262" width="110" height="30" rx="15" fill="#ffffff" opacity="0.08" stroke="#FF6B6B" stroke-width="1">
      <animate attributeName="opacity" values="0.08;0.16;0.08" dur="5.2s" repeatCount="indefinite"/>
    </rect>
    <text x="445" y="281" text-anchor="middle">🔥 PyTorch</text>

    <rect x="510" y="262" width="120" height="30" rx="15" fill="#ffffff" opacity="0.08" stroke="#A78BFA" stroke-width="1">
      <animate attributeName="opacity" values="0.08;0.16;0.08" dur="4.2s" repeatCount="indefinite"/>
    </rect>
    <text x="570" y="281" text-anchor="middle">⚡ Node.js</text>

    <rect x="640" y="262" width="120" height="30" rx="15" fill="#ffffff" opacity="0.08" stroke="#00E5FF" stroke-width="1">
      <animate attributeName="opacity" values="0.08;0.16;0.08" dur="5.8s" repeatCount="indefinite"/>
    </rect>
    <text x="700" y="281" text-anchor="middle">👾 Gemini Vision</text>
  </g>
</svg>

</div>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=00E5FF&center=true&vCenter=true&multiline=true&width=720&height=60&lines=Agentic+AI+%26+RAG+Engineer;Generative+AI+%26+Full-Stack+Developer;300%2B+DSA+Problems+Solved;Building%3A+LangGraph+Pipelines" alt="Typing SVG" />
  <br/>
  <img src="https://komarev.com/ghpvc/?username=codeby-lakhan&color=7C3AED&style=flat-square&label=PROFILE+VIEWS" alt="Profile views" />
</p>

---

## <img src="https://img.shields.io/badge/-ABOUT%20ME-2dd4bf?style=for-the-badge" /> 

<div align="center">
<table style="border-radius:18px;border:1px solid rgba(255,255,255,0.12);background:linear-gradient(135deg,#ffffff08,#ffffff03);box-shadow:0 8px 32px #0008">
<tr><td align="left" style="padding:20px 30px">
Computer Science undergraduate specialising in <b>agentic AI systems</b> and <b>full-stack development</b>. I've shipped <b>4 production-grade projects</b> — LangGraph multi-agent pipelines, multimodal Gemini Vision, advanced RAG (CRAG, Self-RAG), FAISS vector search, and a full-stack Node.js marketplace — including 2 hackathon entries (<i>Google Vibe2Code 2026; Bharatiya Antariksh 2026, ISRO</i>).

Currently building hands-on neural networks with <b>PyTorch</b>, with a strong DSA foundation (<b>300+ problems</b>) and internship experience.
</td></tr>
</table>
</div>

---

## <img src="https://img.shields.io/badge/-TECH%20STACK-7c3aed?style=for-the-badge" />

<div align="center">
  <img src="https://skillicons.dev/icons?i=python,java,js,c,react,nodejs,express,mongodb,mysql,html,css,docker,git,streamlit" alt="Core stack" />
</div>

<!-- ANIMATED SKILL BARS -->
<div align="center">
<svg viewBox="0 0 640 430" width="100%" style="max-width:640px">
  <defs>
    <linearGradient id="bar1" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#00E5FF"/><stop offset="1" stop-color="#06B6D4"/>
    </linearGradient>
    <linearGradient id="bar2" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#7C3AED"/><stop offset="1" stop-color="#A78BFA"/>
    </linearGradient>
    <linearGradient id="bar3" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#FF6B6B"/><stop offset="1" stop-color="#F8B4C4"/>
    </linearGradient>
  </defs>
  <g font-family="Segoe UI, system-ui, sans-serif" font-size="15" fill="#E2E8F0">
    <!-- rows: label, track, animated fill, % -->
    <text x="20" y="52">Python &amp; Data Science</text>
    <rect x="250" y="42" width="340" height="14" rx="7" fill="#ffffff" opacity="0.08"/>
    <rect x="250" y="42" width="0" height="14" rx="7" fill="url(#bar1)"><animate attributeName="width" from="0" to="300" dur="1.6s" begin="0.1s" fill="freeze"/></rect>
    <text x="600" y="52">88%</text>

    <text x="20" y="112">Java · DSA</text>
    <rect x="250" y="102" width="340" height="14" rx="7" fill="#ffffff" opacity="0.08"/>
    <rect x="250" y="102" width="0" height="14" rx="7" fill="url(#bar2)"><animate attributeName="width" from="0" to="290" dur="1.6s" begin="0.3s" fill="freeze"/></rect>
    <text x="600" y="112">85%</text>

    <text x="20" y="172">LangGraph · LangChain</text>
    <rect x="250" y="162" width="340" height="14" rx="7" fill="#ffffff" opacity="0.08"/>
    <rect x="250" y="162" width="0" height="14" rx="7" fill="url(#bar1)"><animate attributeName="width" from="0" to="310" dur="1.6s" begin="0.5s" fill="freeze"/></rect>
    <text x="600" y="172">92%</text>

    <text x="20" y="232">RAG · FAISS · Vector Search</text>
    <rect x="250" y="222" width="340" height="14" rx="7" fill="#ffffff" opacity="0.08"/>
    <rect x="250" y="222" width="0" height="14" rx="7" fill="url(#bar3)"><animate attributeName="width" from="0" to="300" dur="1.6s" begin="0.7s" fill="freeze"/></rect>
    <text x="600" y="232">88%</text>

    <text x="20" y="292">PyTorch · ML</text>
    <rect x="250" y="282" width="340" height="14" rx="7" fill="#ffffff" opacity="0.08"/>
    <rect x="250" y="282" width="0" height="14" rx="7" fill="url(#bar2)"><animate attributeName="width" from="0" to="255" dur="1.6s" begin="0.9s" fill="freeze"/></rect>
    <text x="600" y="292">75%</text>

    <text x="20" y="352">Node.js · Express · MongoDB</text>
    <rect x="250" y="342" width="340" height="14" rx="7" fill="#ffffff" opacity="0.08"/>
    <rect x="250" y="342" width="0" height="14" rx="7" fill="url(#bar3)"><animate attributeName="width" from="0" to="280" dur="1.6s" begin="1.1s" fill="freeze"/></rect>
    <text x="600" y="352">82%</text>

    <text x="20" y="412">Git · Docker · REST APIs</text>
    <rect x="250" y="402" width="340" height="14" rx="7" fill="#ffffff" opacity="0.08"/>
    <rect x="250" y="402" width="0" height="14" rx="7" fill="url(#bar1)"><animate attributeName="width" from="0" to="272" dur="1.6s" begin="1.3s" fill="freeze"/></rect>
    <text x="600" y="412">80%</text>
  </g>
</svg>
</div>

<details>
  <summary style="text-align:center;color:#A78BFA"><b>🧬 Full skill breakdown</b></summary>

**AI & Agentic:** LangGraph · LangChain (LCEL) · Groq API (Llama 3.x) · Gemini 1.5 Pro Vision · CRAG · Self-RAG · Multi-Agent Pipelines · Prompt Engineering

**ML & Data:** PyTorch · Supervised Learning · EDA · Feature Engineering · Pandas · NumPy · Matplotlib · Seaborn · Plotly

**Vector Search:** FAISS (multi-tenant) · Parent-Child Chunking · FastEmbed (BAAI/bge-small-en-v1.5 · 384-dim) · gemini-embedding-2-preview

**Full Stack & DevOps:** Node.js · Express.js · MongoDB · MySQL · Passport.js · Cloudinary · Docker · REST APIs · Streamlit · Render

</details>

---

## <img src="https://img.shields.io/badge/-FEATURED%20PROJECTS-00e5ff?style=for-the-badge" />

<div align="center">
  <a href="https://github.com/codeby-lakhan/AlignAgent">
  <table style="border-radius:16px;border:1px solid #7C3AED66;background:linear-gradient(160deg,#1a1a40,#0d0d26)">
  <tr><td width="420" style="padding:18px 22px">
    <b style="font-size:16px">🤖 AlignAgent</b>
    <div style="font-size:12px;color:#94A3B8">Agentic RAG Skill Gap Analyzer</div>
    <br/>
    <div style="font-size:12.5px;color:#CBD5E1">
      8-node LangGraph pipeline (Groq/Llama-3.3-70B) · multi-tenant FAISS · CRAG grading + Self-RAG reflection loop · neo-brutalist Streamlit UI
    </div>
    <br/>
    <span style="font-size:11px;color:#00E5FF">Python · LangGraph · FAISS · Streamlit</span>
  </td></tr>
  </table>
  </a>

  <a href="https://github.com/codeby-lakhan/CommunityHero">
  <table style="border-radius:16px;border:1px solid #00E5FF66;background:linear-gradient(160deg,#1a1a40,#0d0d26)">
  <tr><td width="420" style="padding:18px 22px">
    <b style="font-size:16px">🏙️ CommunityHero</b>
    <div style="font-size:12px;color:#94A3B8">Civic Issue Reporting Platform</div>
    <br/>
    <div style="font-size:12.5px;color:#CBD5E1">
      5-node LangGraph pipeline · Gemini 1.5 Pro Vision photo analysis · 24h auto-escalation SLA · 30-ward Folium heatmap · Google Vibe2Code 2026
    </div>
    <br/>
    <span style="font-size:11px;color:#7C3AED">LangGraph · Gemini Vision · SQLite · Streamlit</span>
  </td></tr>
  </table>
  </a>

  <a href="https://github.com/codeby-lakhan/Wanderlust">
  <table style="border-radius:16px;border:1px solid #FF6B6B66;background:linear-gradient(160deg,#1a1a40,#0d0d26)">
  <tr><td width="420" style="padding:18px 22px">
    <b style="font-size:16px">🏖️ Wanderlust</b>
    <div style="font-size:12px;color:#94A3B8">Full-Stack Accommodation Marketplace</div>
    <br/>
    <div style="font-size:12.5px;color:#CBD5E1">
      RESTful routing · Passport.js session auth + role guards · Cloudinary media · Nominatim geocoding · Joi validations · booking engine
    </div>
    <br/>
    <span style="font-size:11px;color:#FF6B6B">Node.js · Express · MongoDB · EJS</span>
  </td></tr>
  </table>
  </a>
</div>

---

## <img src="https://img.shields.io/badge/-GITHUB%20STATS-a78bfa?style=for-the-badge" />

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=codeby-lakhan&show_icons=true&count_private=true&bg_color=0d0d26&title_color=00E5FF&text_color=E0E7FF&icon_color=7C3AED&border_color=7C3AED66" alt="GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=codeby-lakhan&background=0d0d26&border=7C3AED66&stroke=00E5FF&ring=FF6B6B&fire=FF6B6B&currStreakNum=E0E7FF&sideNums=A78BFA&currStreakLabel=00E5FF&sideLabels=94A3B8" alt="GitHub Streak" />
  <br/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=codeby-lakhan&layout=compact&bg_color=0d0d26&title_color=00E5FF&text_color=E0E7FF&border_color=7C3AED66" alt="Top Languages" width="400"/>
</div>

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=codeby-lakhan&theme=algolia&no-frame=true&row=2&column=4&margin-w=10&margin-h=10" alt="Trophies" />
</div>

---

## <img src="https://img.shields.io/badge/-EXPERIENCE-06b6d4?style=for-the-badge" />

<div align="center">
<table style="border-radius:18px;border:1px solid rgba(255,255,255,0.12);background:linear-gradient(135deg,#ffffff08,#ffffff03);box-shadow:0 8px 32px #0008">
<tr><td align="left" style="padding:20px 30px">
  <b>💻 Full Stack Developer Intern — Cognifyz Technologies</b> &nbsp;·&nbsp; <i style="color:#94A3B8">Jun 2025 – Aug 2025 · Remote</i>
  <ul style="color:#CBD5E1;margin-top:8px">
    <li>Built RESTful API endpoints in Express.js with JWT auth + Mongoose validation; wired end-to-end into React frontends.</li>
    <li>Implemented protected route middleware, input sanitisation, centralised error handling, and MongoDB compound indexes for query performance.</li>
  </ul>
</td></tr>
</table>
</div>

---

## <img src="https://img.shields.io/badge/-EDUCATION%20%26%20ACHIEVEMENTS-2dd4bf?style=for-the-badge" />

<div align="center">
<table style="border-radius:18px;border:1px solid rgba(255,255,255,0.12);background:linear-gradient(135deg,#ffffff08,#ffffff03);box-shadow:0 8px 32px #0008">
<tr><td align="left" style="padding:20px 30px">
  <b>🎓 Poornima University, Jaipur</b> — B.Tech CSE (AI &amp; DS) · 2024–2028 · <b style="color:#00E5FF">GPA 9.18/10</b>
  <ul style="color:#CBD5E1;margin-top:8px">
    <li>🧠 DSA: 300+ LeetCode problems (Java) — trees, graphs, dynamic programming</li>
    <li>📜 Certifications: Full Stack MERN (Apna College) · Soft Skills (NPTEL)</li>
    <li>🏆 Hackathons: Google Vibe2Code 2026 · Bharatiya Antariksh 2026 (ISRO) · Next Wave (state finalist) · SIH</li>
  </ul>
</td></tr>
</table>
</div>

---

## <img src="https://img.shields.io/badge/-CONNECT%20WITH%20ME-7c3aed?style=for-the-badge" />

<div align="center">
  <a href="https://www.linkedin.com/in/codeby-lakhan">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:lakhansingh9138@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://github.com/codeby-lakhan">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://hackernoon.com/">
    <img src="https://img.shields.io/badge/Portfolio-00E5FF?style=for-the-badge&logo=react&logoColor=000" alt="Portfolio"/>
  </a>
</div>

<br/>
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00E5FF,50:7C3AED,100:FF6B6B&height=140&section=footer" />
  <br/>
  <sub style="color:#64748B">Crafted with <b style="color:#FF6B6B">❤</b> · Glassmorphism + SMIL animations</sub>
</div>