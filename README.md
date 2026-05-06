# Hi, I'm Abhiroop Sarkar

AI/ML Engineer · RAG Systems · Distributed ML · Formal Verification  
Bengaluru, India &nbsp;|&nbsp; abhiroop.sarkar23@gmail.com

> Building production ML systems for GenAI, RAG, and distributed inference.  
> Joint MSc in Data Science & AI from IIT Madras and University of Birmingham.  
> Previously at Airbus and Axis Bank. I like clean abstractions, well-monitored systems, and cricket.

---

## Tech Stack

**Languages**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**ML / DL Frameworks**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)

**GenAI & LLMs**  
![Gemini](https://img.shields.io/badge/Gemini_API-4285F4?style=flat-square&logo=google&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
`RAG Systems` `LoRA / QLoRA Fine-tuning` `Prompt Engineering` `INT4/INT8 Quantization`

**ML Systems**  
`PyTorch DDP` `NCCL` `GPU Optimization` `Model Compression` `Distributed Training`

**Cloud & MLOps**  
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![W&B](https://img.shields.io/badge/Weights_&_Biases-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black)
`ZenML` `GCP` `SageMaker` `SQS` `S3`

**Databases & Vector Search**  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
`pgvector` `ChromaDB` `HNSW` `IVF-Flat`

**Formal Methods**  
`CVXPY` `SCS` `Semidefinite Programming` `Lyapunov Theory` `Supermartingales`

**Computer Vision**  
`YOLOv11` `OpenCV` `Document Layout Detection` `OCR`

---

## Experience

### AI/ML Engineer — Gist Impact, Bengaluru (2024 – Present)
- Architected production multimodal GenAI system for CSRD sustainability reporting, processing 100K+ documents with 35% latency reduction through token-aware rate limiting and distributed processing
- Designed distributed system with FastAPI, AWS SQS, and S3; profiled queue sizing (256 messages) to eliminate worker starvation and memory pressure
- Optimized semantic search with pgvector HNSW indexing achieving sub-100ms query latency; query batching reduced end-to-end latency by 40%
- Profiled Gemini 2.0 API throughput vs. concurrency, determining optimal parameters (batch=10, concurrent=3) while managing quota constraints (60 RPM, 32K TPM)

### GenAI Research Intern — Airbus, Bangalore (2024)
- Built production RAG system for aerospace contract analysis; reduced hallucination through attention distribution profiling and information density-based context filtering
- Evaluated dense (bi-encoder) vs. sparse (BM25) retrieval trade-offs for legal terminology; investigated contrastive learning for ranking improvement
- Fine-tuned YOLOv11n for document layout detection achieving 92% mAP; integrated with Docling for structured extraction from multi-column contract formats
- Evaluated INT8/INT4 quantization + LoRA for GPU-constrained fine-tuning; identified optimal accuracy-efficiency operating points
- Awarded TechXceed Top 5 Paper among 115 submissions at Airbus Research Publication Conference

### Data Science Intern — Axis Bank, Mumbai (2023)
- Fine-tuned FinBERT on 142K banking documents for complaint severity classification, improving accuracy from 94.42% to 97.13%
- Ablation studies revealed domain adaptation primarily affects middle-layer attention patterns while preserving general language understanding in early layers

### ML Research Intern — Panoculon Lab, IIT Madras Research Park (2023)
- Built CV-powered Flutter app for visually impaired navigation; achieved 95% object detection accuracy with sub-200ms latency using TensorFlow Lite edge deployment

---

## Research

### Master's Dissertation: Formal Verification in Reinforcement Learning (2024 – 2025)
Supervisor: Dr. Mirco Giacobbe, University of Birmingham

Developed formal verification methodology for RL reward synthesis using polynomial ranking supermartingales and semidefinite programming. Achieved 100% synthesis success across three test systems with sub-second computation. Synthesized reward functions with provable convergence guarantees matching practical heuristic performance (7.1 vs 7.1 steps to goal) while providing mathematical certainty.  
`CVXPY` `SCS` `Positivstellensatz` `Stochastic Systems`

### Anomaly Detection Using Transformers (2023 – 2024)
Supervisor: Prof. Raghunathan Rengaswamy, RBCDSAI, IIT Madras

Unsupervised anomaly detection for manufacturing sequences using BERT embeddings — 83% accuracy, 11% above Random Forest baseline. Investigated DistilBERT compression for edge deployment under 100ms latency constraint.

### Distributed CNN Training — Curtin University (2021 – 2022)
Supervisor: Dr. Filbert Juwono

Optimized distributed CNN training on dual NVIDIA Tesla K80 GPUs achieving 1.85x speedup. Identified PCIe bandwidth as primary bottleneck; implemented gradient accumulation and FP16 mixed-precision training. Published at IEEE GECOST 2022.

---

## Projects

**Smart Research Retriever (RAG)**  
RAG system for academic paper retrieval using ChromaDB, MoE-inspired specialized retrievers, and cross-encoder re-ranking. Improved retrieval accuracy by 25%, reduced irrelevant results by 30%.  
`ChromaDB` `LangChain` `Cross-encoder` `Query Expansion`

**ML Pipeline with ZenML and MLflow**  
End-to-end ML pipeline with experiment tracking, model versioning, and A/B testing framework for 10+ model variants with automated rollback on performance degradation.  
`ZenML` `MLflow` `GitHub Actions` `CI/CD`

---

## Education

**Joint MSc, Data Science and Artificial Intelligence** — 2023–2025  
University of Birmingham & IIT Madras  
Dissertation: "Reward Function Optimization in Reinforcement Learning" — Supervisor: Dr. Mirco Giacobbe

**BTech, Artificial Intelligence** — 2019–2023  
G H Raisoni College of Engineering, Nagpur — CGPA: 8.60/10 (First Class with Distinction)

---

## Publications

- "A Computational Approach for Predicting the Termination of COVID-19" — IEEE GECOST 2022
- "Natural Language Based Corpus Model on a Wide Range of Medical Corpus" — Journal Publication

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhiroop-sarkar-a2bb2119b/)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=flat-square&logo=twitter&logoColor=white)](https://twitter.com/AbhiroopSarkar9)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:abhiroop.sarkar23@gmail.com)

---

Cricket fan. Music listener. Always learning.
