<div align="center">
<svg viewBox="0 0 440 420" width="100%" style="max-width:440px">
    <defs>
    <linearGradient id="glow" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0" stop-color="#7C3AED" stop-opacity="0.5"/>
      <stop offset="0.5" stop-color="#00E5FF" stop-opacity="0.35"/>
      <stop offset="1" stop-color="#FF6B6B" stop-opacity="0.45"/>
      <animate attributeName="x1" values="0;1;0" dur="10s" repeatCount="indefinite"/>
    </linearGradient>
    <radialGradient id="bgpad" cx="0.5" cy="0.5" r="0.5">
      <stop offset="0" stop-color="#16163d" stop-opacity="0.9"/>
      <stop offset="1" stop-color="#0a0a1f" stop-opacity="0"/>
    </radialGradient>
    <linearGradient id="shine" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0" stop-color="#ffffff" stop-opacity="0.5"/>
      <stop offset="1" stop-color="#ffffff" stop-opacity="0"/>
    </linearGradient>
  </defs>

  <ellipse cx="220" cy="400" rx="150" ry="16" fill="#000" opacity="0.35">
    <animate attributeName="rx" values="150;118;150" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.35;0.22;0.35" dur="4s" repeatCount="indefinite"/>
  </ellipse>

  <g>
    <animateTransform attributeName="transform" type="translate" values="0 0;0 -14;0 0" dur="4s" repeatCount="indefinite"/>

    <ellipse cx="220" cy="200" rx="170" ry="150" fill="url(#bgpad)"/>
    <path d="M220.0,150.0 282.0,184.0 220.0,218.0 158.0,184.0Z" fill="url(#glow)"/>

    <g>
      <animateTransform attributeName="transform" type="rotate" values="0 220 210;0 220 210;360 220 210" dur="14s" repeatCount="indefinite" keyTimes="0;0.5;1"/>
      <path d="M158.0,184.0 220.0,218.0 282.0,184.0 220.0,150.0Z" fill="none" stroke="#00E5FF" stroke-width="1.2" opacity="0.25"/>
    </g>

    <g>
      <path d="M220.0,150.0 240.7,161.3 220.0,172.7 199.3,161.3Z" fill="#FFD500" stroke="#17173a" stroke-width="1.6" stroke-linejoin="round"/>
      <path d="M240.7,161.3 261.3,172.7 240.7,184.0 220.0,172.7Z" fill="#FFD500" stroke="#17173a" stroke-width="1.6" stroke-linejoin="round"/>
      <path d="M261.3,172.7 282.0,184.0 261.3,195.3 240.7,184.0Z" fill="#FFD500" stroke="#17173a" stroke-width="1.6" stroke-linejoin="round"/>
      <path d="M199.3,161.3 220.0,172.7 199.3,184.0 178.7,172.7Z" fill="#FFD500" stroke="#17173a" stroke-width="1.6" stroke-linejoin="round"/>
      <path d="M220.0,172.7 240.7,184.0 220.0,195.3 199.3,184.0Z" fill="#FFD500" stroke="#17173a" stroke-width="1.6" stroke-linejoin="round"/>
      <path d="M240.7,184.0 261.3,195.3 240.7,206.7 220.0,195.3Z" fill="#FFD500" stroke="#17173a" stroke-width="1.6" stroke-linejoin="round"/>
      <path d="M178.7,172.7 199.3,184.0 178.7,195.3 158.0,184.0Z" fill="#FFD500" stroke="#17173a" stroke-width="1.6" stroke-linejoin="round"/>
      <path d="M199.3,184.0 220.0,195.3 199.3,206.7 178.7,195.3Z" fill="#FFD500" stroke="#17173a" stroke-width="1.6" stroke-linejoin="round"/>
      <path d="M220.0,195.3 240.7,206.7 220.0,218.0 199.3,206.7Z" fill="#FFD500" stroke="#17173a" stroke-width="1.6" stroke-linejoin="round"/>
      <path d="M158.0,184.0 178.7,195.3 178.7,260.0 158.0,248.7Z" fill="#C41E3A" stroke="#17173a" stroke-width="1.6" stroke-linejoin="round"/>
      <path d="M178.7,195.3 199.3,206.7 199.3,271.3 178.7,260.0Z" fill="#C41E3A" stroke="#17173a" stroke-width="1.6" stroke-linejoin="round"/>
      <path d="M199.3,206.7 220.0,218.0 220.0,282.7 199.3,271.3Z" fill="#C41E3A" stroke="#17173a" stroke-width="1.6" stroke-linejoin="round"/>
      <path d="M158.0,248.7 178.7,260.0 178.7,324.7 158.0,313.3Z" fill="#C41E3A" stroke="#17173a" stroke-width="1.6" stroke-linejoin="round"/>
      <path d="M178.7,260.0 199.3,271.3 199.3,336.0 178.7,324.7Z" fill="#C41E3A" stroke="#17173a" stroke-width="1.6" stroke-linejoin="round"/>
      <path d="M199.3,271.3 220.0,282.7 220.0,347.3 199.3,336.0Z" fill="#C41E3A" stroke="#17173a" stroke-width="1.6" stroke-linejoin="round"/>
      <path d="M158.0,313.3 178.7,324.7 178.7,389.3 158.0,378.0Z" fill="#C41E3A" stroke="#17173a" stroke-width="1.6" stroke-linejoin="round"/>
      <path d="M178.7,324.7 199.3,336.0 199.3,400.7 178.7,389.3Z" fill="#C41E3A" stroke="#17173a" stroke-width="1.6" stroke-linejoin="round"/>
      <path d="M199.3,336.0 220.0,347.3 220.0,412.0 199.3,400.7Z" fill="#C41E3A" stroke="#17173a" stroke-width="1.6" stroke-linejoin="round"/>
      <path d="M220.0,218.0 240.7,206.7 240.7,271.3 220.0,282.7Z" fill="#0051BA" stroke="#17173a" stroke-width="1.6" stroke-linejoin="round"/>
      <path d="M240.7,206.7 261.3,195.3 261.3,260.0 240.7,271.3Z" fill="#0051BA" stroke="#17173a" stroke-width="1.6" stroke-linejoin="round"/>
      <path d="M261.3,195.3 282.0,184.0 282.0,248.7 261.3,260.0Z" fill="#0051BA" stroke="#17173a" stroke-width="1.6" stroke-linejoin="round"/>
      <path d="M220.0,282.7 240.7,271.3 240.7,336.0 220.0,347.3Z" fill="#0051BA" stroke="#17173a" stroke-width="1.6" stroke-linejoin="round"/>
      <path d="M240.7,271.3 261.3,260.0 261.3,324.7 240.7,336.0Z" fill="#0051BA" stroke="#17173a" stroke-width="1.6" stroke-linejoin="round"/>
      <path d="M261.3,260.0 282.0,248.7 282.0,313.3 261.3,324.7Z" fill="#0051BA" stroke="#17173a" stroke-width="1.6" stroke-linejoin="round"/>
      <path d="M220.0,347.3 240.7,336.0 240.7,400.7 220.0,412.0Z" fill="#0051BA" stroke="#17173a" stroke-width="1.6" stroke-linejoin="round"/>
      <path d="M240.7,336.0 261.3,324.7 261.3,389.3 240.7,400.7Z" fill="#0051BA" stroke="#17173a" stroke-width="1.6" stroke-linejoin="round"/>
      <path d="M261.3,324.7 282.0,313.3 282.0,378.0 261.3,389.3Z" fill="#0051BA" stroke="#17173a" stroke-width="1.6" stroke-linejoin="round"/>
    </g>

    <path d="M158.0,184.0 220.0,150.0 282.0,184.0Z" fill="url(#shine)" opacity="0.22">
      <animate attributeName="opacity" values="0.22;0.05;0.22" dur="4s" repeatCount="indefinite"/>
    </path>

    <g transform="translate(220.0,150.0)">
        <circle r="9" fill="none" stroke="#ffffff" stroke-width="2" opacity="0.9"><animate attributeName="r" values="4;34" dur="3.5s" repeatCount="indefinite"/><animate attributeName="opacity" values="0.8;0" dur="3.5s" repeatCount="indefinite"/></circle></g>
    <g transform="translate(220.0,412.0)">
        <circle r="9" fill="none" stroke="#ffffff" stroke-width="2" opacity="0.9"><animate attributeName="r" values="4;34" dur="3.5s" repeatCount="indefinite"/><animate attributeName="opacity" values="0.8;0" dur="3.5s" repeatCount="indefinite"/></circle></g>
    <g transform="translate(282.0,313.3)">
        <circle r="9" fill="none" stroke="#ffffff" stroke-width="2" opacity="0.9"><animate attributeName="r" values="4;34" dur="3.5s" repeatCount="indefinite"/><animate attributeName="opacity" values="0.8;0" dur="3.5s" repeatCount="indefinite"/></circle></g>
  </g>

  <g font-family="Segoe UI, system-ui, sans-serif">
    <circle cx="60" cy="70" r="3" fill="#00E5FF"><animate attributeName="cy" values="70;40;70" dur="5s" repeatCount="indefinite"/><animate attributeName="opacity" values="1;0.2;1" dur="5s" repeatCount="indefinite"/></circle>
    <circle cx="380" cy="90" r="2.5" fill="#FF6B6B"><animate attributeName="cy" values="90;130;90" dur="6s" repeatCount="indefinite"/><animate attributeName="opacity" values="0.2;1;0.2" dur="6s" repeatCount="indefinite"/></circle>
    <circle cx="395" cy="330" r="3" fill="#A78BFA"><animate attributeName="cy" values="330;300;330" dur="7s" repeatCount="indefinite"/><animate attributeName="opacity" values="1;0.3;1" dur="7s" repeatCount="indefinite"/></circle>
    <circle cx="45" cy="300" r="2" fill="#00E5FF"><animate attributeName="cy" values="300;330;300" dur="4.5s" repeatCount="indefinite"/></circle>
    <circle cx="330" cy="40" r="2" fill="#ffffff"><animate attributeName="opacity" values="0;1;0" dur="3s" repeatCount="indefinite"/></circle>
    <circle cx="100" cy="50" r="2" fill="#ffffff"><animate attributeName="opacity" values="0;1;0" dur="4s" repeatCount="indefinite"/></circle>
  </g>
