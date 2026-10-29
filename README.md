<p align="center">
  <a href="mailto:gthejesraj@gmail.com">Email</a>
  &nbsp;/&nbsp;
  <a href="https://www.linkedin.com/in/thejes-raj">LinkedIn</a>
  &nbsp;/&nbsp;
  <a href="https://github.com/Gthejesraj/driftfix">driftfix</a>
  &nbsp;/&nbsp;
  <a href="https://github.com/Gthejesraj?tab=repositories">Projects</a>
</p>

<p align="center">
  <img src="./assets/profile-hero.svg" alt="Thejes Raj Gangadhar - developer tools and AI systems" width="100%" />
</p>

<p align="center">
  <strong>I build developer tools and AI systems that turn messy failures into reviewable fixes.</strong>
</p>

<p align="center">
  <sub>agentic systems / LLM evaluation / code migration / RAG / developer tools</sub>
</p>

---

### Now Building

[driftfix](https://github.com/Gthejesraj/driftfix) fixes your code when a Dependabot upgrade breaks CI. It reads the failing tests and the changelog, has Claude adapt the code to the new version, reruns your tests itself, and only commits to the PR if they pass. If it can't get to green, it leaves a comment and commits nothing.

- 12/12 breaking upgrades fixed on the benchmark (httpx, numpy, openai, pydantic, SQLAlchemy, Django, and more) at $0.12 to $0.51 per fix, with no tests edited.
- Ran it on 183 real repos still on pydantic 1, SQLAlchemy 1.x or numpy 1. 16 broke on upgrade, and 9 of those fixes were clean and mergeable.
- Replayed 13 migrations that maintainers had already made. driftfix fixed 10.

Ships as a GitHub Action and a CLI (`pip install driftfix`).

---

### Open Source

| Project | Contribution | Status |
| --- | --- | --- |
| [OpenLIT](https://github.com/openlit/openlit/pull/1539) | Fixed Mistral SDK 2.x instrumentation paths while keeping 1.x compatibility, with regression coverage. | Merged |
| [Intuit StuntDouble](https://github.com/intuit/stunt-double/pull/78) | Added recursive nested operator matching in InputMatcher (fixes #60), with regression tests. | Merged |
| [EcoTrace](https://github.com/Zwony/ecotrace/pull/198) | Added a LangChain callback handler for per-run LLM energy and emissions tracking. | Merged |
| [Dagster](https://github.com/dagster-io/dagster/pull/34181) | Kept ordering and blank lines intact when writing newly pulled .env variables. | Open |

---

### Selected Work

| Project | What it does | Stack |
| --- | --- | --- |
| [WireMend](https://github.com/Gthejesraj/wiremend) | Captures failing API calls, maps them to the Python source line, and prepares a validated, reviewable fix PR. | Python, GitHub API |
| [WHO Report RAG Question Answering](https://github.com/Gthejesraj/who-report-rag-question-answering) | Hybrid retrieval, reranking, and grounded answer generation over WHO reports. | RAG, BM25, embeddings, OpenAI |
| [Agentic E-Commerce Shopping Assistant](https://github.com/Gthejesraj/agentic-ecommerce-shopping-assistant) | Search, price comparison, sentiment analysis, and recommendation through specialized agents. | Python, Gemini, Hugging Face, SerpApi |
| [Amazon Review Sentiment DistilBERT](https://github.com/Gthejesraj/amazon-review-sentiment-distilbert) | DistilBERT fine-tuning for large-scale Amazon review sentiment classification. | PyTorch, Transformers, scikit-learn |
| [Research Paper Knowledge Graph](https://github.com/Gthejesraj/research-paper-knowledge-graph) | Semantic knowledge graph for research papers with graph storage and embeddings. | Neo4j, embeddings, Python |
| [Data Engineering Pipeline Project](https://github.com/Gthejesraj/data-engineering-pipeline-project) | Modern analytics pipeline with orchestration and transformation layers. | Airflow, dbt, dashboards |

---

### Technical Interests

- Developer tools with a clear review surface.
- LLM agents that stay bounded, testable, and inspectable.
- Dependency and API migrations that don't need a human to babysit them.
- Retrieval and evaluation systems that explain why they fail.

---

### Tools I Use

Python, TypeScript, PyTorch, vLLM, LangGraph, LangChain, OpenAI, Neo4j, PostgreSQL, Airflow, dbt, Docker, React, AWS.

---

<p align="center">
  <sub>Open to ML engineering and AI engineering roles, and always happy to talk developer tools and production AI systems.</sub>
</p>
