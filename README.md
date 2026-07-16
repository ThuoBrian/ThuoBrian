# Brian Thuo

Backend and infrastructure engineer · Nairobi, Kenya (UTC+3)

[LinkedIn](https://www.linkedin.com/in/brian-thuo-gachau) · [Email](mailto:thuogachau@gmail.com) · [GitHub](https://github.com/ThuoBrian)

---

## About

Technology Associate at [IPA Kenya](https://www.poverty-action.org/), keeping production infrastructure running for 200+ staff across East Africa — networks, endpoints, cloud operations, and the monitoring that catches problems before they become incidents.

Outside of that, I build backend systems in Rust and Python. Most of what I ship is tooling for the kind of operational problems I run into at work: parsing logs, tracking inventory, running local models on sensitive data, and moving work through queues reliably.

---

## Engineering Principles

- **Operate by default.** Every system should be observable, recoverable, and cheap to reason about at 2 a.m.
- **Prefer small, stateless pieces.** Complexity belongs in the problem, not in the wiring.
- **Keep sensitive data close.** When the work involves internal docs or PII, local-first beats cloud-first.
- **Infrastructure changes are code changes.** Versioned, reviewed, and reversible.

---

## Tech Stack

What I actually ship, not everything I've touched.

- **Languages:** Rust, Python, SQL, Bash
- **Rust:** Actix-web, Tokio, SQLx, petgraph
- **Python:** FastAPI, ChromaDB, Pydantic
- **Data:** PostgreSQL
- **Ops:** Prometheus, Grafana, GitHub Actions, Docker

---

## Projects

### [Local RAG Support Chatbot](https://github.com/ThuoBrian/Local-RAG-Support-Chatbot)

`FastAPI` · `ChromaDB` · `Ollama` · `Pydantic`

IT-support chatbot that answers from a local document set. Designed so nothing sensitive leaves the machine: documents are chunked, embedded, and retrieved locally before being passed to a local LLM.

### [Laptop Inventory API](https://github.com/ThuoBrian/Laptop_Inventory_CLI)

`Rust` · `Actix-web` · `PostgreSQL` · `SQLx` · `Docker`

REST API for tracking laptops and assignments. Uses SQLx for compile-time checked queries and a small migrations setup so the schema stays reversible.

### [Log File Parser](https://github.com/ThuoBrian/Log_File_Parser)

`Python` · `regex` · `CLI tooling`

Parses syslog files, classifies severity, and reports error rates. Built from repeatedly triaging the same production logs at work.

### [Community Detection on Graphs](https://github.com/ThuoBrian/Community-Detection-Using-Graph)

`Rust` · `petgraph`

Builds a directed graph from usernames and finds strongly connected communities with Kosaraju's algorithm.

---

## Currently Building

A Postgres-backed distributed task queue in Rust. Current focus is crash recovery and retry semantics; next up are a dead-letter queue and a small local embeddings store.

---

## Experience

**Technology Associate** · [Innovations for Poverty Action, Kenya](https://www.poverty-action.org/) · 2018 – Present

- Run production systems and network infrastructure for 200+ staff across East Africa.
- Automated deployments and container workflows through GitHub Actions, reducing manual release steps.
- Built Prometheus and Grafana monitoring to surface incidents earlier and shorten time-to-fix.
- Own endpoint security, cloud operations, and day-to-day IT service delivery.

---

Open to senior backend and infrastructure engineering roles — remote-friendly, based in Nairobi (UTC+3).
