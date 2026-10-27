<img src="https://raw.githubusercontent.com/BEPb/BEPb/master/assets/Bottom_up.svg" width="100%" />

<h1 align="center">Hi 👋, I'm Nitesh Kumar Shah</h1>

<h3 align="center">
AI / Machine Learning Engineer · Computer Vision · LLM/RAG · MLOps
</h3>

<p align="center">
M.Sc. Artificial Intelligence · FAU Erlangen-Nürnberg, Germany
</p>

<p align="center">
I build and evaluate practical AI applications, from document-layout computer vision and ML pipelines to retrieval-augmented generation systems.
</p>

<p align="center">
<a href="mailto:kshahnitesh@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail" alt="Email"></a>
<a href="https://www.linkedin.com/in/niteshshah09"><img src="https://img.shields.io/badge/LinkedIn-Nitesh%20Shah-blue?style=for-the-badge&logo=linkedin" alt="LinkedIn"></a>
<a href="https://github.com/niteshshah53"><img src="https://img.shields.io/badge/GitHub-Profile-black?style=for-the-badge&logo=github" alt="GitHub"></a>
</p>

---

## 👋 About Me

- 🎓 **M.Sc. Artificial Intelligence**, FAU Erlangen-Nürnberg, Germany
- 🔬 **Master's thesis (August 2025 – March 2026):** transformer and CNN–Transformer approaches for handwritten document-layout segmentation
- 👁️ Interested in computer vision, applied machine learning, AI engineering, and ML systems
- 🧩 Built a full-stack document-layout application integrating a pretrained Docling Heron RT-DETR v2 model with FastAPI and React/TypeScript
- 🛠️ Practical experience with Python, PyTorch, FastAPI, Docker, automated testing, and reproducible ML workflows
- 🌍 Open to suitable junior and entry-level AI/ML, computer-vision, and software engineering opportunities

---

