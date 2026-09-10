<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e3a5f,100:0d1b2a&height=200&section=header&text=Zakaria%20Baouali&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Java%20Backend%20Developer%20%C2%B7%20Spring%20Boot%20%C2%B7%20System%20Design&descAlignY=58&descSize=18" width="100%"/>

<a href="https://twitter.com/baouali_zakaria">
  <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" />
</a>

</div>

<br/>

## 🧠 About Me

I build backend systems the way they'd be built at scale — starting from domain modeling and
architecture decisions, not just code. My approach to every project is the same: understand the
domain, design the architecture deliberately *(event storming, bounded contexts, C4 diagrams,
documented decisions)*, then write the code — not the other way around.

Right now I'm applying that process to something more demanding than a typical CRUD app.

<br/>

## ⚡ Currently Building

<div align="center">
<h3>Athena — a trading operating system</h3>
</div>

Athena watches the market, turns raw data into trade signals, manages risk, and executes trades
with a broker — with minimal manual work from the trader. Built as **11 services, each with a
single responsibility.**

<table width="100%">
<tr>
<td valign="top" width="50%">

**📡 Data Pipeline**
<br/><sub>gets raw market data in, stores it, makes it usable</sub>

| Service | Responsibility |
|---|---|
| `Connection` | Talks to external APIs, receives market data |
| `Data` | Reads and writes all persistent data |
| `Storage` | File/object storage — records, logs, backups |
| `Caching` | Fast, temporary storage for hot data |
| `Processing` | Turns raw data into usable features |

</td>
<td valign="top" width="50%">

**🎯 Intelligence & Decisioning**
<br/><sub>turns features into trade decisions</sub>

| Service | Responsibility |
|---|---|
| `Signal Generation` | AI-agent powered — produces trade decisions |
| `Risk` | AI-agent powered — sizing, real-time monitoring |

**⚙️ Trading**

| Service | Responsibility |
|---|---|
| `Execution Engine` | Places & manages orders across brokers |

</td>
</tr>
</table>

> Signal Generation decides **what** it wants to do, Risk decides **whether and how much** it's
> allowed to do, and Execution decides **how** to actually place it with the broker.

**🧩 Platform / Supporting Services**
<br/><sub>standard services every product needs, independent of the trading logic</sub>

`Authentication` · `Payment` · `Notification`

<div align="center">
<br/>

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)

</div>

<br/>

> *Every service's architecture is designed before it's built — requirements, event storming,
> bounded contexts, C4 diagrams, and documented decisions come first.*

<br/>

## 🛠️ Tech Stack

<table width="100%">
<tr>
<td valign="top" width="25%">

**Languages**
<br/><br/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" width="36" height="36"/>&nbsp;
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/spring/spring-original.svg" width="36" height="36"/>&nbsp;
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="36" height="36"/>&nbsp;
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="36" height="36"/>

</td>
<td valign="top" width="25%">

**Databases**
<br/><br/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" width="36" height="36"/>&nbsp;
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" width="36" height="36"/>&nbsp;
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original.svg" width="36" height="36"/>&nbsp;
<img src="https://www.vectorlogo.zone/logos/neo4j/neo4j-icon.svg" width="36" height="36"/>

</td>
<td valign="top" width="25%">

**Messaging & Real-Time**
<br/><br/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/apachekafka/apachekafka-original.svg" width="36" height="36"/>

</td>
<td valign="top" width="25%">

**Infrastructure**
<br/><br/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" width="36" height="36"/>&nbsp;
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" width="36" height="36"/>

</td>
</tr>
</table>

<br/>

## 📊 GitHub Stats

<div align="center">
<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=zakariyaabaouali&hide_border=true" />

</div>

<br/>

## 🎌 Fun Fact

Big anime fan — **Solo Leveling** is my favorite. Watching a protagonist go from E-rank to
S-rank through relentless, deliberate leveling up is basically how I think about learning
systems architecture, if I'm honest.

<br/>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1b2a,100:1e3a5f&height=100&section=footer"/>

✨ *Always open to collaboration and new opportunities* ✨

</div>
