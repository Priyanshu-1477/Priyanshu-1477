<!-- Profile README for Priyanshu-1477/Priyanshu-1477 -->
<!-- Animated images use Capsule Render and Readme Typing SVG. -->

<div align="center">

<img
  width="100%"
  alt="Priyanshu Raj — Backend, Systems, AI"
  src="https://capsule-render.vercel.app/api?type=venom&amp;height=260&amp;color=0:22d3ee,50:8b5cf6,100:f472b6&amp;text=PRIYANSHU%20RAJ&amp;fontSize=64&amp;fontColor=ffffff&amp;stroke=22d3ee&amp;strokeWidth=1&amp;animation=fadeIn&amp;fontAlignY=48&amp;desc=BREAK%20THINGS.%20TRACE%20EVERYTHING.%20BUILD%20BETTER.&amp;descSize=15&amp;descAlignY=68"
/>

<a href="https://github.com/Priyanshu-1477">
<img alt="Building backends. Distributing work. Investigating failures. Asking why it broke." src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;weight=600&amp;size=23&amp;duration=2600&amp;pause=900&amp;color=22D3EE&amp;center=true&amp;vCenter=true&amp;width=800&amp;height=60&amp;lines=Building+backends.+Distributing+work.;Making+AI+agents+investigate+failures.;Following+the+request+down+the+stack.;If+it+broke%2C+I+want+to+know+why." />
</a>

**CSE @ BIT Mesra · Class of 2028 · India**

<a href="https://www.linkedin.com/in/priyanshu-raj-a5538333b/"><img alt="LinkedIn" src="https://img.shields.io/badge/LET'S_CONNECT-0A66C2?style=for-the-badge&amp;logo=linkedin&amp;logoColor=white" /></a>
<a href="mailto:prmahatha@gmail.com"><img alt="Email Priyanshu" src="https://img.shields.io/badge/DROP_A_MESSAGE-8B5CF6?style=for-the-badge&amp;logo=gmail&amp;logoColor=white" /></a>
<a href="https://github.com/Priyanshu-1477?tab=repositories"><img alt="Explore repositories" src="https://img.shields.io/badge/OPEN_THE_LAB-0891B2?style=for-the-badge&amp;logo=github&amp;logoColor=white" /></a>

<br /><br />

**The endpoint works. Cool. What happens when the worker dies?**

</div>

## 🧑‍💻 `whoami`

Hey, I'm **Priyanshu** — a B.Tech CSE student at **Birla Institute of Technology, Mesra**, usually somewhere between a backend service, a Linux terminal, and a question that starts with *“but how does that actually work?”*

I build practical software to understand the machinery behind it: **APIs, workers, queues, databases, networks, and AI agents that can use tools**. I'm especially interested in what happens when these pieces have to cooperate—and when they stop cooperating.

My interests run through **backend engineering, distributed systems, Linux, networking, cybersecurity, and applied AI/ML**. I like projects with enough moving parts to force real design decisions, then understanding them well enough to explain every important one.

```yaml
priyanshu:
  education: B.Tech CSE, BIT Mesra
  graduating: 2028
  operating_system: Zorin OS / Linux
  home_base: backend + distributed systems
  side_quests: networking, cybersecurity, AI/ML
  learning_style: build it → inspect it → understand it
  favorite_question: "What happens when this fails?"
  looking_for: internships + interesting engineering collaborations
```

<div align="center">
<img alt="Build, break, trace, fix, repeat" src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;size=18&amp;duration=2200&amp;pause=600&amp;color=A78BFA&amp;center=true&amp;vCenter=true&amp;width=700&amp;height=48&amp;lines=%24+build+%26%26+break+%26%26+trace+%26%26+fix;%3E+repeat+until+the+design+makes+sense." />
</div>

## ⚡ The current lab

### 🕵️ Backend Incident Investigator

**An AI agent with a debugging job.** · In progress

I'm building an agent to investigate backend failures by gathering evidence and deciding what to check next.

The intended workflow: inspect service health, read application logs, check configuration and connectivity, explain the likely cause with evidence, propose a fix, and verify recovery after an approved action. Tool calls and their outcomes should leave a visible execution trail.

**Demo target:** an API fails because its database hostname is wrong—even though PostgreSQL itself is healthy. The interesting part is getting the agent to establish that distinction.

`Python` `FastAPI` `Docker` `PostgreSQL` `LLM tool calling`

