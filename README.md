# Brian Thuo

Backend & infrastructure engineer · Nairobi, Kenya (UTC+3)

[Email](mailto:thuogachau@gmail.com) · [GitHub](https://github.com/ThuoBrian) · [LinkedIn](https://www.linkedin.com/in/brian-thuo-gachau)

---

## What I do

I build small, boring systems that are easy to fix at 2 a.m. — because I keep IT running for 200+ staff across East Africa, and I've been paged enough to know clever doesn't survive production.

Most of my code is in Rust and Python: parsers for logs I got tired of reading by hand, inventory APIs with compile-time query checks, and local RAG pipelines for data that shouldn't leave the building.

---

## Selected work

| Project | Stack | Why it exists |
|--------|-------|-------------|
| [Local RAG Support Chatbot](https://github.com/ThuoBrian/Local-RAG-Support-Chatbot) | FastAPI, ChromaDB, Ollama, Pydantic | IT-support chatbot that answers from local docs. No external API calls. No data leaves the machine. |
| [Laptop Inventory API](https://github.com/ThuoBrian/Laptop_Inventory_CLI) | Rust, Actix-web, PostgreSQL, SQLx, Docker | Tracks hardware assignments. SQLx gives compile-time checked queries; migrations roll back cleanly. |
| [Log File Parser](https://github.com/ThuoBrian/Log_File_Parser) | Python, regex | Turns syslog noise into error-rate reports. Built after one too many manual triage sessions. |
| [Community Detection](https://github.com/ThuoBrian/Community-Detection-Using-Graph) | Rust, petgraph | Finds tightly-connected user communities with Kosaraju's algorithm. |

---

## Currently building

A Postgres-backed task queue in Rust — crash recovery, retries, and a dead-letter queue. Because reliable job handling shouldn't require a managed service.

---

## Let's talk

If you're hiring for backend or infrastructure roles — or just want to compare notes on Rust error handling — [send me an email](mailto:thuogachau@gmail.com). Remote-friendly, based in Nairobi (UTC+3).
