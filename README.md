<div align="center">

# Hi, I'm Zakariyaa Baouali 👋

### Java Backend Developer · Spring Boot · System Design

I build backend systems the way they'd be built at scale — starting from domain modeling and
architecture decisions, not just code. Currently deep in **Athena**, a trading operating system
I'm designing and building from the ground up.

[![Twitter](https://img.shields.io/badge/-Twitter-1DA1F2?style=flat-square&logo=twitter&logoColor=white)](https://twitter.com/baouali_zakaria)
[![Instagram](https://img.shields.io/badge/-Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://instagram.com/zak_maroki)

</div>

---

## 🧠 About Me

I'm a backend developer focused on **Spring Boot**, distributed systems, and software
architecture. My approach to every project starts the same way: understand the domain, design
the architecture deliberately (event storming, bounded contexts, C4 diagrams, ADRs), *then*
write the code — not the other way around.

Right now I'm applying that process to something more demanding than a typical CRUD app: a
trading system, where correctness, concurrency, and latency actually matter.

---

## ⚡ Currently Building — Athena

**A trading operating system.** It watches the market, turns raw data into trade signals,
manages risk, and executes trades with a broker — with minimal manual work from the trader.

Built as **11 services, each with a single responsibility.**

**Data Pipeline** — gets raw market data in, stores it, and turns it into something usable
- `Connection Service` — talks to external APIs, receives incoming market data
- `Data Service` — talks to the database; reads and writes all persistent data
- `Storage Service` — handles file/object storage (historical records, logs, backups)
- `Caching Service` — keeps frequently-used data in fast, temporary storage
- `Processing Service` — converts raw data into mathematical features the rest of the system uses

**Intelligence & Decisioning** — turns features into actual trade decisions
- `Signal Generation Service` — AI-agent-powered; turns tracked features into trade decisions
- `Risk Service` — AI-agent-powered; sizing plus real-time tracking of open trades

**Trading**
- `Execution Engine` — sends and manages orders with the broker; built to integrate with
  multiple brokers, not just one

> Signal Generation decides *what* it wants to do, Risk decides *whether and how much* it's
> allowed to do, and Execution decides *how* to actually place it with the broker.

**Platform / Supporting Services** — standard services every product needs, independent of the
trading logic
- `Authentication Service` — user identity and access
- `Payment Service` — billing and payments
- `Notification Service` — alerts and updates to users

**Athena's stack:** `Spring Boot` · `PostgreSQL` · `Redis` · `GraphQL`

> *Every service's architecture is designed before it's built — requirements, event storming,
> bounded contexts, C4 diagrams, and documented decisions (ADRs) come first.*

---

## 🛠️ Tech Stack

**Languages & Frameworks**

![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Databases**

![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Neo4j](https://img.shields.io/badge/-Neo4j-008CC1?style=flat-square&logo=neo4j&logoColor=white)

**Messaging & Real-Time**

![Kafka](https://img.shields.io/badge/-Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

**Infrastructure & Tools**

![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

## 📊 GitHub Stats

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=zakariyaabaouali&show_icons=true&locale=en&theme=default" alt="zakariyaabaouali stats" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=zakariyaabaouali&show_icons=true&locale=en&layout=compact" alt="zakariyaabaouali top langs" height="165"/>
</p>

<p align="left">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=zakariyaabaouali" alt="zakariyaabaouali streak stats" />
</p>

---

## 🎌 Fun Fact

Big anime fan — **Solo Leveling** is my favorite. (Watching a protagonist go from E-rank to
S-rank through relentless, deliberate leveling up is basically how I think about learning
systems architecture, if I'm honest.)

---

<div align="center">

✨ *Always open to collaboration and new opportunities* ✨

</div>
