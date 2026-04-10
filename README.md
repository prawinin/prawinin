<!-- Animated Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:1a1b27&height=220&section=header&text=Prawin%20Kumar&fontSize=75&fontColor=58a6ff&fontAlignY=35&animation=fadeIn&desc=AI%20Systems%20Architect%20%7C%20Founder%20@%20VyapAI&descSize=18&descColor=8b949e&descAlignY=55" width="100%" />
</p>

<!-- Typing SVG -->
<p align="center">
  <a href="https://vyapai.tech">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=100&lines=Building+production-grade+AI+systems+that+enterprises+deploy+on+day+one;Offline-first+%E2%80%A2+Citation-grounded+%E2%80%A2+Air-gap+capable;From+legal+intelligence+to+clinical+AI+to+M%26A+analysis" alt="Typing SVG" />
  </a>
</p>

<!-- Quick Links -->
<p align="center">
  <a href="https://vyapai.tech"><img src="https://img.shields.io/badge/🌐_vyapai.tech-Visit_Portfolio-58a6ff?style=for-the-badge&labelColor=0d1117" alt="Portfolio" /></a>&nbsp;
  <a href="mailto:prawin@vyapai.tech"><img src="https://img.shields.io/badge/📧_Email-prawin@vyapai.tech-58a6ff?style=for-the-badge&labelColor=0d1117" alt="Email" /></a>&nbsp;
  <a href="https://calendly.com/prawinin"><img src="https://img.shields.io/badge/📅_Book_a_Call-Calendly-58a6ff?style=for-the-badge&labelColor=0d1117" alt="Calendly" /></a>
</p>

<br/>

<!-- Divider -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<br/>

## 🧠 About Me

```yaml
name: Prawin Kumar
role: Founder & Lead Engineer @ VyapAI
education: IIT Guwahati — BSc Data Science & AI
focus: Enterprise AI Infrastructure
philosophy: "We don't build demos. We build systems that work on the infrastructure you already have."
```

- 🏗️ I architect **production-grade AI systems** — RAG pipelines, offline-first legal AI, clinical trial matchers, M&A analyzers
- 🔒 Every system I build is **air-gap capable** — zero data leakage, locally hosted LLMs, privacy-first
- 🎯 I ship **full-stack AI products** with source code, deployment docs, and enterprise integration support
- 📚 IIT Guwahati — **BSc Data Science & AI** — building with academic rigor and engineering depth
- 🌍 Building from India, engineering for global enterprises

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<br/>

## 🚀 Flagship Products — VyapAI

