<h2>Hi, I'm Sandeep 👋</h2>

<p>
  <a href="https://sandeepraju.dev"><img src="https://img.shields.io/badge/Portfolio-sandeepraju.dev-24614b?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/sandeepkraju-softwareengineer/"><img src="https://img.shields.io/badge/LinkedIn-Sandeep_Konduru_Raju-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:sandeep.kondururaju@gmail.com"><img src="https://img.shields.io/badge/Email-sandeep.kondururaju@gmail.com-555?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Dublin-Available_now-2e9b6a?style=flat-square" alt="Dublin, available now" />
</p>

I'm a backend and AI engineer based in Dublin. I spent 4 years at Manhattan Associates building the Java and Spring Boot services behind a warehouse platform that handles 10M+ transactions a day, for retail clients in Europe and the US. I was on call for it too, so I care a lot about things not breaking at 3am.

Near the end of that job I helped build MAKI, an internal multi-agent coding tool, and built the evaluation harness that checked its output before production. That got me into AI properly. I'm now finishing an MSc in Artificial Intelligence at National College of Ireland (Dec 2026).

### 📊 Work in numbers

| 10M+ | 99.5% | 15K+ | 100+ |
|:---:|:---:|:---:|:---:|
| transactions a day | availability | requests a second | production incidents fixed |

### 🛠️ What I'm building

**🚌 [Dublin Transit AI](https://github.com/SandeepKonduruRaju/Dublin-Transit-AI)** (live: [try it](https://dublin-transit-ai.swedencentral.cloudapp.azure.com))

Ask Dublin bus questions in plain English, like "is the 39A running late?" or "how reliable was route 15 this week?". A poller saves the NTA live feed to Postgres every minute, FastAPI tools join it to the national timetable, and a LangGraph agent with Claude answers only from those tools. A 100 question eval with a 100% safety gate runs in GitHub Actions, so the agent never makes up routes. Runs on Azure with Docker Compose and Caddy.

**🔎 [AI Incident Investigation Platform](https://github.com/SandeepKonduruRaju/ai-incident-platform)** (v1.0.0: [demo](https://incident.sandeepraju.dev))

Helps engineers find the root cause of a production incident faster. A Spring Boot API sends events through an outbox to Kafka, and a Python LangGraph worker runs hybrid RAG with Claude and returns a cited root cause, or says it isn't sure. On a 28 case eval: 89% root cause accuracy and 100% valid citations.

### 🧰 Tools I use

<p>
  <img src="https://skillicons.dev/icons?i=java,spring,python,fastapi,go,mysql,postgres,redis,kafka,rabbitmq&theme=light" alt="Backend and data" /><br />
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,terraform,aws,jenkins,githubactions,linux,grafana,prometheus,git&theme=light" alt="Cloud and delivery" />
</p>

AI: LangChain, LangGraph, RAG, pgvector, MCP, agent evaluation
