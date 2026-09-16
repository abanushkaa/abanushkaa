<h1 align="center">Hi 👋, I'm Anushka Baranwal!!</h1>

<p align="center">
  <img width="800em" src="https://readme-typing-svg.demolab.com?color=E22FE4&width=380&height=28&lines=Applied+AI+Engineer...;Building+Agentic+Systems...;LangGraph+%2B+ReAct+Agents...;RAG+%26+LLM+Pipelines...;Codeforces+Specialist...;Nice+To+Meet+You+....&center=true" />
</p>

<h3 align="center">Building agentic AI systems · Co-creator of Groundwork — an autonomous AI agent for open-source contributions · Targeting AI Engineer roles</h3>

- 🔭 Currently building **[Groundwork](https://github.com/abanushkaa/groundwork)** — an autonomous ReAct agent that drafts verified code patches for open-source issues
- 🌱 Currently deepening **LangChain, LLM fine-tuning, and RAG internals**
- 🏆 Codeforces Specialist (1400+) · 250+ problems solved across LeetCode & GeeksforGeeks
- 👨‍💻 More about me: [Portfolio](https://theanushkadev.netlify.app/)
- 💬 Ask me about **Java, Python, JavaScript, React, LangChain/LangGraph, RAG pipelines**
- 📫 Reach me at **abanushka678@gmail.com**
- 📄 [My Resume](https://drive.google.com/file/d/1e24W1Y935fQmi4l5FWRzhwihkhX3Msrp/view?usp=drive_link)

---

<h3 align="left">🚀 Flagship Project — Groundwork</h3>

**An autonomous ReAct agent that reads a GitHub repo and drafts a working, maintainer-safe patch for an open issue — with cited reasoning, not guesses.**

Instead of pattern-matching like most AI coding assistants, Groundwork parses the repo into a real Abstract Syntax Tree with `tree-sitter`, then runs a ReAct agentic loop that actively explores and cross-references the codebase before it writes a single line of the patch.

- 🧠 **Grounded Verification Loop** — every architectural claim is checked against the actual AST, not the LLM's assumption
- 🔍 **Agentic Contribution Drafter** — custom `search_codebase` / `read_file` tool loop that iterates until it understands the code, *then* drafts the `.patch`
- 🛡️ **Maintainer-safe by design** — forks, branches, and drafts the patch, but deliberately stops short of opening the PR itself, so nothing lands without a human in the loop
- ⚡ **Production backend** — SSE streaming for live agent thoughts, SHA-based SQLite caching, IP rate limiting, dynamic LLM key pooling
- 📊 **Benchmarked** — 100% precision on a 7-repo grounded-accuracy benchmark (starlette, click, requests, express, axios, chalk, kleur)
- 🔌 **Ships as an MCP server** — usable directly from Claude Desktop or Cursor

`Python` `FastAPI` `LangGraph` `Tree-sitter` `Next.js` `Server-Sent Events`

**[Live Demo](https://thegroundwork.vercel.app/) · [GitHub Repo](https://github.com/abanushkaa/groundwork)**

*Co-built with [Devyansh Upadhyay](https://github.com/devyansh7887).*

---

<h3 align="left">Connect with me:</h3>

<p align="left">
<a href="https://www.linkedin.com/in/abanushka678/" target="_blank">
<img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" height="30"/>
</a>

<a href="https://leetcode.com/u/AnushkaaB/" target="_blank">
<img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" height="30"/>
</a>

<a href="https://www.geeksforgeeks.org/user/abanushyveq/" target="_blank">
<img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/geeks-for-geeks.svg" height="30"/>
</a>
</p>

---

<h3 align="left">Certifications :</h3>

<p align="left" style="display:flex; flex-wrap:wrap; gap:20px; align-items:center;">

<a href="https://www.credly.com/badges/01e8412c-d8d0-4ec5-ab91-f8070a6571ae/public_url">
<img src="https://images.credly.com/size/80x80/images/0a6d331e-8abf-4272-a949-33f754569a76/CCNAENSA__1_.png"/>
</a>

<a href="https://www.credly.com/badges/d90bf55d-af03-454b-9435-89c6bec888d5/public_url">
<img src="https://images.credly.com/size/80x80/images/70d71df5-f3dc-4380-9b9d-f22513a70417/CCNAITN__1_.png"/>
</a>

<a href="https://www.credly.com/badges/5f4fc602-2f62-4853-829f-8ec625b5dbdb/public_url">
<img src="https://images.credly.com/size/80x80/images/f4ccdba9-dd65-4349-baad-8f05df116443/CCNASRWE__1_.png"/>
</a>

<a href="https://www.credly.com/badges/6dc6a3ad-3a92-4a35-b0b3-a0ee3d9fd28a/public_url">
<img src="https://images.credly.com/size/80x80/images/3f802526-7274-4230-91ab-f6d1a35340e6/image.png"/>
</a>

<a href="https://www.credly.com/badges/17fc0ed7-9575-4851-8339-a495186e9263/public_url">
<img src="https://images.credly.com/size/80x80/images/68c0b94d-f6ac-40b1-a0e0-921439eb092e/image.png"/>
</a>

<a href="https://www.credly.com/badges/c29a741a-9fde-4de7-9cd6-a872a78e30db/public_url">
<img src="https://images.credly.com/size/80x80/images/af8c6b4e-fc31-47c4-8dcb-eb7a2065dc5b/I2CS__1_.png"/>
</a>

</p>

---

<h3 align="left">Tech Stack:</h3>

**Languages**
<p align="left">
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>
</p>

**LLM Engineering & Agents**
<p align="left">
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Tree--sitter-000000?style=for-the-badge"/>
<img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge"/>
<img src="https://img.shields.io/badge/RAG%20Pipelines-6E56CF?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Fine--Tuning-3B3B98?style=for-the-badge"/>
</p>

**Deep Learning & Data**
<p align="left">
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge"/>
</p>

**Frontend & Backend**
<p align="left">
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
</p>

---

<h3 align="left">GitHub Activity :</h3>

<p>
<img height="150em" src="https://streak-stats.demolab.com/?user=abanushkaa" />
</p>

---

<h3 align="left">Competitive Programming Stats :</h3>

<p>

<a href="https://leetcode.com/u/AnushkaaB/">
<img height="150em" src="https://leetcard.jacoblin.cool/AnushkaaB?theme=dark&font=PT%20Serif&ext=contest"/>
</a>
<a href="https://www.geeksforgeeks.org/user/abanushyveq/">
<img height="150em" src="https://gfgstatscard.vercel.app/abanushyveq"/>
</a>

</p>