## 🛠️ Tech Stack

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-orange?style=flat&logo=openjdk)
![C](https://img.shields.io/badge/C-blue?style=flat)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)

### Machine Learning & Computer Vision
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow)
![Hugging Face Transformers](https://img.shields.io/badge/Transformers-yellow?style=flat)
![Computer Vision](https://img.shields.io/badge/Computer%20Vision-green?style=flat)
![RT-DETR](https://img.shields.io/badge/RT--DETR-v2-blue?style=flat)

### LLM & Retrieval
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat)
![RAG](https://img.shields.io/badge/RAG-purple?style=flat)
![Ollama](https://img.shields.io/badge/Ollama-black?style=flat)

### APIs, Testing & MLOps
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker)
![DVC](https://img.shields.io/badge/DVC-13ADC7?style=flat)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git)

### Data & Semantic Web
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql)
![RDF](https://img.shields.io/badge/RDF-blue?style=flat)
![SPARQL](https://img.shields.io/badge/SPARQL-green?style=flat)

---

## ⭐ Featured Projects

### 📄 Layout Vision — Document Layout Detection Application
A full-stack application that detects structural regions in a document image and visualizes the results through an interactive web interface.

**Tech:** Python, PyTorch, Hugging Face Transformers, Docling Heron RT-DETR v2, FastAPI, Pydantic, React, TypeScript, Vitest, pytest, Docker Compose

- Integrated the pretrained Docling Heron RT-DETR v2 model and exposed predictions through a typed FastAPI REST API.
- Implemented image validation, preprocessing, inference postprocessing, and mapping of bounding boxes to original-image pixel coordinates.
- Built an interactive React/TypeScript viewer with class filtering, synchronized selection, zoom, and box/label visibility controls.
- Added backend and frontend automated tests and a CPU-based Docker deployment path.
- Inspected predictions on six NASA technical-report page examples; this is qualitative evaluation, not a ground-truth accuracy benchmark.

🔗 [Repository: doc-layout-api](https://github.com/niteshshah53/doc-layout-api)

### 🧠 Industrial RAG Platform
A retrieval-augmented generation application for document question-answering with source citations.

**Tech:** Python, FastAPI, LangGraph, Qdrant, Ollama, React/TypeScript, RAGAS, Docker, Pytest

- Built an end-to-end retrieval and answer-generation workflow with hybrid retrieval and source-grounded citations.
- Used LangGraph to structure the workflow into explicit processing steps.
- Added evaluation tooling and automated tests to support systematic inspection of retrieval and answer quality.

🔗 [Repository: industrial-rag-platform](https://github.com/niteshshah53/industrial-rag-platform)

### 🔬 Handwritten Document Layout Segmentation — Master's Thesis
**Research period: August 2025 – March 2026**  
Research conducted with the Pattern Recognition Lab, FAU Erlangen-Nürnberg.

Compared transformer and CNN–Transformer approaches for segmenting handwritten document layouts.

**Tech:** Swin-UNet, MISSFormer, SSTrans-Net, CNN–Transformer architectures, PyTorch

- Benchmarked multiple segmentation architectures for handwritten document-layout analysis.
- Investigated model behavior through comparative experiments and ablation studies.
- Evaluated segmentation using metrics including mean Intersection over Union (mIoU), F1-score, precision, and recall.
- Achieved a best mIoU of approximately **0.81** in the thesis experiments.

🔗 [Repository: Transformer_Models](https://github.com/niteshshah53/Transformer_Models)

### ⚙️ MVTec Defect Detection — MLOps Portfolio
An experiment-tracking and reproducible pipeline project for industrial visual anomaly detection using PatchCore.

**Tech:** Python, Anomalib, PyTorch, MLflow, DVC, pytest

- Structured anomaly-detection experiments around the MVTec AD dataset and PatchCore baseline.
- Used MLflow for experiment tracking and DVC to organize reproducible pipeline stages.
- Audited image-level and pixel-level evaluation outputs across selected product categories.

🔗 [Repository: mvtec-defect-mlops](https://github.com/niteshshah53/mvtec-defect-mlops)

### 🐔 Chicken Disease Classification — ML Pipeline
An image-classification project demonstrating a repeatable training and deployment workflow.

**Tech:** TensorFlow/Keras, DVC, Docker, GitHub Actions, Azure

- Organized model development into a reproducible ML pipeline.
- Worked with dataset and pipeline versioning and automated build/test/deployment steps.

🔗 [Repository: Chicken-Disease-Classification-Project](https://github.com/niteshshah53/Chicken-Disease-Classification-Project)

---

## 🎓 Education

**M.Sc. Artificial Intelligence**  
FAU Erlangen-Nürnberg, Germany · October 2021 – April 2026

**B.E. Information Science and Engineering**  
Visvesvaraya Technological University, India · August 2016 – August 2020

---

## 💼 Experience

### Master's Thesis Research — Pattern Recognition Lab, FAU Erlangen-Nürnberg
**August 2025 – March 2026**

- Compared transformer and CNN–Transformer architectures for handwritten document-layout segmentation.
- Conducted segmentation experiments and analyzed model performance using standard region-overlap and classification metrics.
- Investigated model behavior through comparative and ablation experiments.

### Web Developer Intern — INFIDATA Technologies, Bangalore, India
**July 2019 – September 2019**

- Worked on backend logic and database operations for an e-commerce administration module using PHP, MySQL, and JavaScript/jQuery.
- Used Git for version control and Postman to test APIs.

---

## 📈 GitHub Stats

<p align="center">
<img height="170" src="https://github-readme-stats.vercel.app/api?username=niteshshah53&show_icons=true&theme=tokyonight" alt="GitHub stats">
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=niteshshah53&layout=compact&theme=tokyonight" alt="Top languages">
</p>

<p align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=niteshshah53&theme=tokyonight" alt="GitHub streak">
</p>

---

## 📫 Contact

- 📧 Email: [kshahnitesh@gmail.com](mailto:kshahnitesh@gmail.com)
- 💼 LinkedIn: [linkedin.com/in/niteshshah09](https://www.linkedin.com/in/niteshshah09)
- 🐙 GitHub: [github.com/niteshshah53](https://github.com/niteshshah53)

<p align="center">Thanks for visiting my profile 🚀</p>

<img src="https://raw.githubusercontent.com/Trilokia/Trilokia/master/bottom_header.svg" alt="">