[**Enter the investigation →**](https://github.com/Priyanshu-1477/backend-incident-investigator)

---

### ⚙️ Distributed Automation Platform

**Give the workers work. Know when they disappear.** · Ongoing build

An orchestrator–worker architecture with worker registration, heartbeat monitoring, and distributed task assignment. Celery and Redis handle asynchronous execution and retries; PostgreSQL keeps persistent state.

This is where I explore the questions behind background jobs: who owns a task, how workers report their health, and how execution state survives beyond a single process.

`FastAPI` `Celery` `Redis` `PostgreSQL` `Docker`

---

### 🧠 Text-to-SQL

**Human question in. Database query out.** · Exploratory project

Exploring how natural-language questions can become SQL queries. I'm interested in the engineering around the model: schema context, query correctness, and how to evaluate whether the result actually answers the question.

**Current design question:** where to begin with a pretrained model, and when fine-tuning would be justified.

`NLP` `SQL` `LLMs` `Evaluation`

---

### 🕸️ KGGen News Pilot

**Different headlines. Same event. What happens to the graph?** · Research pilot

A news-to-knowledge-graph experiment investigating extraction, clustering, duplicate information, and their implications for question answering.

The pilot corpus contains **16 reviewed articles across three events**. The extraction and evaluation work is ongoing; conclusions will come from completed runs and evidence.

`Python` `KGGen` `Knowledge graphs` `Deduplication` `QA evaluation`

<div align="center">

[**Browse the rest of the lab ↗**](https://github.com/Priyanshu-1477?tab=repositories)

</div>

## 🛠️ The toolbox

<div align="center">

<img alt="Python, C, C++, JavaScript, TypeScript, FastAPI, Django, Flask, Node.js, Express, PostgreSQL, MongoDB, Redis, Docker, Git, Linux, React, and OpenCV" src="https://skillicons.dev/icons?i=python,c,cpp,js,ts,fastapi,django,flask,nodejs,express,postgres,mongodb,redis,docker,git,linux,react,opencv&amp;perline=9&amp;theme=dark" />

</div>

<br />

| Where I'm working | What I use |
| :--- | :--- |
| Backend & APIs | FastAPI · Django · Flask · Node.js · Express · REST |
| State & background work | PostgreSQL · MongoDB · Redis · Celery |
| Systems & workflow | Linux · Docker · Git · shell scripting |
| AI, retrieval & vision | BGE-M3 · FAISS · OpenCV · model training & evaluation |
| Interfaces | React · JavaScript · TypeScript |

## 🔬 What keeps me curious

- **Distributed systems:** task ownership, retries, worker health, and failure recovery.
- **Linux & networking:** processes, sockets, service communication, and what the OS is doing underneath.
- **Backend infrastructure:** database behavior, caching, concurrency, and observability.
- **Agentic AI:** tool selection, evidence gathering, and checking whether an action actually helped.

## 🤝 Let's build something worth debugging

I'm looking for **internship opportunities in backend engineering, infrastructure, and developer tools**. I'd also like to collaborate on systems projects or practical AI tools with clear engineering problems.

Got a backend problem, an interesting system, or a suspiciously silent worker? Let's talk.

<div align="center">

<a href="mailto:prmahatha@gmail.com"><img alt="Email prmahatha@gmail.com" src="https://img.shields.io/badge/prmahatha%40gmail.com-111827?style=for-the-badge&amp;logo=gmail&amp;logoColor=22D3EE" /></a>
<a href="https://www.linkedin.com/in/priyanshu-raj-a5538333b/"><img alt="Connect with Priyanshu Raj on LinkedIn" src="https://img.shields.io/badge/PRIYANSHU_RAJ-111827?style=for-the-badge&amp;logo=linkedin&amp;logoColor=A78BFA" /></a>

<br /><br />

<img alt="Still learning. Still building. Still asking why." src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;size=17&amp;duration=2800&amp;pause=1200&amp;color=22D3EE&amp;center=true&amp;vCenter=true&amp;width=700&amp;height=45&amp;lines=Still+learning.+Still+building.+Still+asking+why.;See+you+in+the+logs." />

<img width="100%" alt="Animated purple and cyan footer" src="https://capsule-render.vercel.app/api?type=waving&amp;color=0:06b6d4,50:7c3aed,100:050816&amp;height=130&amp;section=footer&amp;animation=twinkling" />

</div>
