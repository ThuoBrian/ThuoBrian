# Brian Thuo

Backend and infrastructure engineer in Nairobi, Kenya.

[LinkedIn](https://www.linkedin.com/in/brian-thuo-gachau) · [Email](mailto:thuogachau@gmail.com) · [GitHub](https://github.com/ThuoBrian)

---

## About

Technology Associate at IPA Kenya, where I keep infrastructure running for 200+ staff across East Africa — networks, endpoints, cloud operations, and the monitoring that flags problems before they become incidents. Outside of that, I write backend services in Rust and Python, mostly tooling for the kind of IT problems I run into at work.

---

## Tech Stack

What I actually ship, not everything I've touched.

- **Languages:** Rust, Python, SQL, Bash
- **Rust:** Actix-web, Tokio, SQLx, petgraph
- **Python:** FastAPI, ChromaDB, Pydantic
- **Data:** PostgreSQL

---

## Projects

### [Local RAG Support Chatbot](https://github.com/ThuoBrian/Local-RAG-Support-Chatbot)

IT-support chatbot that answers from a local set of documents — nothing leaves the machine. FastAPI and ChromaDB in front of a local Ollama model.

### [Laptop Inventory API](https://github.com/ThuoBrian/Laptop_Inventory_CLI)

REST API for tracking laptops and who they're assigned to. Rust, Actix-web, PostgreSQL via SQLx.

### [Log File Parser](https://github.com/ThuoBrian/Log_File_Parser)

Parses syslog files, classifies severity, and reports error rates. Came out of triaging production logs at work.

### [Community Detection on Graphs](https://github.com/ThuoBrian/Community-Detection-Using-Graph)

Builds a directed graph from usernames and finds strongly connected communities with Kosaraju's algorithm, using `petgraph`.

---

## Currently Building

A distributed task queue in Rust, Postgres-backed. Working through crash recovery and retry handling now; a dead-letter queue and a small embeddings store are next.

---

## Experience

**Technology Associate** · [Innovations for Poverty Action, Kenya](https://www.poverty-action.org/) · 2018 – Present

- Keep production systems running for 200+ staff across East Africa
- Automated deployments with GitHub Actions and container workflows, cutting release time and manual steps
- Built Prometheus and Grafana monitoring that surfaces incidents faster and shortens time-to-fix
- Run network infrastructure, endpoint security, and day-to-day IT service delivery

---

Open to Rust and Python backend roles and IT/infrastructure engineering — remote-friendly, based in Nairobi (UTC+3).