> *Each solution ships with full source code, deployment architecture, and technical documentation.*  
> *Visit **[vyapai.tech](https://vyapai.tech)** for enterprise inquiries and demos.*

<table>
<tr>
<td width="50%">

### ⚖️ NyayAI — Indian Legal Intelligence
<p>
  <img src="https://img.shields.io/badge/RAG-Pipeline-blue?style=flat-square&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/FAISS-Vector_Search-green?style=flat-square&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/Ollama-Local_LLM-orange?style=flat-square&labelColor=0d1117" />
</p>

Local-first legal intelligence system using RAG for Indian legal workflows. Retrieves precedents via FAISS + SQLite, grounds responses against India Code statutory database, and generates advisory assessments via on-device LLM inference.

**Key Engineering:**
- Dual-store architecture: `legal_cases.db` + `indiacode_corpus.db`
- GPU-accelerated vector indexing (ROCm/CUDA)
- BNS/BNSS/BSA latest-law prioritization

</td>
<td width="50%">

### 🇺🇸 AmicusAI US — Federal Legal Research
<p>
  <img src="https://img.shields.io/badge/Air--Gapped-Zero_Leakage-red?style=flat-square&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/CourtListener-Federal_API-blue?style=flat-square&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/Reranker-Court_Tiers-purple?style=flat-square&labelColor=0d1117" />
</p>

Offline-first U.S. legal research engine for Federal Appellate litigation. Citation-grounded memos using local RAG — zero public API exposure. Custom `USFederalReranker` boosts authority-weighted retrieval across court tiers.

**Key Engineering:**
- Federal scrapers: CourtListener, GovInfo, Congress.gov
- Jurisdiction-aware semantic reranking
- Strict prompt policy: verified, in-context evidence only

</td>
</tr>
<tr>
<td width="50%">

### 🔬 Ortho-Match — Clinical Trial Matcher
<p>
  <img src="https://img.shields.io/badge/100%25-Offline-teal?style=flat-square&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/PubMedBERT-Embeddings-blue?style=flat-square&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/HIPAA-Ready-green?style=flat-square&labelColor=0d1117" />
</p>

AI clinical trial discovery for orthopedic oncology. Hybrid SQL + FAISS matching engine — extracts structured patient profiles from pathology PDFs via on-device NER, then ranks ClinicalTrials.gov candidates by PubMedBERT semantic similarity.

**Key Engineering:**
- Two-stage matcher: SQL gate → FAISS cosine ranking
- PDF → structured patient profile via Ollama NER
- Explainable recommendations with score rationale

</td>
<td width="50%">

### 📊 VDR Analyzer — M&A Due Diligence
<p>
  <img src="https://img.shields.io/badge/Qdrant-Vector_DB-blue?style=flat-square&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/Citation-Grounded-green?style=flat-square&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/Multi--Provider-LLM-orange?style=flat-square&labelColor=0d1117" />
</p>

Offline RAG pipeline for virtual data room document analysis. Ingests PDF contracts, indexes into Qdrant, and delivers citation-grounded answers with document/page references. Three-stage separation: ingestion → retrieval → generation.

**Key Engineering:**
- UUID5 chunk IDs for idempotent, duplication-safe indexing
- CPU ingestion + GPU generation pipeline split
- Provider-agnostic: Ollama, llama.cpp, vLLM, TGI

</td>
</tr>
<tr>
<td width="50%">

### 🏗️ Project Neev — AI Construction Platform
<p>
  <img src="https://img.shields.io/badge/Genetic-Algorithm-purple?style=flat-square&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/3D-Three.js-blue?style=flat-square&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/28--City-Cost_Index-green?style=flat-square&labelColor=0d1117" />
</p>

Complete AI construction platform: computer vision plot scanning → regulatory checks → genetic algorithm floor plans → ML cost prediction → 3D visualization → DXF CAD + PDF exports. Covers 28 Indian cities with CPWD DSR 2025 calibration.

**Key Engineering:**
- Genetic algorithm layout optimization
- Random Forest + CPWD DSR 2025 cost calibration
- Three.js interactive 3D building viewer

</td>
<td width="50%">

### 📸 GCam Fusion Studio — Camera Mod Pipeline
<p>
  <img src="https://img.shields.io/badge/APK-Builder-blue?style=flat-square&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/Device-Profiling-green?style=flat-square&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/Multi--Lens-Tuning-orange?style=flat-square&labelColor=0d1117" />
</p>

Build pipeline for device-specific GCam mods. Takes a base APK + config + device profile JSON and produces a normalized build workspace with fusion recipes, patch blueprints, and an unsigned rebuilt APK candidate.

**Key Engineering:**
- Per-sensor tuning: aperture, OIS, HDR, RAW
- Seamless lens-switch feasibility analysis
- Low-light shadow cleanup + thermal budgeting

</td>
</tr>
</table>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">


## 🛠️ Tech Arsenal

<p align="center">

### Languages & Core
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

### AI / ML Stack
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

### Backend & APIs
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)

### Databases & Vector Stores
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

### DevOps & Tools
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![ROCm](https://img.shields.io/badge/ROCm-ED1C24?style=for-the-badge&logo=amd&logoColor=white)

</p>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<br/>

## 🏛️ Architecture Philosophy

```
┌─────────────────────────────────────────────────────────────────────┐
│                    PRODUCTION AI SYSTEMS @ VyapAI                    │
├─────────────────────────────────────────────────────────────────────┤
│                                                                     │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐              │
│  │   Ingestion   │  │  Retrieval   │  │  Generation  │              │
│  │   ─────────   │  │  ──────────  │  │  ──────────  │              │
│  │  PDF/Web/API  │→ │ FAISS/Qdrant │→ │ Ollama/vLLM  │              │
│  │  parsing +    │  │ hybrid SQL + │  │ citation-    │              │
│  │  chunking     │  │ semantic     │  │ grounded     │              │
│  └──────────────┘  └──────────────┘  └──────────────┘              │
│                                                                     │
│  Design Principles:                                                 │
│  ✦ Offline-first — air-gap capable, zero data leakage              │
│  ✦ Citation-grounded — every claim traceable to source              │
│  ✦ Laptop-first, scalable later — works on modest hardware          │
│  ✦ Provider-agnostic — swap LLMs without code changes               │
│  ✦ Idempotent indexing — re-index safely, never duplicate           │
│                                                                     │
└─────────────────────────────────────────────────────────────────────┘
```

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<br/>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=prawinin&style=for-the-badge&color=58a6ff&label=PROFILE+VIEWS&labelColor=0d1117" alt="Profile Views" />
</p>

<p align="center">
  <em>"We don't build demos. We build systems that work on the infrastructure you already have."</em>
</p>

<!-- Animated Footer -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:1a1b27&height=120&section=footer" width="100%" />
</p>
