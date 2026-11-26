<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=160&section=header&text=Manthan%20Chauhan&fontSize=44&fontColor=fff&animation=fadeIn&fontAlignY=34&desc=Backend%20Systems%20%C2%B7%20LLM%20Applications%20%C2%B7%20Applied%20ML&descAlignY=56&descSize=16" width="100%"/>

B.Tech CSE @ **SVNIT Surat** · Software engineer building backend systems, LLM applications and streaming ML pipelines

<a href="https://manthan-chauhan.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-A78BFA?style=for-the-badge&logo=vercel&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/manthan-chauhan-373a5a2a8/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:manthansvnit9868@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>

</div>

---

## 🚀 Featured Projects

### [AI Workflow Builder](https://github.com/manthu01/Ai-Workflow-Builder): natural language to executable automation pipelines
`TypeScript` `Claude API` `Temporal` `React Flow` `Hono` `PostgreSQL` `pgvector` `Drizzle` `SSE`

- An LLM compiler that turns plain-English requests into validated, executable workflow DAGs on a React Flow canvas. It routes each request to a model by complexity, retries with validation feedback to repair bad output, and ingests OpenAPI specs as callable API nodes.
- A durable execution engine on Temporal. Each node runs as an isolated, retryable activity, with parallel fan-out, conditional branching, human-in-the-loop approvals, LLM self-healing of failed nodes and live per-node progress over SSE.

### [PulseGuard](https://github.com/manthu01/Real-Time-Transaction-Pipeline-Fraud-Detection): real-time transaction monitoring and fraud detection
`Kafka` `Spark Structured Streaming` `Delta Lake` `Redis` `LightGBM` `SHAP` `NestJS` `Next.js` `WebSockets`

- A streaming pipeline on Kafka and Spark Structured Streaming. It computes 26 rolling behavioural features per customer into a Redis online feature store that training and serving share.
- A LightGBM champion with an Isolation Forest in shadow mode. It scores **PR-AUC 0.906 vs. 0.457** on 188K synthetic UPI/card/NEFT transactions and lifts recall from **91.9% to 96.8%** at a fixed 200 alerts/day. Every alert gets a TreeSHAP explanation in a live analyst console.

### [Ledgr](https://github.com/manthu01/Ledgr): expense splitting and group ledger · [Live ↗](https://get-ledgr.vercel.app/)
`Next.js` `NestJS` `TypeScript` `PostgreSQL` `Prisma` `Zod` `JWT` `Google OAuth` `Telegram Bot API` `GitHub Actions`

- A Splitwise-style platform with server-side integer-cent splits. Greedy debt simplification settles any group in at most n−1 transfers, and a webhook-driven Telegram bot logs expenses from chat messages.
- bcrypt and Google OAuth auth with short-lived JWTs and rotated httpOnly refresh cookies. A 1+2N request fan-out became a 3-query summary endpoint. The API is hardened with rate limiting, Helmet, shared Zod schemas and CI.

### [LectureLens](https://github.com/manthu01/LectureLens): Ctrl+F for your entire semester of lectures · [Live ↗](https://lecturelens-app.vercel.app)
`Python` `FastAPI` `Whisper` `Gemini` `Qdrant` `BM25` `Cross-encoder` `Next.js` `SSE`

- A RAG system over lecture videos. Whisper transcribes YouTube playlists with timestamps (Hindi/Hinglish translated to English), an LLM labels each segment, and answers cite the exact second the lecturer explained it.
- Hybrid dense + BM25 retrieval fused with RRF reaches **Recall@1 0.96 and MRR 0.98** on a held-out eval set. A confidence gate refuses questions the lectures don't cover instead of guessing.

### More projects

| Project | What it is | Stack |
|:--|:--|:--|
| [**CreditFlow**](https://github.com/manthu01/Loan-Origination-Decisioning-System) | Loan origination & credit decisioning: versioned policy rules, a WOE scorecard (AUC 0.71, KS 0.31), reason codes, a hash-chained audit log with replay and a what-if policy simulator | NestJS · FastAPI · Next.js · PostgreSQL · XGBoost |
| [**Gigapixel WSI Viewer**](https://github.com/manthu01/gigapixel-wsi-viewer) | Streams 8-gigapixel pathology slides into the browser: a Deep Zoom tile pyramid, an nginx-accelerated tile API and a custom 60 fps canvas viewer with annotations | Django · Celery · Redis · React · nginx |
| [**FlowSync**](https://github.com/manthu01/flowsync-productivity-suite) · [Live ↗](https://flowsync-productivity-suite.vercel.app) | Collaborative task manager with real-time shared tasks, recurring tasks, analytics and an audited admin panel | React · Express · Socket.io · PostgreSQL |

---

## 🧰 Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=ts,py,cpp,js,react,nextjs,tailwind&theme=dark" />
<br/>
<img src="https://skillicons.dev/icons?i=nodejs,nestjs,express,fastapi,postgres,redis,mysql,prisma&theme=dark" />
<br/>
<img src="https://skillicons.dev/icons?i=kafka,sklearn,docker,nginx,githubactions,jest,vercel,git&theme=dark" />

</div>

| Area | Tools |
|:--|:--|
| **AI & LLM systems** | Claude API, RAG, embeddings, hybrid search (vector + full-text, RRF), retrieval eval (recall@k, MRR), structured outputs |
| **Machine learning** | LightGBM, XGBoost, scikit-learn, SHAP, pandas, NumPy: anomaly detection, imbalanced classification, drift monitoring (PSI) |
| **Data engineering** | Apache Kafka, Spark Structured Streaming, Delta Lake, Redis online feature stores, exactly-once stream processing |
| **Backend** | Node.js, NestJS, Express, Hono, FastAPI, Temporal, REST, WebSockets, SSE, JWT/OAuth, Zod |
| **Data & DevOps** | PostgreSQL, pgvector, MySQL, Redis, Prisma, Drizzle, Docker, nginx, GitHub Actions, Vercel, Render |

---

## ⚔️ Competitive Programming

| Platform | Rank | Max Rating |
|:--|:--|:--|
| [LeetCode](https://leetcode.com/u/Manthu01/) | Knight | **1924** |
| [CodeChef](https://www.codechef.com/users/manthu01) | 3★ | **1643** |
| [Codeforces](https://codeforces.com/profile/manthu01) | Pupil | **1321** |

🏆 3rd place, **CodeSprint 2K24** (Nexus, NIT Surat) · Organiser of **CodeCraft**, a multi-round coding event · Solutions: [Leetcode-Solutions](https://github.com/manthu01/Leetcode-Solutions)

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

</div>