</svg>

<p>
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=3500&pause=500&color=58A6FF&center=true&vCenter=true&width=600&lines=Hi+%F0%9F%91%8B+I'm+Lakhan+Singh;Generative+AI+%26+Full-Stack+Engineer;Agentic+AI+%26+RAG+Systems;Building+solutions+that+scale" alt="Typing intro" />
</p>

<p>
  <a href="https://github.com/codeby-lakhan"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
  <a href="https://www.linkedin.com/in/codeby-lakhan"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:lakhansingh9138@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>
</div>

---

I'm a **Generative AI & Full-Stack Engineer** who builds real products with agentic AI. I design multi-agent LangGraph pipelines, retrieval systems (CRAG, Self-RAG, FAISS) and full-stack Node.js apps — turning raw problems into reliable, production-ready software.

- 🔭 Currently building **agentic AI pipelines** with LangGraph
- 📄 Shipped **4 production-grade projects** — including 2 hackathon entries (Google Vibe2Code 2026, Bharatiya Antariksh 2026/ISRO)
- 🧠 Applying **PyTorch** to hands-on neural network projects
- 💪 Strong **DSA** foundation — 300+ problems solved (Java)
- 🎓 B.Tech CSE (AI & DS) @ Poornima University · GPA 9.18/10
- 🤝 Open to opportunities & collaborations

