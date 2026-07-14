<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=F7931E&center=true&vCenter=true&width=600&lines=Brian+Thuo+%F0%9F%A6%80;Rust+%26+Python+Engineer;IT+Infrastructure+%26+Systems)](https://git.io/typing-svg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/brian-thuo-gachau)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:thuogachau@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ThuoBrian)

</div>

---

## About Me

Backend and infrastructure engineer in Nairobi, Kenya. I write Rust and Python, and I run the systems they live on.

I'm a Technology Associate at IPA Kenya, where I keep the infrastructure working for 200+ staff across East Africa: networks, endpoints, cloud operations, and the monitoring that tells me when something breaks. Most of my public work is where those two sides meet — backend services in Rust, and tooling for the kind of IT problems I deal with day to day.

```rust
fn brian() -> Engineer {
    Engineer {
        languages: vec!["Rust", "Python", "Bash", "SQL"],
        focus:     vec!["Backend Systems", "IT Infrastructure", "AI Tooling"],
        location:  "Nairobi, Kenya 🌍",
        seeking:   "Rust & systems engineering roles, remote-friendly",
    }
}
```

---

## Tech Stack

**Languages** &nbsp;
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Backend** &nbsp;
![Axum](https://img.shields.io/badge/Axum-000000?style=for-the-badge&logo=rust&logoColor=white)
![Tokio](https://img.shields.io/badge/Tokio-000000?style=for-the-badge&logo=rust&logoColor=orange)
![Actix](https://img.shields.io/badge/Actix-000000?style=for-the-badge&logo=rust&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![SQLx](https://img.shields.io/badge/SQLx-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Data** &nbsp;
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

**Infra & Ops** &nbsp;
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

---

## Projects

<table>
<tr>
<td width="50%">

### Local RAG Support Chatbot
[![Repo](https://img.shields.io/badge/View-181717?style=flat-square&logo=github)](https://github.com/ThuoBrian/Local-RAG-Support-Chatbot)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)

An IT-support chatbot that answers from a local document set — no data leaves the machine. Runs on Ollama and ChromaDB behind a FastAPI web UI with streamed (SSE) responses.

</td>
<td width="50%">

### Laptop Inventory API
[![Repo](https://img.shields.io/badge/View-181717?style=flat-square&logo=github)](https://github.com/ThuoBrian/Laptop_Inventory_CLI)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust)

A REST API for tracking laptops and who they're assigned to, written in Rust with Actix-web and PostgreSQL.

</td>
</tr>
<tr>
<td width="50%">

### Log File Parser
[![Repo](https://img.shields.io/badge/View-181717?style=flat-square&logo=github)](https://github.com/ThuoBrian/Log_File_Parser)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust)

A Rust utility that parses syslog files, detects errors, and reports error rates. Came out of triaging real production logs at work.

</td>
<td width="50%">

### Community Detection on Graphs
[![Repo](https://img.shields.io/badge/View-181717?style=flat-square&logo=github)](https://github.com/ThuoBrian/Community-Detection-Using-Graph)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust)

Builds a directed graph of usernames and finds strongly connected communities using the `petgraph` crate.

</td>
</tr>
</table>

---

## Currently Building

A persistent, distributed **task queue in Rust** — Postgres-backed, crash-recoverable, with retries and a dead-letter queue. It's my main project right now; the design notes and progress live in its repo. Next up: a small vector store for embeddings.

---

## Experience

**Technology Associate** · [Innovations for Poverty Action, Kenya](https://www.poverty-action.org/) · 2018 – Present

- Keep production systems running for 200+ staff across East Africa
- Automated deployments with GitHub Actions and container workflows, cutting release time and manual steps
- Built Prometheus and Grafana monitoring that surfaces incidents faster and shortens time-to-fix
- Run network infrastructure, endpoint security, and day-to-day IT service delivery

---

## GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=ThuoBrian&show_icons=true&theme=tokyonight&count_private=true&hide_border=true" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ThuoBrian&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" />

</div>

---

<div align="center">

*Open to Rust and Python backend roles and IT / infrastructure engineering — remote-friendly, based in Nairobi (UTC+3).*

</div>
