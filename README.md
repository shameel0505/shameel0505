# Mohamed Shameel

**Senior AI Systems Engineer & Automation Architect**  
*Building deterministic edge-AI systems, local inference runtimes, and resilient automation pipelines.*

[![GitHub](https://img.shields.io/badge/GitHub-shameel0505-181717?style=flat&logo=github)](https://github.com/shameel0505)
[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)](https://pytorch.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)](https://opencv.org/)

---

## 🏛️ Engineering Philosophy

> *"Seniority is not measured by lines of code or buzzword density, but by architectural judgment: understanding failure domains, eliminating false-positives deterministically, minimizing compute footprints, and building software that runs reliably in production without cloud dependencies."*

I specialize in building **air-gapped, zero-telemetry AI systems** and **high-throughput automation pipelines**. My focus centers on small-to-midsize model quantization (GGUF/GGML), Abstract Syntax Tree (AST) guardrails, edge computer vision, and robust distributed ETL architectures.

---

## 🚀 Featured Engineering Systems

### 1. [Aegis: Air-Gapped Semantic Code Review Engine](https://github.com/shameel0505/aegis)
*Local AI Code Review & Static Analysis Engine with Deterministic AST Guardrails.*
- **Problem:** Small local LLMs (3B-9B) run fast on laptops but hallucinate on framework-managed paradigms (e.g., falsely flagging FastAPI `Depends()` as null dereferences).
- **Solution:** Hybrid architecture combining Tree-sitter call-graph mapping with deterministic AST pre/post-filters to guarantee 100% false-positive rejection on framework safe zones while preserving critical security sinks (SQLi, command injection).
- **Stack:** Python, Tree-Sitter, AST, Pydantic, Git Notes synchronization, Local LLMs (Ollama / vLLM).

### 2. [YOLO Vehicle Speed & Flow Tracking](https://github.com/shameel0505/YOLO-Vehicle-Speed-Tracker)
*Real-Time Edge Computer Vision for Calibrated Velocity Estimation & Traffic Flow Modeling.*
- **Problem:** Naive Euclidean velocity tracking in surveillance footage distorts speeds due to inference latency and acute perspective compression.
- **Solution:** Frame-index synchronized velocity measurement ($v = \frac{d \cdot \text{FPS}}{\Delta \text{frames}}$) combined with planar projective geometry and multi-object tracking (ByteTrack / BoT-SORT).
- **Stack:** Ultralytics YOLOv8 / YOLO11, OpenCV, NumPy, Pytest unit-tested physics engine.

### 3. [GPT-Lite: Zero-Telemetry Local LLM Assistant](https://github.com/shameel0505/gpt-lite-local-chatbot)
*Production-Grade Air-Gapped Conversational Interface.*
- **Problem:** Cloud AI services introduce data exfiltration risks and high API recurring costs for everyday development.
- **Solution:** Low-footprint, memory-mapped local inference UI with `@st.cache_resource` weight persistence, dynamic context window pruning, and native XSS-sanitized chat components.
- **Stack:** Streamlit, GPT4All (GGML/llama.cpp runtime), 4-bit Quantization (Mistral 7B / Llama 3 8B).

### 4. [Automated Multi-Modal Content Pipeline](https://github.com/shameel0505/news_project)
*End-to-End News Aggregation, Typography Compositing & Social Publishing.*
- **Problem:** Automating daily high-volume content production requires strict deduplication, WCAG contrast compliance, and durable session handling without triggering anti-bot protections.
- **Solution:** Multi-source ingestion (Brave Search API + RSS), SHA-fingerprinted deduplication, automated dynamic typography rendering via Pillow, and rate-limited dispatch with exponential backoff.
- **Stack:** Python, Pillow, REST APIs, Session Recovery, Rate-Limiting Gateways.

---

## 🛠️ Technical Competencies

- **Languages & Core:** Python (Fluent: AsyncIO, Metaprogramming, CPython internals), SQL, Shell (Bash/Zsh).
- **AI & Deep Learning:** Quantized Local Inference (GGUF, GGML, Ollama), Computer Vision (YOLOv8/11, OpenCV, ByteTrack), PyTorch, Tree-sitter & AST Static Analysis.
- **System Design & Automation:** Resilient ETL Pipelines, Multi-Threading, Headless Automation, Rate-Limiting & Backoff Strategies.
- **Engineering Quality:** Test-Driven Development (`pytest`), Code Health (`ruff`, `mypy`), CI/CD (GitHub Actions), Docker, Semantic Git Workflows.

---

## 📬 Contact & Collaboration

- **GitHub:** [@shameel0505](https://github.com/shameel0505)
- **Primary Focus:** High-impact AI infrastructure, edge inference, and mission-critical automation systems.
