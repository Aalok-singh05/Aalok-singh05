yush-jadaun/README.md
Ayush Jadaun
Co-Founder & CTO @ Dreamvator · Building distributed systems, AI infrastructure, and developer tools

Portfolio LinkedIn Email npm

About
I'm a 2nd-year ECE student at MNNIT Allahabad, currently building Dreamvator — aviation stealth startup. I architect and ship full production systems: from distributed job queues and multi-agent orchestration to mobile apps, payment infrastructure, and cloud deployments.

My work sits at the intersection of distributed systems, AI/ML, and systems engineering. I care about building things that are technically rigorous and solve real problems.

Currently: CTO & Co-Founder at Dreamvator (React Native · Node.js · AWS ECS Fargate)
Published: @psyqueue/core on npm and marlos on PyPI
Executive at Computer Coding Club, MNNIT Allahabad
Open to collaboration opportunities in distributed systems, AI infrastructure, and full-stack engineering
Projects
PsyQueue — Micro-Kernel Distributed Job Queue
npm version License: MIT

Plugin-architecture job queue in TypeScript. ~500-line kernel with 20+ plugins covering DAG workflows, Saga compensation, multi-tenancy, circuit breakers, and exactly-once delivery. Outperforms BullMQ via fused ackAndFetch (2 Redis round-trips vs 3), hybrid list + sorted-set dequeue, and hash field packing (13 vs 30 fields per HGETALL). Ships SQLite/Redis/Postgres backends — zero infra to start.

TypeScript Redis PostgreSQL SQLite Node.js

DAIOS — Distributed Autonomous Intelligent Orchestration System
Demo

Multi-agent orchestration system where an Orchestra Agent decomposes tasks and assigns them to specialized Dev, Debug, and Ops agents via a Redis pub/sub message bus. Each agent runs a ReAct loop backed by Gemini 2.0 Flash with vector + session memory. Supports sequential and parallel execution with retry logic and fault-tolerant timeout budgets.

Python Node.js Redis FastAPI Docker Gemini

MarlOS — Multi-Agent Reinforcement Learning Operating System
PyPI Demo

Fully decentralized P2P distributed OS — no central orchestrator. Nodes communicate via ZeroMQ gossip, authenticate with Ed25519 signatures, and self-heal by migrating jobs on failure. Each node runs a PPO agent (25-dim state vector) for cooperative bid/forward/defer decisions. Includes a fairness-aware economic layer (MarlCredits) with progressive taxation and starvation prevention. Built at Hack36 9.0.

Python PyTorch Stable Baselines3 ZeroMQ Docker

TBuddy — Multi-Agent Travel Planning System
PyPI

5 specialized agents (Weather, Events, Maps, Budget, Itinerary) orchestrated via Redis pub/sub with real-time SSE streaming. LangGraph-based stateful planning with MCP architecture. Each agent runs in an isolated Docker container with configurable replicas.

Python FastAPI Redis LangGraph Docker Gemini

Dreamvator — Structured Pilot Training Platform
Website STEALTH AVIATION STARTUP

AllProfanity — Multi-Language Profanity Filter
npm version npm downloads

Zero-dependency profanity filter supporting 9 languages (English, Hindi, Hinglish, Bengali, Tamil, Telugu, French, German, Spanish) including native scripts (Devanagari, Bengali, Tamil, Telugu). 160+ weekly downloads. Customizable word lists, character-level and word-level replacement, built entirely in TypeScript.

TypeScript Node.js npm

Achievements
Competition	Year
🥇	Winner — Hactivate, Botrush 3.0 (Robotics Club, MNNIT)	2025
🥇	Winner — Galactic Heist, Botrush 3.0 (Astronomy Club, MNNIT)	2025
🥇	Winner — Robowars, Botrush 3.0 (Robotics Club, MNNIT)	2025
🥇	Triple Winner — CodeSangam 2025 (DroidRush, Logical Rhythm, ContriHub)	2025
🥇	Winner — AIML Hackathon, Culrav/Avishkar (MNNIT)	2024
🥈	Runner-up — Quinthalon Mock Interview, ES Society (MNNIT)	2024
🏆	2nd Runner-up — DevJam, Weekend of Code (MNNIT)	2025
🏆	10th Place — Hack36 9.0	2025
Stack
Languages     C++  Python  TypeScript  JavaScript  Rust
Frontend      React  React Native  Next.js  Tailwind CSS
Backend       Node.js  Express  FastAPI  PostgreSQL  MongoDB  Redis  Supabase
AI / ML       PyTorch  TensorFlow  LangGraph  Stable Baselines3  Gemini
DevOps        AWS (ECS · RDS · CloudFront)  Terraform  Docker  Nginx
Stats
 
📫 ayushjadaun6@gmail.com · linkedin.com/in/ayush-jadaun-677199311 · ayushjadaun.vercel.app
