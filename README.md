<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1f1a,50:047857,100:064e3b&height=200&section=header" />

<div align="center">

<img src="https://readme-typing-svg.demolab.com/?lines=Aarav+Khanal;AI+%2F+ML+Engineer;Trained+LLMs+From+Scratch+on+an+8+GB+Laptop;Multi-Agent+Systems+%C2%B7+Research+%C2%B7+Full-Stack&font=Fira+Code&center=true&width=750&height=50&color=34d399&vCenter=true&size=22&pause=2000" />

<br/>

<img src="https://img.shields.io/badge/BMS_College_of_Engineering-064e3b?style=for-the-badge&logo=googlescholar&logoColor=white" />
<img src="https://img.shields.io/badge/Bengaluru,_India-047857?style=for-the-badge&logo=googlemaps&logoColor=white" />

<br/><br/>

<a href="https://www.linkedin.com/in/aarav-khanal-40795832a/">
  <img src="https://img.shields.io/badge/LinkedIn-047857?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="mailto:khanalaarav2063@gmail.com">
  <img src="https://img.shields.io/badge/Email-10b981?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
<a href="https://github.com/Aaravkhanal">
  <img src="https://img.shields.io/badge/GitHub-064e3b?style=for-the-badge&logo=github&logoColor=white" />
</a>

<br/><br/>

<img src="https://img.shields.io/github/followers/Aaravkhanal?label=FOLLOWERS&style=for-the-badge&color=10b981&labelColor=064e3b" />
<img src="https://img.shields.io/github/stars/Aaravkhanal?label=STARS&style=for-the-badge&color=34d399&labelColor=064e3b" />

<br/><br/>

<a href="#-about">About</a> •
<a href="#-featured-projects">Projects</a> •
<a href="#-research">Research</a> •
<a href="#-tech-stack">Tech Stack</a> •
<a href="#-connect">Connect</a>

</div>

<br/>

<a id="-about"></a>
## ⟡ About

I'm an AI/ML and full-stack engineer who likes understanding systems all the way down. I've trained language models from random initialisation on a MacBook Air, built the tokenizer, trainer, evaluation suite, API and web platform around them, and run controlled experiments to find out what actually works, including the results that don't flatter the model.

Alongside that, I build multi-agent and multi-model products (code review, design-to-code, adversarial debate) and a self-hosted Git forge. I care about evaluation you can trust, honest limits, and tests that prove claims.

```yaml
Currently:
  Building:      GITOWN (independent Git forge), LLM training + evaluation tooling
  Researching:   Memorization vs. compositional creativity in small language models
  Sharpening:    Deep learning, distributed systems, system design
  Open to:       Internships, collaborations, research-driven engineering roles
```

<div align="center">

| 🧠 Model sizes trained from scratch | 🧪 Controlled training runs | ✅ Tests in flagship repo | 📦 Featured projects |
|:---:|:---:|:---:|:---:|
| 4 (5M → 48.1M params) | 50+ | 564 | 6 |

</div>

<br/>

<a id="-featured-projects"></a>
## ⟡ Featured Projects

<div align="center">

<a href="https://github.com/Aaravkhanal/MY-LLM">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Aaravkhanal&repo=MY-LLM&theme=dark&bg_color=0b0f0e&title_color=34d399&icon_color=34d399&text_color=d1fae5&hide_border=true" />
</a>
<a href="https://github.com/Aaravkhanal/canary-memorization-study">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Aaravkhanal&repo=canary-memorization-study&theme=dark&bg_color=0b0f0e&title_color=34d399&icon_color=34d399&text_color=d1fae5&hide_border=true" />
</a>
<a href="https://github.com/Aaravkhanal/GITOWN">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Aaravkhanal&repo=GITOWN&theme=dark&bg_color=0b0f0e&title_color=34d399&icon_color=34d399&text_color=d1fae5&hide_border=true" />
</a>
<a href="https://github.com/Aaravkhanal/ProjectMind-AI">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Aaravkhanal&repo=ProjectMind-AI&theme=dark&bg_color=0b0f0e&title_color=34d399&icon_color=34d399&text_color=d1fae5&hide_border=true" />
</a>
<a href="https://github.com/Aaravkhanal/Frameflow-ai">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Aaravkhanal&repo=Frameflow-ai&theme=dark&bg_color=0b0f0e&title_color=34d399&icon_color=34d399&text_color=d1fae5&hide_border=true" />
</a>
<a href="https://github.com/Aaravkhanal/Jubidate_ai">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Aaravkhanal&repo=Jubidate_ai&theme=dark&bg_color=0b0f0e&title_color=34d399&icon_color=34d399&text_color=d1fae5&hide_border=true" />
</a>

