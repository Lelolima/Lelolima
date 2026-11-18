<div align="center">

# Wellington de Lima Catarina

**AI Engineering · LLM Applications · Python · Computer Vision · Intelligent Automation**

[LinkedIn](https://www.linkedin.com/in/wellington-de-lima-catarina/) · [Email](mailto:lelolima806@gmail.com) · [Repositories](https://github.com/Lelolima?tab=repositories)

</div>

---

## Engineering Summary

I design and build applied AI systems in Python: services that put language models, computer vision and automation behind clear APIs, with configuration, logging and tests treated as part of the product rather than an afterthought. My background is in data science and business intelligence, and my current focus is the engineering around models — orchestration, provider fallback, integration with existing systems, and the safeguards that make automation safe to run.

The repositories here are public, personal projects. Each one states its maturity plainly, and the evidence (code, tests, CI definitions) is linked so it can be checked.

## Core Engineering Expertise

Tools listed below are the ones used in the public code on this account.

| Domain | Demonstrated in public code |
|---|---|
| **AI & LLM Systems** | Multi-provider LLM orchestration with fallback (Anthropic, OpenAI, Ollama) · Hugging Face Transformers · Ultralytics YOLO, PyTorch, OpenCV · object tracking |
| **Software & Backend** | Python 3.10+ · FastAPI · Pydantic settings · async services · React + TypeScript front ends |
| **Automation & Data** | Playwright (web) · pywinauto / pynput (desktop) · pandas · Plotly Dash · ETL scripts · Power BI |
| **Quality & Delivery** | pytest · Ruff, Black, mypy · Docker and Docker Compose · GitHub Actions workflow definitions |

**Currently deepening:** retrieval-augmented generation, agent evaluation, observability for AI services, and application security.

## Selected Engineering Projects

| Project | What it does | Stack | Maturity and evidence |
|---|---|---|---|
| [**Automation-Computer**](https://github.com/Lelolima/Automation-Computer) | Desktop and web automation toolkit in which an LLM turns a goal into an action plan, with encryption and audit-logging utilities. | Python · Playwright · pywinauto · Anthropic / OpenAI / Ollama clients · Fernet, bcrypt | Prototype. Core modules implemented; [14 unit tests](https://github.com/Lelolima/Automation-Computer/tree/master/tests); [CI workflow](https://github.com/Lelolima/Automation-Computer/blob/master/.github/workflows/ci.yml) defined. Vision and web dashboard are roadmap items. |
| [**AgroVision-AI**](https://github.com/Lelolima/AgroVision-AI) | Livestock monitoring pipeline: animal detection, tracking, behaviour classification and weight estimation, served through an API. | Python · Ultralytics YOLO · PyTorch · OpenCV · FastAPI · Docker | Prototype. Runs in a simulation mode when model weights are absent; [7 tests](https://github.com/Lelolima/AgroVision-AI/blob/main/tests/test_api.py). No trained weights or benchmark results are published yet. |
| [**Logistics Dashboard**](https://github.com/Lelolima/Dashboard-de-log-stica-feito-em-Python) | Delivery-operations dashboard with a separated data loading, validation, processing and visualisation layer. | Python · Plotly Dash · pandas · Docker | Working prototype on seeded synthetic data. [25 tests](https://github.com/Lelolima/Dashboard-de-log-stica-feito-em-Python/tree/main/tests); Ruff and mypy configured; [CI workflow](https://github.com/Lelolima/Dashboard-de-log-stica-feito-em-Python/blob/main/.github/workflows/ci.yml) defined. |
| [**Document Management with AI**](https://github.com/Lelolima/Sistema-de-Gerenciamento-de-Documentos-com-IA) | Document upload, text extraction, text analysis and version comparison behind a REST API with a web client. | Python · FastAPI · React · TypeScript · Docker Compose | Prototype. Backend services and front-end pages implemented; [backend tests](https://github.com/Lelolima/Sistema-de-Gerenciamento-de-Documentos-com-IA/tree/main/project/backend/tests) cover the service layer. |
| [**Healthcare Analytics**](https://github.com/Lelolima/Sess-o-Power-BI-) | Hospital KPI analytics: a Python ETL step, a web dashboard and Power BI / DAX documentation. | Python · pandas · Power BI · Docker | Portfolio study with documentation and [tests](https://github.com/Lelolima/Sess-o-Power-BI-/tree/main/tests) for the utility layer. |

## Engineering Principles

- **Simple architecture first.** Small modules with one responsibility; complexity has to justify itself.
- **Reliability over demos.** Explicit fallbacks, typed configuration and error handling at system boundaries.
- **Security by default.** Secrets stay in the environment, inputs are validated, and automation is constrained and auditable.
- **Testable and observable.** If behaviour cannot be tested or traced through logs, it is not finished.
- **Evaluate AI, don't assume it.** Model output is measured against expectations before it is trusted.
- **Documentation as an interface.** A README should state what works, what does not, and how to verify it.

## Engineering Notes & Technical Exploration

Experimental work, kept separate from the projects above:

- [ShadowForge-Agent](https://github.com/Lelolima/ShadowForge-Agent) — research into agent decision loops and guardrails for authorised security testing.
- [O-olho-de-DEUS](https://github.com/Lelolima/O-olho-de-DEUS) — study of an edge-to-cloud video analytics architecture with privacy masking, human review and audit logging.
- [Advanced-AI-Pipeline-Architecture](https://github.com/Lelolima/Advanced-AI-Pipeline-Architecture) — exploration of a multimodal analysis pipeline with a TypeScript interface and a Python backend.

## Connect & Collaborate

Technical discussion, code review and open-source collaboration are welcome — on AI systems engineering, LLM applications, computer vision and automation.

[LinkedIn](https://www.linkedin.com/in/wellington-de-lima-catarina/) · [lelolima806@gmail.com](mailto:lelolima806@gmail.com)

---

<sub>🇧🇷 <strong>Em português:</strong> Engenharia de IA aplicada em Python — sistemas com LLMs, visão computacional e automação, construídos com atenção a arquitetura, testes e segurança. Trajetória em ciência de dados e BI; foco atual em engenharia de sistemas inteligentes. Os projetos acima são pessoais e indicam com clareza o estágio de maturidade de cada um.</sub>
