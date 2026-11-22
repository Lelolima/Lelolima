<a id="top"></a>

<div align="center">

<img src="assets/header.svg" alt="Wellington de Lima Catarina - AI Engineering, LLM Applications, Python, Computer Vision, Intelligent Automation" width="100%">

[Summary](#engineering-summary) · [Expertise](#core-engineering-expertise) · [Projects](#selected-engineering-projects) · [Principles](#engineering-principles) · [Exploration](#engineering-notes--technical-exploration) · [Connect](#connect--collaborate)

[LinkedIn](https://www.linkedin.com/in/wellington-de-lima-catarina/) · [Email](mailto:lelolima806@gmail.com) · [Repositories](https://github.com/Lelolima?tab=repositories)

</div>

---

## Engineering Summary

I design and build applied AI systems in Python: services that put language models, computer vision and automation behind clear APIs, with configuration, logging and tests treated as part of the product rather than an afterthought. My background is in data science and business intelligence, and my current focus is the engineering around models — orchestration, provider fallback, integration with existing systems, and the safeguards that make automation safe to run.

The repositories here are public, personal projects. Each one states its maturity plainly, and the evidence (code, tests, CI definitions) is linked so it can be checked.

<details>
<summary>🇧🇷 <strong>Ler em português</strong></summary>
<br>

Engenharia de IA aplicada em Python — sistemas com LLMs, visão computacional e automação, construídos com atenção a arquitetura, testes e segurança. Trajetória em ciência de dados e BI; foco atual em engenharia de sistemas inteligentes. Os projetos abaixo são pessoais e indicam com clareza o estágio de maturidade de cada um.

</details>

## Core Engineering Expertise

Click a domain to expand it. Tools listed are the ones used in the public code on this account.

<details open>
<summary><strong>AI &amp; LLM Systems</strong></summary>
<br>

- Multi-provider LLM orchestration with fallback (Anthropic, OpenAI, Ollama)
- Hugging Face Transformers
- Ultralytics YOLO, PyTorch, OpenCV, object tracking

</details>

<details>
<summary><strong>Software &amp; Backend Engineering</strong></summary>
<br>

- Python 3.10+, FastAPI, Pydantic settings, async services
- React + TypeScript front ends

</details>

<details>
<summary><strong>Automation &amp; Data</strong></summary>
<br>

- Playwright (web), pywinauto / pynput (desktop)
- pandas, Plotly Dash, Streamlit, ETL scripts, Power BI

</details>

<details>
<summary><strong>Quality &amp; Delivery</strong></summary>
<br>

- pytest, Ruff, Black, mypy
- Docker and Docker Compose
- GitHub Actions workflow definitions

</details>

**Currently deepening:** retrieval-augmented generation, agent evaluation, observability for AI services, and application security.

## Selected Engineering Projects

Each project opens to show the approach, stack, maturity and where to verify it.

<details open>
<summary><strong>Automation-Computer</strong> — LLM-planned desktop and web automation</summary>
<br>

| | |
|---|---|
| **Problem** | Automating multi-step desktop and web tasks from a stated goal. |
| **Approach** | An LLM turns the goal into an action plan; controllers execute it, with encryption and audit-logging utilities. |
| **Stack** | Python · Playwright · pywinauto · Anthropic / OpenAI / Ollama clients · Fernet, bcrypt |
| **Maturity** | Prototype. Core modules implemented; vision and web dashboard are roadmap items. |
| **Evidence** | [Code](https://github.com/Lelolima/Automation-Computer) · [Tests](https://github.com/Lelolima/Automation-Computer/tree/master/tests) · [CI workflow definition](https://github.com/Lelolima/Automation-Computer/blob/master/.github/workflows/ci.yml) |

</details>

<details>
<summary><strong>AgroVision-AI</strong> — computer vision for livestock monitoring</summary>
<br>

| | |
|---|---|
| **Problem** | Monitoring animals from video without manual counting or weighing. |
| **Approach** | Detection, tracking, behaviour classification and weight estimation, served through an API. |
| **Stack** | Python · Ultralytics YOLO · PyTorch · OpenCV · FastAPI · Docker |
| **Maturity** | Prototype. Runs in a simulation mode when model weights are absent; no trained weights or benchmark results are published yet. |
| **Evidence** | [Code](https://github.com/Lelolima/AgroVision-AI) · [Tests](https://github.com/Lelolima/AgroVision-AI/tree/main/tests) · [CI workflow definition](https://github.com/Lelolima/AgroVision-AI/blob/main/.github/workflows/ci.yml) |

</details>

<details>
<summary><strong>Logistics Dashboard</strong> — delivery operations analytics in Python</summary>
<br>

| | |
|---|---|
| **Problem** | Giving operations a single view of delivery status, hubs and performance. |
| **Approach** | Separate data loading, validation, processing and visualisation layers. |
| **Stack** | Python · Plotly Dash · pandas · Docker |
| **Maturity** | Working prototype on seeded synthetic data; Ruff and mypy configured. |
| **Evidence** | [Code](https://github.com/Lelolima/Dashboard-de-log-stica-feito-em-Python) · [Tests](https://github.com/Lelolima/Dashboard-de-log-stica-feito-em-Python/tree/main/tests) · [CI workflow definition](https://github.com/Lelolima/Dashboard-de-log-stica-feito-em-Python/blob/main/.github/workflows/ci.yml) |

</details>

<details>
<summary><strong>Document Management with AI</strong> — extraction, analysis and comparison API</summary>
<br>

| | |
|---|---|
| **Problem** | Extracting, analysing and comparing the content of uploaded documents. |
| **Approach** | REST API for upload, text extraction, text analysis and version comparison, with a web client. |
| **Stack** | Python · FastAPI · PyMuPDF · python-docx · Tesseract OCR · React · TypeScript · Docker Compose |
| **Maturity** | Prototype. Backend services and front-end pages implemented. |
| **Evidence** | [Code](https://github.com/Lelolima/Sistema-de-Gerenciamento-de-Documentos-com-IA) · [Backend tests](https://github.com/Lelolima/Sistema-de-Gerenciamento-de-Documentos-com-IA/tree/main/project/backend/tests) |

</details>

<details>
<summary><strong>Healthcare Analytics</strong> — hospital KPI study with ETL and BI</summary>
<br>

| | |
|---|---|
| **Problem** | Tracking hospital KPIs such as occupancy, waiting time and cost per procedure. |
| **Approach** | A Python ETL step, a Streamlit dashboard on synthetic data, and Power BI / DAX documentation. |
| **Stack** | Python · pandas · Streamlit · Power BI · Docker |
| **Maturity** | Portfolio study. |
| **Evidence** | [Code](https://github.com/Lelolima/Sess-o-Power-BI-) · [Tests](https://github.com/Lelolima/Sess-o-Power-BI-/tree/main/tests) |

</details>

## Engineering Principles

<details>
<summary><strong>Six principles I build by</strong></summary>
<br>

- **Simple architecture first.** Small modules with one responsibility; complexity has to justify itself.
- **Reliability over demos.** Explicit fallbacks, typed configuration and error handling at system boundaries.
- **Security by default.** Secrets stay in the environment, inputs are validated, and automation is constrained and auditable.
- **Testable and observable.** If behaviour cannot be tested or traced through logs, it is not finished.
- **Evaluate AI, don't assume it.** Model output is measured against expectations before it is trusted.
- **Documentation as an interface.** A README should state what works, what does not, and how to verify it.

</details>

## Engineering Notes & Technical Exploration

<details>
<summary><strong>Experimental work</strong>, kept separate from the projects above</summary>
<br>

- [ShadowForge-Agent](https://github.com/Lelolima/ShadowForge-Agent) — research into agent decision loops and guardrails for authorised security testing.
- [O-olho-de-DEUS](https://github.com/Lelolima/O-olho-de-DEUS) — study of an edge-to-cloud video analytics architecture with privacy masking, human review and audit logging.
- [Advanced-AI-Pipeline-Architecture](https://github.com/Lelolima/Advanced-AI-Pipeline-Architecture) — exploration of a multimodal analysis pipeline with a TypeScript interface and a Python backend.

</details>

## Connect & Collaborate

Technical discussion, code review and open-source collaboration are welcome — on AI systems engineering, LLM applications, computer vision and automation.

[LinkedIn](https://www.linkedin.com/in/wellington-de-lima-catarina/) · [lelolima806@gmail.com](mailto:lelolima806@gmail.com)

<div align="right">

[Back to top ↑](#top)

</div>