## 🛠️ Tech Stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" alt="C"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/SQL%2FMySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL/MySQL"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
</p>

### 🤖 AI & Agentic

<p>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangGraph"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain"/>
  <img src="https://img.shields.io/badge/Groq%20API-F55036?style=for-the-badge&logo=groq&logoColor=white" alt="Groq API"/>
  <img src="https://img.shields.io/badge/Gemini%20Vision-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Gemini Vision"/>
  <img src="https://img.shields.io/badge/Multi%2DAgent%20Pipelines-6F42C1?style=for-the-badge&logo=codeforces&logoColor=white" alt="Multi-Agent Pipelines"/>
  <img src="https://img.shields.io/badge/Prompt%20Engineering-00C4CC?style=for-the-badge&logo=openai&logoColor=white" alt="Prompt Engineering"/>
  <img src="https://img.shields.io/badge/CRAG-009688?style=for-the-badge&logo=proteinpedia&logoColor=white" alt="CRAG"/>
  <img src="https://img.shields.io/badge/Self%2DRAG-2C6FBB?style=for-the-badge&logo=proteinpedia&logoColor=white" alt="Self-RAG"/>
</p>

### 📊 ML & Data

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch"/>
  <img src="https://img.shields.io/badge/FAISS-3F4F75?style=for-the-badge&logo=databricks&logoColor=white" alt="FAISS"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib"/>
  <img src="https://img.shields.io/badge/Seaborn-22627C?style=for-the-badge&logo=plotly&logoColor=white" alt="Seaborn"/>
  <img src="https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white" alt="Plotly"/>
  <img src="https://img.shields.io/badge/EDA-5C6BC0?style=for-the-badge&logo=databricks&logoColor=white" alt="EDA"/>
