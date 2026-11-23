<div align="center">

<h1>Siddhant Thakur</h1>
<h3>Backend Python Developer &nbsp;·&nbsp; FastAPI · PostgreSQL · LLM &amp; RAG systems</h3>

<p><em>I start with the system, not the screen: where the data lives, what happens when many people use it at once, what each request costs, and what someone sees when it breaks.</em></p>

[![Portfolio](https://img.shields.io/badge/Portfolio-siddhantthakur.pages.dev-0e1216?style=flat-square&logo=cloudflare&logoColor=f0a63a)](https://siddhantthakur.pages.dev)
[![Reflect](https://img.shields.io/badge/Live-reflectcareer.com-79c99a?style=flat-square)](https://reflectcareer.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Siddhant_Thakur-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/siddhantthakur-/)
[![Email](https://img.shields.io/badge/Email-siddhantt649@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:siddhantt649@gmail.com)

</div>

---

## About me

I'm a backend Python developer in Kolkata. I build systems end to end and then run them: FastAPI services on PostgreSQL, background pipelines, and LLM features designed for cost and failure.

- **Building:** Reflect, a live résumé-to-job analysis platform I designed, built and operate
- **Strong in:** API design, relational data, RAG, testing the way a system actually fails
- **Background:** MCA, Techno Main Salt Lake (MAKAUT), 2025 · B.Sc. Computer Science, University of Calcutta
- **Open to:** backend and Python developer roles (India or remote) and freelance API work

The incident write-ups, what broke and how I fixed it, are on my [portfolio](https://siddhantthakur.pages.dev/#incidents).

---

## Featured projects

### [Reflect](https://reflectcareer.com): résumé-to-job match analysis
> *Python 3.11 · FastAPI · PostgreSQL · SQLAlchemy 2 (async) · Alembic · spaCy · sentence-transformers · Next.js · Docker · Caddy*

Reads a résumé against a job description and gives an honest verdict, the evidence behind it, and what to fix.

- **Code decides, the model explains.** Verdict, score and gaps come from deterministic Python; a language model only writes the explanation, with a template fallback and a budget gate, at about $1 per 1,500 analyses.
- **Built to survive real use.** A background pipeline saves each stage to PostgreSQL; live progress over SSE with a polling fallback; session-scoped access control.
- **Caught a FastAPI upgrade regression before release:** only 4 of 10 concurrent analyses finished because DB sessions stayed open through the pipeline. Fixed the session scope and added a 1-to-20-user load gate (45/45 after).
- **Self-hosted on Oracle Cloud** with Docker and Caddy: staging before production, encrypted backups, health and certificate alerts. 1,500+ backend and 1,000+ frontend tests.

> *The repository is private to protect the scoring logic. Happy to walk through the architecture in an interview.*

### [VisionaryX 2.0](https://github.com/siddhant-17-codes/VisionaryX-2.0): AI document Q&A with page citations
> *FastAPI · LangChain · FAISS · Gemini · Supabase · React · Vercel · Render*

- Page- and section-aware PDF/DOCX extraction, 1,000-character chunks, Gemini embeddings, a per-chat FAISS index and an adaptive relevance filter.
- Citations are built from the chunks sent to the model, never parsed from its text. Also answers questions about images and generates them.
- Replaced pickle-based index storage (a code-execution risk) with a JSON format and a data-only reader for old indexes.
- Read the [RAG deep dive](https://github.com/siddhant-17-codes/VisionaryX-2.0/blob/main/docs/RAG_DEEP_DIVE.md), which explains every number in the pipeline.

### [MindMate](https://github.com/siddhant-17-codes/mindmate): mental-wellness mobile app (MCA major project)
> *Flutter · Dart · Firebase Auth · Cloud Firestore*

- Led a team of five; built Firebase Authentication (email verification, password reset, Google Sign-In) and Firestore user profiles.
- Redesigned the mood-assessment feature within five days after review feedback.

### [Portfolio](https://github.com/siddhant-17-codes/portfolio)
> *Astro · TypeScript · Cloudflare Pages*

Hand-built static site with a live health-check trace of my deployed projects, a hash-based Content-Security-Policy, and Lighthouse 100 on performance, accessibility and SEO.

---

## Tech stack

| Area | Technologies |
|---|---|
| **Languages** | Python · SQL · Java · TypeScript · C++ |
| **Backend & data** | FastAPI · Pydantic · SQLAlchemy (async) · Alembic · PostgreSQL · MySQL · Oracle SQL & PL/SQL · REST · SSE |
| **AI / ML** | RAG · embeddings · FAISS · LangChain · Claude & Gemini APIs · spaCy · sentence-transformers · scikit-learn · PyTorch |
| **Infra & tools** | Docker · Caddy · Oracle Cloud · Cloudflare · Vercel · Render · Supabase · Git · pytest · Vitest |
| **Frontend & mobile** | React · Next.js · Astro · Tailwind CSS · Flutter |

---

## Achievements

<p>
  <a href="https://github.com/siddhant-17-codes?tab=achievements"><img src="https://github.githubassets.com/assets/pull-shark-default-498c279a747d.png" width="72" alt="Pull Shark" title="Pull Shark: opened pull requests that have been merged" /></a>
  &nbsp;
  <a href="https://github.com/siddhant-17-codes?tab=achievements"><img src="https://github.githubassets.com/assets/pair-extraordinaire-default-579438a20e01.png" width="72" alt="Pair Extraordinaire" title="Pair Extraordinaire: co-authored commits on merged pull requests" /></a>
</p>

- **Pull Shark** (GitHub, Nov 2026): opened pull requests that were merged
- **Pair Extraordinaire** (GitHub, Nov 2026): co-authored commits on merged pull requests
- **HackerRank Orchestrate** (Oct 2026): built and deployed an AI agent, ranked 971 of 4,094
- **WBJEE JECA 2023:** state rank 530

## Certifications

- IBM: Machine Learning for Data Science Projects ([verify](https://www.credly.com/go/7g3L8d3A)) · Journey to Cloud: Envisioning Your Solution ([verify](https://www.credly.com/go/sMXlQhQd))
- AWS: Introduction to Generative AI – Art of the Possible
- NPTEL (IIT Kharagpur): Introduction to Internet of Things, Elite
- LinkedIn Learning: AWS Certified Machine Learning Engineer – Associate (MLA-C01) Cert Prep

---

## GitHub stats

<div align="center">

![GitHub Streak](https://streak-stats.demolab.com/?user=siddhant-17-codes&theme=github-dark-blue&hide_border=true)

<br/>

![Profile Summary](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=siddhant-17-codes&theme=github_dark)

</div>

---

<div align="center">
<sub>Open to backend engineering roles · CV on request · siddhantt649@gmail.com</sub>
</div>
