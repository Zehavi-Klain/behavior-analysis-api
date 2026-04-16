# 🧠 Behavior Analysis System
The full system is private. This repository showcases key parts of the implementation.

## 🚀 Live Demo

🔗 https://behavioranalystproject-1.onrender.com/home

---

## 📌 Overview

A full-stack platform for behavior analysts that combines patient management, session tracking, data analysis, and AI-driven insights into a unified workflow.
---

## 🧩 Key Features

* AI-assisted behavioral scenario analysis (LLM integration)
* Aggregated insights (per session & global)
* Patient management (profiles, sessions, summaries)  
* Form management (upload, view)  
* Parent access (progress tracking and summaries)  

---

## 🏗️ Architecture

Client (React) → API (ASP.NET Core) → Services → Repositories → Data Layer (SQL)

---

## 🖥️ Client

React-based interface for:

* Scenario input
* Results visualization
* Insight exploration

> Client code is not included in this repository.

---

## 🧠 Core Logic

Focuses on:

* Data processing and aggregation
* Distribution calculations
* Session-level and global analysis


---

## 🤖 AI Integration

LLMs (OpenAI / Gemini) are used for:

* Interpreting free-text scenarios
* Behavior classification
* Structured output generation

> In this repo, AI calls are simplified to highlight system design.

---

## 🔍 Future Work (RAG)

Planned enhancement using Retrieval-Augmented Generation:

* Retrieval of similar historical cases
* Context-aware AI responses
* Improved accuracy via data grounding

Tech direction:

* Vector DB (e.g., Pinecone / FAISS)
* Embeddings-based search
* Hybrid AI + data approach

---

## 🛠️ Tech Stack

* Backend: ASP.NET Core
* Frontend: React
* Database: SQL Server
* AI: OpenAI / Gemini
* Architecture: Layered

---

## 🔐 Scope

This repository includes selected backend components.
The full system is private and under active development.

---

## 👩‍💻 Author

Zehava Klain
Full Stack Developer
