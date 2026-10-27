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
- 🔬 **Graduate ML Researcher (Master’s Thesis), FAU Erlangen-Nürnberg** (August 2025 – March 2026), focused on deep learning and computer vision; developed hybrid segmentation pipelines and achieved **0.8172 mIoU** with SimMIM-pretrained Swin-UNet on U-DIADS-Bib.
- 👁️ Interested in computer vision, applied machine learning, AI engineering, and ML systems
- 🧩 Built a full-stack document-layout application integrating a pretrained Docling Heron RT-DETR v2 model with FastAPI and React/TypeScript
- 🛠️ Project experience across Python, PyTorch, Hugging Face Transformers, LangChain, ChromaDB, FastAPI, React/TypeScript, Streamlit, Docker, and automated testing
- 🌍 Open to suitable junior and entry-level AI/ML, computer-vision, and software engineering opportunities

---

## 🛠️ Technical Skills

- **Programming:** Python, TypeScript, JavaScript, PHP
- **Machine Learning & Computer Vision:** Deep Learning, CNNs, Transformers, Object Detection, Image Segmentation, Predictive Analytics
- **Generative AI:** LLMs, RAG, Embeddings, Semantic Search, OCR, Agentic AI (foundational)
- **Frameworks & Libraries:** PyTorch, Hugging Face Transformers, LangChain, Scikit-learn, Pandas, NumPy, OpenCV, Matplotlib
- **Backend & Frontend:** FastAPI, Flask, Streamlit, React, REST APIs
- **Databases:** MySQL, PostgreSQL, ChromaDB, Vector Search
- **MLOps, DevOps & Cloud:** Git, Docker, Docker Compose, DVC, MLflow, TensorBoard, Microsoft Azure, AWS (basics)
- **Testing & Software Quality:** pytest, Vitest, API Testing, Unit Testing, Environment-based Configuration
- **Data Engineering:** ETL Fundamentals

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

### 🧠 RAG Pipeline for Semi-Structured PDF Querying
A retrieval-augmented generation application for querying text and tabular content from semi-structured and scanned PDFs through a Streamlit interface.

**Tech:** Python, LangChain, ChromaDB, Hugging Face Transformers, embeddings, semantic/vector search, OCR, document/table parsing, Streamlit

- Implemented document chunking, summarization, embedding, and multi-vector retrieval, with local caching to avoid redundant computation.
- Integrated OCR and document/table parsing components to support scanned PDFs and complex tabular content.
- Built an interactive interface for querying semi-structured PDF content.

🔗 [Repository: RAG-Pipeline-for-Semistructured-Data](https://github.com/niteshshah53/RAG-Pipeline-for-Semistructured-Data)

### 🔬 Handwritten Document Layout Segmentation — Master's Thesis
**Graduate ML Researcher (Master’s Thesis)** | *Friedrich-Alexander-Universität Erlangen-Nürnberg*  
*Deep Learning & Computer Vision focus* | August 2025 – March 2026

**Tech:** PyTorch, Swin-UNet, MISSFormer, SSTrans-Net, CNN–Transformer hybrid pipelines, custom Dataset/DataLoader, weighted Cross-Entropy/Dice loss, Fourier Feature Fusion, deep supervision, Docker, NVIDIA A100 HPC, Automatic Mixed Precision (AMP), gradient accumulation, SimMIM, TensorBoard

- **Architected two novel hybrid pipelines** modifying vision transformer models (**Swin-UNet, MISSFormer, SSTrans-Net**) in **PyTorch**, containerizing the environments via **Docker** to scale training across an **NVIDIA A100 HPC cluster**.
- **Engineered custom Dataset and DataLoader scripts** featuring complex bitwise multi-class parsing logic, class-aware data augmentations, and a hybrid Weighted Cross-Entropy/Dice loss function to mitigate severe dataset class imbalances.
- **Implemented advanced custom layers** (Fourier Feature Fusion, deep supervision) while optimizing GPU memory utilization using **Automatic Mixed Precision (AMP)** and gradient accumulation.
- **Executed self-supervised SimMIM pretraining** using **TensorBoard** for rigorous experiment tracking, achieving a peak metric of **0.8172 mIoU** (a **3.82% relative improvement** over the 0.7871 baseline).

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

### Graduate ML Researcher (Master’s Thesis) — Friedrich-Alexander-Universität Erlangen-Nürnberg
**Deep Learning & Computer Vision focus** | **August 2025 – March 2026**

- **Architected two novel hybrid pipelines** modifying vision transformer models (**Swin-UNet, MISSFormer, SSTrans-Net**) in **PyTorch**, containerizing the environments via **Docker** to scale training across an **NVIDIA A100 HPC cluster**.
- **Engineered custom Dataset and DataLoader scripts** featuring complex bitwise multi-class parsing logic, class-aware data augmentations, and a hybrid Weighted Cross-Entropy/Dice loss function to mitigate severe dataset class imbalances.
- **Implemented advanced custom layers** (Fourier Feature Fusion, deep supervision) while optimizing GPU memory utilization using **Automatic Mixed Precision (AMP)** and gradient accumulation.
- **Executed self-supervised SimMIM pretraining** using **TensorBoard** for rigorous experiment tracking, achieving a peak metric of **0.8172 mIoU** (a **3.82% relative improvement** over the 0.7871 baseline).

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