</p>

### 🚀 Full Stack & DevOps

<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/>
  <img src="https://img.shields.io/badge/Passport.js-34E27A?style=for-the-badge&logo=auth0&logoColor=white" alt="Passport.js"/>
  <img src="https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white" alt="Cloudinary"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/REST%20APIs-009688?style=for-the-badge&logo=api&logoColor=white" alt="REST APIs"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit"/>
  <img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white" alt="Render"/>
</p>

## 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=codeby-lakhan&show_icons=true&include_all_commits=true&theme=tokyonight&hide_border=true" alt="GitHub stats" width="46%"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=codeby-lakhan&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" width="46%"/>
  <br/>
  <img src="https://streak-stats.demolab.com/?user=codeby-lakhan&theme=tokyonight&hide_border=true" alt="GitHub Streak" width="60%"/>
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=codeby-lakhan&theme=onestar&row=2&no-frame=false&column=5&margin-w=10&margin-h=10" alt="GitHub Trophies"/>
</p>

## 📌 Featured Projects

| Project | Description |
|---|---|
| [**AlignAgent**](https://github.com/codeby-lakhan/AlignAgent) | Agentic RAG skill gap analyzer — 8-node LangGraph pipeline on Groq/Llama-3.3-70B, multi-tenant FAISS, CRAG + Self-RAG with neo-brutalist Streamlit UI |
| [**CommunityHero**](https://github.com/codeby-lakhan/CommunityHero) | Civic issue reporting — 5-node LangGraph + Gemini 1.5 Pro Vision, 300m geofenced dedup, 24h auto-escalation SLA · Google Vibe2Code 2026 |
| [**WanderLust**](https://github.com/codeby-lakhan/WanderLust) | Full-stack accommodation marketplace — Node.js, Express, MongoDB, Passport.js, Cloudinary, Nominatim geocoding & booking engine |
| [**college-rag-chatbot**](https://github.com/codeby-lakhan/college-rag-chatbot) | Context-aware document intelligence — LangChain, FAISS, Gemini 2.5 Flash |
| [**ByteTrace**](https://github.com/codeby-lakhan/ByteTrace) | Real-time byte-level debugging & tracing tool |

## 🤝 Let's Connect

<p>
  <a href="https://github.com/codeby-lakhan"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
  <a href="https://www.linkedin.com/in/codeby-lakhan"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:lakhansingh9138@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=codeby-lakhan&label=Profile%20Views&color=58A6FF&style=plastic" alt="Profile views"/>
</p>