</div>

<br/>

<details open>
<summary><b>🔬 MY-LLM — A Language Model and Its Whole Stack, Built From Scratch</b></summary>
<br/>

A small decoder-only language model and everything around it, trained from random initialisation on a MacBook Air M3 with 8 GB of memory: byte-level BPE tokenizer, data pipeline, trainer, evaluation, SFT/LoRA fine-tuning, terminal chat, an OpenAI-compatible HTTP API, and a web platform. No pretrained weights and no external model calls.

| | |
|---|---|
| **Model** | Llama-style transformer (RoPE, RMSNorm, SwiGLU, grouped-query attention, KV cache), 4 sizes trained: 5M, 14M, 25.7M, 48.1M parameters |
| **Training** | Bit-for-bit reproducible resume; the 48.1M model completed pretraining (15,000 steps, 33.5 h) and instruction fine-tuning on a laptop |
| **Evaluation** | Every score reported next to chance level and confidence intervals; final test set committed before any model was scored; 7 scientific problems in its own pipeline found, fixed and tested; negative results reported as such |
| **Serving** | OpenAI-compatible API (checked with the official `openai` SDK), accounts with self-service keys, per-key limits, exact batched decoding for concurrent users |
| **Quality** | 564 tests, CI on every push, fresh-clone CI replay script |
| **Repository** | [github.com/Aaravkhanal/MY-LLM](https://github.com/Aaravkhanal/MY-LLM) |

</details>

<details open>
<summary><b>🧪 Canary Memorization Study — Memorization vs. Compositional Creativity</b></summary>
<br/>

Does a small language model trade off memorizing recurring narrative elements against recombining them into novel stories, and does that shift with architecture? This study plants controlled "canaries" at set insertion frequencies and measures exposure following the Carlini et al. methodology, adapted to narrative generation. Currently exploratory: the human-labelled novelty endpoint and a contamination-free confirmatory study are still in progress, and the repo says so plainly.

| | |
|---|---|
| **Design** | Fresh pretraining run per (architecture, frequency) cell: 4 architectures × multiple frequencies at 14M, plus a matched 24-cell 48M scale-transfer grid |
| **Scale** | 53 retained experiment summaries, 106 checkpoints validated, 16,000 generations checked for full-corpus overlap |
| **Rigor** | Pre-registration checks, frozen analysis plans, blinded annotation sheets, claim audit with allowed/prohibited wording, runtime failure audit |
| **Quality** | 115 tests, fresh-clone smoke test, artifact manifest with SHA-256 inventory |
| **Repository** | [github.com/Aaravkhanal/canary-memorization-study](https://github.com/Aaravkhanal/canary-memorization-study) |

</details>

<details open>
<summary><b>🏗️ GITOWN — An Independent Home for Your Code</b></summary>
<br/>

A self-hosted Git forge built on a Next.js interface, a Go API, PostgreSQL metadata, and native Git storage. You can create an account and repository, push with standard Git, open a pull request, review the diff, merge, and pull the result back. A development alpha with an honest feature boundary and public-beta release gates documented in the repo.

| | |
|---|---|
| **Stack** | Next.js · Go · PostgreSQL · native bare Git repositories |
| **Git** | Smart HTTP clone/fetch/push, SSH gateway, LFS, merge/squash/rebase, reviews, merge queue |
| **Platform** | Issues and boards, notifications, packages and releases, wiki, organizations, imports and exports, a custom `gitown` CLI |
| **Security** | Argon2id passwords, TOTP MFA, scoped revocable tokens, rate limits, CSP; independent review documented as still required |
| **Operations** | Backup/restore drills, deployment preflight, load smoke tests, Playwright browser tests, CI |
| **Repository** | [github.com/Aaravkhanal/GITOWN](https://github.com/Aaravkhanal/GITOWN) |

</details>

<details>
<summary><b>🧠 ProjectMind AI — BYOK Multi-Agent AI Engineering Platform</b></summary>
<br/>

Runs Architect, Security, and Quality agents in parallel over every code review, then synthesizes one verdict. A persistent **Repository Brain** learns from each review, and a router picks the right model per task and downgrades when the budget is tight. Ships as a published VS Code extension.

| | |
|---|---|
| **Stack** | FastAPI · LangGraph · SQLite · 15+ LLM providers via LiteLLM |
| **Scale** | 93 REST endpoints across 21 feature domains |
| **Security** | Fernet-encrypted BYOK key storage; keys never leave your machine |
| **Repository** | [github.com/Aaravkhanal/ProjectMind-AI](https://github.com/Aaravkhanal/ProjectMind-AI) · [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=aaravkhanal.projectmind) |

</details>

<details>
<summary><b>⚡ FrameFlow AI — Design-to-Code Consensus Engine</b></summary>
<br/>

Turns screenshots, Figma files, URLs, or screen recordings into frontend code by running OpenAI, Claude, and Gemini simultaneously and reconciling their outputs, with live multi-viewport previews and ZIP export.

| | |
|---|---|
| **Stack** | React · Vite · FastAPI · Supabase (PostgreSQL) · OpenAI · Claude · Gemini |
| **Output** | React, Vue, HTML + Tailwind, Bootstrap, Ionic from a single input |
| **Quality** | 228 automated backend tests; Supabase Auth with JWT, bcrypt, Row-Level Security |
| **Repository** | [github.com/Aaravkhanal/Frameflow-ai](https://github.com/Aaravkhanal/Frameflow-ai) |

</details>

<details>
<summary><b>🌌 Jubidate — Strategic Intelligence OS</b></summary>
<br/>

Assigns live model instances the roles of Pro Advocate, Con Advocate, and Judge, streams their debate over WebSockets, and produces a verdict with evidence-quality warnings and unresolved points. Deployed and publicly demoable.

| | |
|---|---|
| **Stack** | Next.js 15 · React 19 · FastAPI · WebSockets · LiteLLM · NVIDIA NIM · Gemini/Groq |
| **Repository** | [github.com/Aaravkhanal/Jubidate_ai](https://github.com/Aaravkhanal/Jubidate_ai) |
| **Live Demo** | [jubidate-ai.vercel.app](https://jubidate-ai.vercel.app/) · [API docs](https://jubidateai-production.up.railway.app/docs) |

</details>

<br/>

<a id="-research"></a>
## ⟡ Research

**Memorization vs. compositional creativity in small language models** is an ongoing, exploratory study with controlled canary insertion, exact full-corpus overlap diagnostics, blinded human annotation in preparation, and a pre-registered confirmatory follow-up. Findings are reported with their limits: single-seed arms, confounded canaries, and no trade-off claim until the human-labelled endpoint is complete.

Code, protocols and claim audit: [canary-memorization-study](https://github.com/Aaravkhanal/canary-memorization-study)

<br/>

<a id="-tech-stack"></a>
## ⟡ Tech Stack

**Languages**

<img src="https://skillicons.dev/icons?i=python,go,js,ts,cpp" />

**Frontend**

<img src="https://skillicons.dev/icons?i=react,nextjs,html,css,tailwind" />

**Backend & Databases**

<img src="https://skillicons.dev/icons?i=nodejs,fastapi,flask,postgres,mongodb,firebase" />

**AI / ML & Tooling**

<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,opencv,docker,git,linux,vscode" />

**Models & Frameworks**

<img src="https://img.shields.io/badge/OpenAI-1f2937?style=for-the-badge&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/Anthropic_Claude-1f2937?style=for-the-badge&logo=anthropic&logoColor=white" />
<img src="https://img.shields.io/badge/Google_Gemini-1f2937?style=for-the-badge&logo=googlegemini&logoColor=white" />
<img src="https://img.shields.io/badge/Groq-1f2937?style=for-the-badge&logo=lightning&logoColor=white" />
<img src="https://img.shields.io/badge/LangChain-1f2937?style=for-the-badge&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/RAG-047857?style=for-the-badge&logo=databricks&logoColor=white" />

<br/>

## ⟡ AI / ML Expertise

| Domain | Proficiency | Details |
|---|---|---|
| Language Models from Scratch | Advanced | Byte-level BPE, Llama-style transformers (RoPE, GQA, SwiGLU, KV cache), reproducible training, SFT and LoRA, int8 export, batched serving |
| ML Evaluation & Research | Advanced | Chance-level baselines, confidence intervals, paired comparisons, pre-registration, memorization exposure metrics, blinded annotation design |
| Multi-Agent & Multi-Model Systems | Advanced | Debate/vote/reflect pipelines, LangGraph orchestration, consensus engines, LLM gateways across 15+ providers |
| Full-Stack AI Products | Advanced | FastAPI and Go backends, Next.js frontends, OpenAI-compatible APIs, auth, rate limiting, CI |
| Deep Learning | Advanced | PyTorch training loops, MPS/CPU performance tuning, CNNs, transfer learning |

<br/>

<a id="-github-analytics"></a>
## ⟡ GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=aaravkhanal&show_icons=true&hide_border=true&theme=dark&bg_color=0b0f0e&title_color=34d399&icon_color=34d399&text_color=d1fae5&count_private=true" height="165" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=aaravkhanal&hide_border=true&theme=dark&background=0B0F0E&ring=34D399&fire=10B981&currStreakLabel=34D399" height="165" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=aaravkhanal&layout=compact&hide_border=true&theme=dark&bg_color=0b0f0e&title_color=34d399&text_color=d1fae5" height="165" />

</div>

<br/>

## ⟡ Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=aaravkhanal&theme=react-dark&hide_border=true&bg_color=0b0f0e&color=34d399&line=10b981&point=d1fae5" />

</div>

<br/>

## ⟡ Current Focus

```yaml
Building:
  - GITOWN: independent Git forge, moving toward public beta gates
  - Larger and better-evaluated small language models

Researching:
  - Memorization vs. compositional creativity (confirmatory study running)
  - Why instruction-following and length control behave differently at scale

Learning:
  - Distributed systems and scalable AI infrastructure
  - Preference tuning and continuous batching for serving

Open To:
  - Internships and collaborative engineering work
  - Research-driven AI/ML opportunities
```

<br/>

<a id="-connect"></a>
## ⟡ Connect

<div align="center">

<a href="mailto:khanalaarav2063@gmail.com">
  <img src="https://img.shields.io/badge/Email-10b981?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
<a href="https://www.linkedin.com/in/aarav-khanal-40795832a/">
  <img src="https://img.shields.io/badge/LinkedIn-047857?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="https://github.com/Aaravkhanal">
  <img src="https://img.shields.io/badge/GitHub-064e3b?style=for-the-badge&logo=github&logoColor=white" />
</a>

</div>

<br/>

<div align="center">

<i>"If it sounds impossible, it's probably worth building."</i>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:064e3b,50:047857,100:0b1f1a&height=150&section=footer" />
