<div align="center">

# Keerthana Bantu

### AI Engineer @ VCMx Exchange · ML Researcher · Agentic AI Builder

*I build AI systems that perceive, reason, and act, and I engineer them to be safe, testable, and ready for production.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square)](https://www.linkedin.com/in/keerthana-b-b546271a6/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:imwannabebk@gmail.com)
[![Location](https://img.shields.io/badge/Toronto%2C%20Canada-0078D4?style=flat-square&logo=googlemaps&logoColor=white)](https://www.google.com/maps/place/Toronto)

<sub><a href="https://www.linkedin.com/in/bantu-keerthana-b546271a6">linkedin.com/in/bantu-keerthana-b546271a6</a></sub>

</div>

---

## About Me

I'm an **AI Engineer** with a Master of Applied Computing from **Wilfrid Laurier University**. My work sits where **perception, language, and autonomous decision-making** meet. I'm most interested in the step from a model that predicts to a system that reasons, plans, and acts, and in making that step reliable enough to trust.

- **Today:** Building clinical triage AI at **VCMx Exchange**, with privacy-preserving inference, deterministic safety layers, and local LLMs
- **Research:** LLM-guided Vision-and-Language Navigation, combining GPT-4, BLIP, YOLO, and reinforcement learning on the R2R benchmark
- **Interests:** Agentic AI · Multi-Agent Systems · RAG · Responsible AI in healthcare · Embodied AI
- **Philosophy:** A system isn't finished until it's tested, observable, and safe when it fails
- **Based in:** Toronto, Ontario, Canada

---

## Currently

```text
  Working as an AI Engineer at VCMx Exchange: clinical triage AI with safety-first design
  Open-sourcing my VLN research pipeline (NavGPT + PPO + Spatial Episodic Memory)
  Exploring multi-agent reasoning for embodied navigation and guardrails for small local LLMs
```

> **Open to:** research collaborations, conversations about agentic and healthcare AI, and future opportunities

---

## Experience

| Role | Organization | Highlights |
|---|---|---|
| **AI Engineer** *(Jun 2026 – Present)* | VCMx Exchange | Shipped a clinical triage pipeline in Go with local LLMs, a PHI-safe gRPC architecture, and 48 automated safety tests |
| **Research Assistant, Vision & Language Navigation** *(Apr 2025 – Apr 2026)* | Wilfrid Laurier University | Designed a full LLM + perception + RL navigation agent, reaching 83.3% success rate on R2R val-unseen |
| **Data Scientist Intern** *(Apr 2024 – Oct 2024)* | Ascent Group, Bangalore | Automated data ingestion pipelines, improving processing efficiency by 60% |

---

## Industry Work: Safety-First Clinical AI at VCMx Exchange

In healthcare triage, a confident wrong answer is worse than no answer. My work at VCMx focuses on an AI pipeline that stays useful while remaining safe and auditable.

- **Local, lightweight models:** The pipeline is written in **Go** and runs **MedGemma 4B** through **Ollama**. A **Qwen 3 4B router** decides when guideline retrieval is allowed, and deterministic safety rules decide what the model is never allowed to do.
- **Privacy by architecture:** The AI layer only ever sees **de-identified clinical context**, passed over **gRPC/Protobuf**, so PHI is kept out of the inference path.
- **Layered guardrails:** Structured output validation, non-clinical explanation filtering, and **mandatory practitioner review** keep a clinician in the loop.
- **Tested like critical software:** **48 automated tests** cover safety escalation, red-flag detection, and crisis response.
- **Choosing evidence over hype:** I first built RAG on **Postgres + pgvector + nomic-embed-text**. After evaluating the limits of vector search for triage, I replaced it with **tool-gated in-memory catalog lookup**, which is more predictable and easier to audit.

`Go` `MedGemma` `Ollama` `Qwen 3` `gRPC` `Protobuf` `Postgres` `pgvector` `RAG`

*Proprietary work, described at a high level.*

---

## Research: Teaching Agents to Navigate with Language

### Vision-and-Language Navigation (VLN)

Can an LLM act as the planning brain of an embodied agent, one that follows plain-English directions through a real 3D indoor space it has never seen? That is the question behind my research at Wilfrid Laurier University.

- **LLM as planner:** GPT-4-turbo reasons over Matterport3D scenes through a NavGPT-style framework
- **Fused perception:** BLIP captions, YOLOv8 detections, and MiDaS depth are combined at every viewpoint
- **6-layer guardrail system:** Pre-flight validation, smart fallback, dead-end guard, cycle detection, multi-stage escape, and partial credit keep the agent from getting stuck
- **Planner-assisted and planner-free strategies** reduce repeated failure loops in cluttered scenes
- **New evaluation metrics:** TCWPO, IGD/IGD-CD, DQI, VCEQ, and PCEDS, reported alongside standard SR and SPL
- **Result:** **83.3% success rate** on a 12-episode R2R val-unseen subset

*Wilfrid Laurier University · Apr 2025 – Apr 2026*

---

## Tech Stack

<table>
  <tr>
    <td valign="top" width="50%">
      <b>Languages & Core</b><br><br>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white&labelColor=3776AB" />
      <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" />
      <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
      <img src="https://img.shields.io/badge/gRPC%20%2F%20Protobuf-244C5A?style=flat-square" />
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
      <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" />
    </td>
    <td valign="top" width="50%">
      <b>Machine Learning & AI</b><br><br>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
      <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" />
      <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" />
      <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
      <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />
      <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td valign="top">
      <b>LLMs · RAG · Agentic AI</b><br><br>
      <img src="https://img.shields.io/badge/OpenAI%20GPT--4-412991?style=flat-square" />
      <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square" />
      <img src="https://img.shields.io/badge/MedGemma-4285F4?style=flat-square&logoColor=white" />
      <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
      <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logoColor=white" />
      <img src="https://img.shields.io/badge/RAG%20Pipelines-6B7280?style=flat-square&logoColor=white" />
      <img src="https://img.shields.io/badge/Agentic%20RAG-6B7280?style=flat-square&logoColor=white" />
      <img src="https://img.shields.io/badge/ReAct%20%2F%20ReWOO-6B7280?style=flat-square&logoColor=white" />
      <img src="https://img.shields.io/badge/Multi--Agent%20Systems-6B7280?style=flat-square&logoColor=white" />
      <img src="https://img.shields.io/badge/Prompt%20Engineering-6B7280?style=flat-square&logoColor=white" />
    </td>
    <td valign="top">
      <b>Computer Vision</b><br><br>
      <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" />
      <img src="https://img.shields.io/badge/YOLOv8-00B4D8?style=flat-square&logoColor=white" />
      <img src="https://img.shields.io/badge/BLIP-0EA5E9?style=flat-square&logoColor=white" />
      <img src="https://img.shields.io/badge/CLIP-7C3AED?style=flat-square&logoColor=white" />
      <img src="https://img.shields.io/badge/MiDaS-10B981?style=flat-square&logoColor=white" />
      <img src="https://img.shields.io/badge/DeepSORT-059669?style=flat-square&logoColor=white" />
      <img src="https://img.shields.io/badge/Object%20Detection-1D9E75?style=flat-square&logoColor=white" />
      <img src="https://img.shields.io/badge/Depth%20Estimation-0F6E56?style=flat-square&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td valign="top">
      <b>Data Engineering, Databases & Cloud</b><br><br>
      <img src="https://img.shields.io/badge/Postgres%20%2B%20pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white" />
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
      <img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" />
      <img src="https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white" />
      <img src="https://img.shields.io/badge/ETL%20Pipelines-6B7280?style=flat-square&logoColor=white" />
      <img src="https://img.shields.io/badge/CI%2FCD-6B7280?style=flat-square&logoColor=white" />
      <img src="https://img.shields.io/badge/Feature%20Engineering-6B7280?style=flat-square&logoColor=white" />
    </td>
    <td valign="top">
      <b>BI & Visualization</b><br><br>
      <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" />
      <img src="https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white" />
      <img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=matplotlib&logoColor=white" />
      <img src="https://img.shields.io/badge/KPI%20Reporting-6B7280?style=flat-square&logoColor=white" />
      <img src="https://img.shields.io/badge/EDA-6B7280?style=flat-square&logoColor=white" />
    </td>
  </tr>
</table>

---

## Featured Projects

### Clinical Triage AI Pipeline · *VCMx Exchange*
A safety-first triage system built in Go. It pairs small local models (MedGemma 4B, Qwen 3 4B router) with deterministic rules, de-identified inputs over gRPC/Protobuf, enforced practitioner review, and 48 automated safety tests.

`Go` `MedGemma` `Ollama` `Qwen 3` `gRPC` `Protobuf` `pgvector` `RAG`

---

### LLM-Guided Vision-and-Language Navigation · *Research*
An end-to-end agent that follows natural-language directions through indoor Matterport3D environments. GPT-4-turbo plans, BLIP + YOLOv8 + MiDaS perceive, a PPO executor acts, and Spatial Episodic Memory plus a 6-layer guardrail system keep it on course. **83.3% SR, 0.607 SPL** on R2R val-unseen.

`GPT-4` `BLIP` `YOLOv8` `MiDaS` `PPO` `SLAM` `Matterport3D` `R2R` `Python`

---

### ML-Powered Academic Research Retrieval System
A RAG pipeline that uses SciBERT embeddings and Elasticsearch to find, rank, and summarise academic papers. Embedding-based retrieval beats keyword search on domain-specific queries, and summaries are checked for factual consistency and source alignment.

`RAG` `SciBERT` `Elasticsearch` `Transformers` `PyTorch` `TensorFlow` `NLP`

---

### Real-Time Sports Analytics Pipeline
Tracks players in live match footage with YOLOv8 + DeepSORT, derives speed, acceleration, distance, and zone-occupancy metrics, and forecasts tactical positioning with LSTMs. **93% zone prediction accuracy.**

`YOLOv8` `DeepSORT` `LSTM` `OpenCV` `Computer Vision` `Python`

---

### RAG Knowledge Assistant
A complete GenAI application covering preprocessing, chunking, embeddings, semantic search, and source-aware answer generation, designed to cut down unsupported answers.

`Python` `RAG` `LLMs` `Embeddings` `Semantic Search` `Prompt Engineering`

---

### Anomaly Detection in Firewall Traffic
Finds suspicious behaviour in network logs using Isolation Forest, Gradient Boosting, and Graph Neural Networks, producing monitoring signals for security analysis.

`PyTorch` `GNN` `Scikit-learn` `Isolation Forest` `Network Analysis`

---

## Let's Connect

I enjoy talking about agentic systems, embodied AI, and what it takes to put AI into high-stakes domains like healthcare. If that sounds like your kind of conversation, say hello.

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0077B5?style=flat-square)]([https://www.linkedin.com/in/bantu-keerthana-b546271a6](https://www.linkedin.com/in/keerthana-b-b546271a6/)
[![Email](https://img.shields.io/badge/Send%20me%20an%20Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:imwannabebk@gmail.com)

---

<div align="center">
  <i>From <a href="https://github.com/keerthana-bantu">keerthana-bantu</a> · always learning, always building</i>
</div>
