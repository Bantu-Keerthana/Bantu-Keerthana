<div align="center">
# Hi, I'm Keerthana
 
### Data & AI Engineer · ML Researcher · Agentic AI Builder
 
*Building production-ready AI systems - from perception pipelines to LLM-powered agents and safety-critical clinical AI*
 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=curved-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bantu-keerthana-b546271a6)
[![Email](https://img.shields.io/badge/Email-D14836?style=curved-square&logo=gmail&logoColor=white)](mailto:imwannabebk@gmail.com)
[![Location](https://img.shields.io/badge/Toronto%2C%20Canada-0078D4?style=curved-square&logo=googlemaps&logoColor=white)](#)
 
</div>
---
 
## About Me
 
I'm a **Data and AI professional** with a Master of Applied Computing from **Wilfrid Laurier University, Waterloo**.
 
My work sits at the intersection of **perception**, **language**, and **autonomous decision-making**. I build systems where models don't just predict, they reason, plan, and act, and where safety and reliability are designed in from the start.
 
- **Industry:** AI Engineer at **VCMx Exchange** - clinical triage AI pipeline in Go with local LLMs, PHI-safe inference, and tool-gated retrieval
- **Research:** Vision-and-Language Navigation using LLMs, BLIP, YOLO, and the R2R dataset
- **Interests:** Agentic AI, Multi-Agent Systems, RAG pipelines, Safe/Responsible AI in healthcare, Embodied AI
- **Approach:** Production-oriented - I care about things that actually run reliably
- Based in Toronto, Ontario, Canada
---
 
## Currently
 
```text
  Open-sourcing the VLN pipeline with NavGPT + PPO + Spatial Episodic Memory
  Exploring multi-agent reasoning for embodied navigation
  Exploring safe, deterministic guardrails around small local LLMs in clinical settings
```
 
> **Open to:** AI/ML engineering roles · research roles · full-time opportunities · research collaborations
 
---
 
## Experience Highlights
 
| Role | Company | Impact |
|---|---|---|
| **AI Engineer** *(Jun – Sep 2026)* | VCMx Exchange | Clinical triage AI pipeline in Go · MedGemma 4B via Ollama · PHI-safe gRPC/Protobuf architecture · 48 automated safety tests |
| **Research Assistant — VLN** *(Apr 2025 – Apr 2026)* | Wilfrid Laurier University | Full LLM + perception + RL navigation pipeline · 83.3% SR |
| **Data Scientist Intern** *(Apr 2024 – Oct 2024)* | Ascent Group, Bangalore | 60% pipeline efficiency gain via automated ingestion |
 
---
 
## Industry Work: Clinical Triage AI @ VCMx Exchange
 
At VCMx Exchange I built and deployed a clinical triage AI pipeline where correctness and safety matter more than cleverness.
 
- **Go-based pipeline** running **MedGemma 4B via Ollama**, with a **Qwen 3 4B router** and deterministic safety rules for tool-gated guideline retrieval
- **PHI-safe inference architecture** - the AI layer only sees de-identified clinical context, passed over **gRPC/Protobuf**
- **Guardrails by design** - structured output validation, non-clinical explanation filtering, and mandatory practitioner review enforcement
- **48 automated tests** covering safety escalation, red-flag detection, and crisis response
- **Evidence-driven design change** - started with a RAG system on **Postgres + pgvector + nomic-embed-text**, then replaced it with tool-gated in-memory catalog lookup after evaluating vector-search limitations for clinical triage
`Go` `MedGemma` `Ollama` `Qwen 3` `gRPC` `Protobuf` `Postgres` `pgvector` `RAG`
 
---
 
## Research Focus
 
### Vision-and-Language Navigation (VLN)
 
My research investigates how LLMs can serve as high-level planners for embodied agents navigating real indoor 3D environments from natural language instructions alone. Key contributions:
 
- **NavGPT integration** - GPT-4-turbo as a reasoning planner over Matterport3D scenes
- **Multi-modal perception** - BLIP captioning + YOLOv8 detection + MiDaS depth fused per viewpoint
- **6-layer guardrail system** - pre-flight validation, smart fallback, dead-end guard, cycle detection, multi-stage escape, partial credit
- **Planner-assisted and planner-free strategies** to reduce repeated failure loops in complex visual scenes
- **Novel metrics** - TCWPO, IGD/IGD-CD, DQI, VCEQ, PCEDS alongside standard SR and SPL
- **83.3% success rate** on a 12-episode R2R val-unseen subset
*Wilfrid Laurier University · Apr 2025 – Apr 2026*
 
---
 
## Tech Stack
 
<table>
  <tr>
    <td valign="top" width="50%">
      <b>Languages & Core</b><br><br>
      <img src="https://img.shields.io/badge/Python-3776AB?style=curved-square&logo=python&logoColor=white&labelColor=3776AB" />
      <img src="https://img.shields.io/badge/Go-00ADD8?style=curved-square&logo=go&logoColor=white" />
      <img src="https://img.shields.io/badge/SQL-4479A1?style=curved-square&logo=mysql&logoColor=white" />
      <img src="https://img.shields.io/badge/gRPC%20%2F%20Protobuf-244C5A?style=curved-square&logo=grpc&logoColor=white" />
      <img src="https://img.shields.io/badge/Git-F05032?style=curved-square&logo=git&logoColor=white" />
      <img src="https://img.shields.io/badge/Docker-2496ED?style=curved-square&logo=docker&logoColor=white" />
      <img src="https://img.shields.io/badge/Jupyter-F37626?style=curved-square&logo=jupyter&logoColor=white" />
    </td>
    <td valign="top" width="50%">
      <b>Machine Learning & AI</b><br><br>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=curved-square&logo=pytorch&logoColor=white" />
      <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=curved-square&logo=tensorflow&logoColor=white" />
      <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=curved-square&logo=scikitlearn&logoColor=white" />
      <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=curved-square&logo=huggingface&logoColor=black" />
      <img src="https://img.shields.io/badge/NumPy-013243?style=curved-square&logo=numpy&logoColor=white" />
      <img src="https://img.shields.io/badge/Pandas-150458?style=curved-square&logo=pandas&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td valign="top">
      <b>LLMs · RAG · Agentic AI</b><br><br>
      <img src="https://img.shields.io/badge/OpenAI%20GPT--4-412991?style=curved-square&logo=openai&logoColor=white" />
      <img src="https://img.shields.io/badge/Ollama-000000?style=curved-square&logo=ollama&logoColor=white" />
      <img src="https://img.shields.io/badge/MedGemma-4285F4?style=curved-square&logoColor=white" />
      <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=curved-square&logo=langchain&logoColor=white" />
      <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=curved-square&logoColor=white" />
      <img src="https://img.shields.io/badge/RAG%20Pipelines-6B7280?style=curved-square&logoColor=white" />
      <img src="https://img.shields.io/badge/Agentic%20RAG-6B7280?style=curved-square&logoColor=white" />
      <img src="https://img.shields.io/badge/ReAct%20%2F%20ReWOO-6B7280?style=curved-square&logoColor=white" />
      <img src="https://img.shields.io/badge/Multi--Agent%20Systems-6B7280?style=curved-square&logoColor=white" />
      <img src="https://img.shields.io/badge/Prompt%20Engineering-6B7280?style=curved-square&logoColor=white" />
    </td>
    <td valign="top">
      <b>Computer Vision</b><br><br>
      <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=curved-square&logo=opencv&logoColor=white" />
      <img src="https://img.shields.io/badge/YOLOv8-00B4D8?style=curved-square&logoColor=white" />
      <img src="https://img.shields.io/badge/BLIP-0EA5E9?style=curved-square&logoColor=white" />
      <img src="https://img.shields.io/badge/CLIP-7C3AED?style=curved-square&logoColor=white" />
      <img src="https://img.shields.io/badge/MiDaS-10B981?style=curved-square&logoColor=white" />
      <img src="https://img.shields.io/badge/DeepSORT-059669?style=curved-square&logoColor=white" />
      <img src="https://img.shields.io/badge/Object%20Detection-1D9E75?style=curved-square&logoColor=white" />
      <img src="https://img.shields.io/badge/Depth%20Estimation-0F6E56?style=curved-square&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td valign="top">
      <b>Data Engineering, Databases & Cloud</b><br><br>
      <img src="https://img.shields.io/badge/Postgres%20%2B%20pgvector-4169E1?style=curved-square&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/Elasticsearch-005571?style=curved-square&logo=elasticsearch&logoColor=white" />
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=curved-square&logo=mysql&logoColor=white" />
      <img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=curved-square&logo=apachespark&logoColor=white" />
      <img src="https://img.shields.io/badge/Databricks-FF3621?style=curved-square&logo=databricks&logoColor=white" />
      <img src="https://img.shields.io/badge/ETL%20Pipelines-6B7280?style=curved-square&logoColor=white" />
      <img src="https://img.shields.io/badge/CI%2FCD-6B7280?style=curved-square&logoColor=white" />
      <img src="https://img.shields.io/badge/Feature%20Engineering-6B7280?style=curved-square&logoColor=white" />
    </td>
    <td valign="top">
      <b>BI & Visualization</b><br><br>
      <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=curved-square&logo=powerbi&logoColor=black" />
      <img src="https://img.shields.io/badge/Tableau-E97627?style=curved-square&logo=tableau&logoColor=white" />
      <img src="https://img.shields.io/badge/Matplotlib-11557C?style=curved-square&logo=matplotlib&logoColor=white" />
      <img src="https://img.shields.io/badge/KPI%20Reporting-6B7280?style=curved-square&logoColor=white" />
      <img src="https://img.shields.io/badge/EDA-6B7280?style=curved-square&logoColor=white" />
    </td>
  </tr>
</table>
---
 
## Featured Projects
 
### Clinical Triage AI Pipeline *(VCMx Exchange)*
> *Industry · Jun – Sep 2026*
 
Go-based clinical triage pipeline using MedGemma 4B (Ollama), a Qwen 3 4B router, and deterministic safety rules. PHI-safe by design (de-identified context only, over gRPC/Protobuf), with structured output validation, practitioner review enforcement, and 48 automated safety tests. *Proprietary work, described at a high level.*
 
`Go` `MedGemma` `Ollama` `Qwen 3` `gRPC` `Protobuf` `pgvector` `RAG`
 
---
 
### LLM-Guided Vision-and-Language Navigation *(pinned)*
> *Research · Wilfrid Laurier University · 2025–2026*
 
End-to-end VLN agent navigating indoor Matterport3D environments from natural language. GPT-4-turbo high-level planner + BLIP + YOLOv8 + MiDaS perception + PPO RL executor + Spatial Episodic Memory + 6-layer guardrail system. **83.3% SR, 0.607 SPL** on R2R val-unseen.
 
`GPT-4` `BLIP` `YOLOv8` `MiDaS` `PPO` `SLAM` `Matterport3D` `R2R` `Python`
 
---
 
### ML-Powered Academic Research Retrieval System *(pinned)*
> *Wilfrid Laurier University*
 
RAG pipeline combining SciBERT embeddings and Elasticsearch to search, rank, and summarise academic papers. Embedding-based retrieval outperforms keyword search on domain-specific queries, with prompt-driven summarisation evaluated for factual consistency and source alignment.
 
`RAG` `SciBERT` `Elasticsearch` `Transformers` `PyTorch` `TensorFlow` `NLP`
 
---
 
### Real-Time Sports Analytics Pipeline *(pinned)*
> *Wilfrid Laurier University*
 
Player tracking over live match footage using YOLOv8 + DeepSORT. Extracts movement metrics — speed, acceleration, distance covered, zone occupancy — and forecasts positioning with LSTM models. **93% zone prediction accuracy.**
 
`YOLOv8` `DeepSORT` `LSTM` `OpenCV` `Computer Vision` `Python`
 
---
 
### RAG Knowledge Assistant
 
End-to-end GenAI application: document preprocessing, chunking, embeddings, semantic search, and source-aware response generation designed to reduce unsupported answers.
 
`Python` `RAG` `LLMs` `Embeddings` `Semantic Search` `Prompt Engineering`
 
---
 
### Anomaly Detection in Firewall Traffic
> *Wilfrid Laurier University*
 
Anomaly detection pipeline over network traffic logs using Isolation Forest, Gradient Boosting, and Graph Neural Networks to surface suspicious behaviour and monitoring signals.
 
`PyTorch` `GNN` `Scikit-learn` `Isolation Forest` `Network Analysis`
 
---
 
## Let's Connect
 
I'm open to AI/ML engineering and research roles, collaborations, and conversations about agentic systems, embodied AI, and safe AI in healthcare.
 
[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0077B5?style=curved-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bantu-keerthana-b546271a6)
[![Email](https://img.shields.io/badge/Send%20me%20an%20Email-D14836?style=curved-square&logo=gmail&logoColor=white)](mailto:imwannabebk@gmail.com)
 
---
 
<div align="center">
  <i>From <a href="https://github.com/keerthana-bantu">keerthana-bantu</a> — always learning, always building</i>
</div>
 
