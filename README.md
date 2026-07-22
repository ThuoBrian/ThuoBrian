# Brian Thuo

Backend and infrastructure engineer · Nairobi, Kenya (UTC+3)

[LinkedIn](https://www.linkedin.com/in/brian-thuo-gachau) · [Email](mailto:thuogachau@gmail.com) · [GitHub](https://github.com/ThuoBrian)

---

## About

I'm a Technology Lead at [IPA Kenya](https://www.poverty-action.org/), where I keep IT running for 200+ staff across East Africa — networks, endpoints, cloud ops, and the monitoring that (hopefully) catches things before they turn into an incident.

Outside of that, I build backend systems in Rust and Python, usually to solve the same kinds of problems I hit at work: parsing logs, tracking inventory, running models locally on data that shouldn't leave the building, and moving jobs through queues without losing any. I like small, boring, reversible systems more than clever ones — boring is easier to fix at 2 a.m.

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

An IT-support chatbot that answers from a local document set — no data leaves the machine. Docs get chunked, embedded, and searched locally, then handed to a local LLM.

### [Laptop Inventory API](https://github.com/ThuoBrian/Laptop_Inventory_CLI)

`Rust` · `Actix-web` · `PostgreSQL` · `SQLx` · `Docker`

A REST API for tracking laptops and who has them. Uses SQLx for compile-time checked queries, with migrations so the schema can always be rolled back.

### [Log File Parser](https://github.com/ThuoBrian/Log_File_Parser)

`Python` · `regex` · `CLI tooling`

Parses syslog files and reports error rates by severity. Built after triaging the same production logs by hand one too many times.

### [Community Detection on Graphs](https://github.com/ThuoBrian/Community-Detection-Using-Graph)

`Rust` · `petgraph`

Builds a graph from usernames and finds tightly-connected communities using Kosaraju's algorithm.

---

## Currently Building

A Postgres-backed task queue in Rust. Right now: crash recovery and retries. Next: a dead-letter queue and a small local embeddings store.

---

## Experience

**Technology Lead** · [Innovations for Poverty Action, Kenya](https://www.poverty-action.org/) · 2018 – Present

- Keep production systems and network infrastructure running for 200+ staff across East Africa.
- Automated deployments with GitHub Actions so releases don't need babysitting.
- Set up Prometheus and Grafana monitoring to catch problems before people notice them.
- Handle endpoint security, cloud operations, and day-to-day IT support.

---

Open to backend and infrastructure engineering roles — remote-friendly, based in Nairobi (UTC+3).
