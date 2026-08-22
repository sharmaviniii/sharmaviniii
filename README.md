<h1 align="center"> Hi there, I'm <a href="https://www.linkedin.com/in/vanshika-sharma-435678270/">Vanshika Sharma</a> </h1>

<!--
**sharmaviniii/sharmaviniii** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:
- 🤔 I’m looking for help with an
- 💬 Ask me about ...
-->
<img src="https://www.pngmart.com/files/23/Coding-PNG-Clipart.png" min-width="200px" max-width="200px" width="250px" align="right">

I like building things that make me stop and think, **“Why does this have to work this way?”**

A Computer Science & Engineering Graduate (GPA - 7.44; May'26), I've worked across software engineering, cloud technologies, artificial intelligence, and data-driven applications, transforming ideas into scalable, production-ready systems.

---

## ✨ A little about how I build

I started with the usual things you'd expect from a Computer Science student — DSA, databases, networks, Java, C++, Python. But somewhere along the way, I became more interested in what happens **after** the code works.

What happens when the network disappears? <br> What happens when an AI system isn't sure about its answer? <br> What happens when thousands of packets need to be processed at the same time? <br> What happens when a meeting contains an important decision that nobody remembers three weeks later? <br>
Those questions are what usually send me down a rabbit hole. And that's probably the best way to describe my GitHub: <br>

**a collection of rabbit holes that turned into working systems.**

### 🌐 A little more of my work - **[ Visit my portfolio](https://vanshika-s-portfolio.ai.studio/)** · **[👗 Explore the TrendÉvo case study](https://trendevocasestudy.ai.studio/)**

---


## 💼 Industry Experience

### 👁️ FaceVerify POC

During my time at Lipman Family Farms, I got to work on something very different from my university projects. 
An attendance card tells you **what card was scanned**. But what if you also need to know **who actually scanned it?** 
I worked on a production-ready Azure module that used facial recognition to verify employee identities during attendance scans. The workflow became: 

**card scan → Azure Blob Storage → Blob-triggered Function → Face API → confidence decision → audit / supervisor notification**

The interesting constraint was that verification couldn't become the thing slowing attendance down.That experience taught me a different side of software engineering - production systems aren't just about getting the happy path right. They're about what happens when the image is bad, the face isn't detected, confidence is low, or something goes wrong. And sometimes the best system is the one the user barely notices.

Stack - C#, .NET, Azure Functions, Azure Blob Storage, Azure Cognitive Services, REST APIs, Event-Driven Architecture

---

## 🛠 Things I've built

### 🧠 IntelMeet

Meetings produce an absurd amount of information. Decisions. Action items. Risks. Follow-ups. And then, somehow, everyone forgets half of it.

So I built **IntelMeet** — a meeting intelligence platform that turns transcripts into something you can actually use. It started as an AI idea, but quickly became a lesson in building software around AI: authentication, workspaces, APIs, databases, vector search, testing, deployment, and all the unglamorous pieces that make an application feel like a real product. **15+ APIs. 70+ automated backend tests. TXT/PDF/DOCX ingestion. Semantic search.** The interesting part wasn't getting an LLM to summarize a meeting. It was figuring out how to build everything around it so the system could be trusted.

---

### 💳 MeshPay

What if you needed to send a payment when the internet wasn't available? That question became **MeshPay**. Instead of treating connectivity as something we could always assume, I explored an offline-first payment system where transactions could travel through a simulated mesh network and eventually reach a connected bridge. That meant thinking about things that sound very different from a normal payment app: **encryption, replay attacks, duplicate transactions, concurrency, packet routing and exactly-once settlement.** It became one of those projects where the original idea was simple and the engineering rabbit hole was *not*.

---

### 🔎 VectorForge AI

I wanted to understand something I was constantly using without really understanding deeply: **How does semantic search actually work underneath?** So I stopped using a vector database and decided to build one. VectorForge implements **Brute Force, KD-Tree and HNSW indexing in C++**, then connects that retrieval layer to a local RAG pipeline using Llama 3.2 and Nomic embeddings. The goal wasn't just to make another RAG app.
It was to understand what happens between:

`"I asked a question"` and `"these are the vectors we decided were relevant."`

That curiosity led me much deeper into search algorithms, embeddings, similarity metrics and performance optimization.

---

### 🌐 NetSentry

This one started with another question: **What can you actually learn from network traffic when you can't simply read the contents?**
NetSentry is my multi-threaded Deep Packet Inspection engine in C++. It parses traffic, tracks connections, extracts TLS SNI information and identifies applications while running packet processing through a concurrent pipeline. It can handle **10,000+ queued packets** and identify **15+ internet services**.
Building it taught me something I hadn't fully appreciated before: sometimes performance isn't about making one function faster. Sometimes you have to rethink **how the entire system moves work around.**

---

### 👗 TrendÉvo

And then there's fashion. Which probably looks slightly out of place next to packet inspection and distributed payments. That's exactly why I like it. <br>
TrendÉvo started from a question about how fashion trends are actually predicted — and whether AI could make recommendations feel more personal instead of simply saying *“people who liked this also liked that.”* <br>
I worked on a system combining **trend forecasting, conversational memory, weather intelligence, semantic search and personalized recommendations**. <br>
I also went through research papers and an industry case study before turning those findings into actual product requirements and architecture. It ended up becoming my capstone project and scored **438/450**.<br>
More importantly, it reminded me that good engineering doesn't always start with engineering.
Sometimes it starts with understanding the world you're building for.

**→ [Read the TrendÉvo Case Study](https://trendevocasestudy.ai.studio/)**
---

## 🧠 Areas of Interest

- Software Deveopment
- Backend Engineering
- Artificial Intelligence & Machine Learning
- Cloud Computing & Distributed Systems
- Full-Stack Development
- Project Management

---

## 🧩 Tech stack.

**Languages**

`Python` `Java` `C++` `C#` `JavaScript` `TypeScript` `SQL`

**Backend**

`FastAPI` `Flask` `Spring Boot` `.NET` `REST APIs` `SQLAlchemy` `Spring Data JPA` `JWT` `Swagger/OpenAPI`

**AI / ML**

`Generative AI` `LLMs` `RAG` `Vector Search` `Embeddings` `Semantic Search` `Recommendation Systems` `Computer Vision` `Machine Learning`

**Frontend**

`React` `React 19` `TypeScript` `JavaScript` `HTML` `CSS` `Tailwind CSS`
`Distributed Systems` `Multithreading` `Concurrency` `TCP/IP` `Deep Packet Inspection`

**Databases**

`PostgreSQL` `MongoDB` `MySQL` `SQL Server` `ChromaDB` `FAISS`

**Cloud / DevOps**

`Azure` `Azure Functions` `Azure Blob Storage` `Azure DevOps` `Docker` `Git`

**Software Engineering**  

`Software Design` `Software Architecture` `Data Structures and Algorithms` `Object-Oriented Programming` `Distributed Systems` `Multithreading` `Concurrency` `Software Development Lifecycle` `Unit Testing` `Integration Testing` `Regression Testing` `Debugging` `Code Reviews` `Agile`

**AI-Assisted Development**

`Claude Code` `OpenAI Codex` `Cursor` `Google AI Studio` `Antigravity`


---

## 🤝 Find me beyond GitHub

Want to see the work beyond the code?

**[Portfolio](https://vanshika-s-portfolio.ai.studio/)** · 
**[TrendÉvo Case Study](https://trendevocasestudy.ai.studio/)** · Or just say hi: [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vanshika-sharma-435678270/) [![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:vanshika1310sharma@gmail.com)



<p align="center">
  <i>Still curious. Still building. Still breaking things to understand how they work.</i>
</p>

