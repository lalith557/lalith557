<div align="center">

# Hi, I'm Gona Lalith 👋

### AI/ML Engineer · Computer Vision · Builder

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1000&color=58A6FF&center=true&vCenter=true&width=700&lines=Building+ML+systems+where+correctness+is+non-negotiable;From+transparent-object+segmentation+to+clinical+EHR+pipelines;Vision+Language+Models+%7C+GNNs+%7C+Real-world+ML;Currently%3A+patent+application+under+review+%2B+freelance+ML" alt="Typing SVG" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/glalith)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@gonalalith2005)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)]([https://orcid.org/REPLACE-WITH-YOUR-ORCID-ID](https://orcid.org/0009-0006-7208-9341))
[![Email](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gonalalith2005@gmail.com)

</div>

<br>

<div align="center">

|  🔬 Patent Application Under Review  |  🖼️ 0.92 IoU on Trans10K (Spectra)  |  🧬 26.9K Patients Modeled (T2D)  |  🛠️ End-to-End ML Systems Shipped  |
|:---:|:---:|:---:|:---:|

</div>

---

## 📋 Quick Facts

| | |
|---|---|
| 🎯 **Focus** | Computer vision, vision-language models, and applied/clinical ML |
| 🎓 **Education** | B.Tech CSE (AI/ML), Lovely Professional University |
| 💼 **Status** | 🟢 Open to ML/AI Engineering internships & full-time roles |
| 🔬 **Innovation** | Co-inventor on a patent application under review (on-device ML) |

---

## 🌱 Currently

- 🖼️ Deepening work in **Vision Language Models** and multimodal deep learning
- 💼 Delivering end-to-end ML solutions as a **freelance developer on Upwork**
- 📚 Sharpening DSA fundamentals (Graphs, DP, Greedy, Trees, Binary Search) for technical interviews

---

## About

I build machine learning systems end-to-end — from the model architecture through to a deployed, reproducible pipeline — with a focus on computer vision and high-stakes applied ML.

Over the last year I've built a transparent-object segmentation model fusing a self-supervised DINOv2 ViT backbone with optical-flow cues, a progression-aware GNN framework for clinical subtyping on MIMIC-IV EHR data, and shipped real ML solutions for freelance clients. I'm also a co-inventor on a patent application under review. Every project here has real metrics, rigorous evaluation, or real users — not just notebooks.

> **Focused on computer vision and vision-language models**, with an emphasis on rigorous evaluation and shipping reproducible systems.

---

## 🚀 Featured Projects

### 🔷 Spectra — Transparent-Object Segmentation

*Segments transparent objects by fusing self-supervised vision features with motion cues — then rigorously proves the gains come from the learned representation, not the pipeline.*

`Python` `PyTorch` `DINOv2 (ViT)` `RAFT` `cross-attention` `FastAPI` `Docker`

- **0.92 IoU on Trans10K** (**+3.6 IoU over DeepLabV3+**) by fusing a self-supervised **DINOv2 ViT backbone** with **RAFT optical-flow cues** via cross-attention
- Rigorous evaluation suite — **ablations, bootstrap CIs, TOST testing, zero-shot transfer** — isolating gains to the learned representation
- Shipped a reproducible pipeline (fixed seeds, deterministic training) as a containerized **FastAPI + Gradio** service (Docker/Railway) with per-image interpretability maps

**[📦 Repo](https://github.com/lalith557)**

---

### 🔷 Graph-Based Trajectory Modeling for Type 2 Diabetes Subtyping

*Moves T2D subtyping beyond static clustering — models how patients evolve over time, then validates that the subtypes actually predict different survival outcomes.*

`Python` `PyTorch` `Scikit-learn` `Pandas` `NumPy` `MIMIC-IV` `GNN (GAT/GCN)` `DTW`

- End-to-end **GNN pipeline** (multi-scale LSTM + cross-scale attention + GAT/GCN fusion + Markov modeling) for unsupervised subtyping over **26,923 EHR patients**, beating GRU/Transformer/GRU-D baselines (silhouette 0.36 vs. ≤0.28)
- **Leakage-free evaluation framework** (5-seed benchmarking, ablations, bootstrap CIs) and confounder-adjusted survival analysis (Cox w/ Charlson index + eGFR), lifting concordance **0.674 → 0.732**; externally validated on NHANES
- Validated that gains came from graph-based fusion, not attention/DTW add-ons — correcting non-reproducible results into honest, code-backed findings

**[📦 Repo](https://github.com/lalith557)**

---

### 🔷 Freelance ML Development — Upwork

*Delivering production machine learning for real clients — full pipeline, from raw data to a deployed prediction API.*

`Python` `Scikit-learn` `Flask` `Pandas` `NumPy` `Seaborn`

- Developed **end-to-end ML solutions** for client projects — data preprocessing, feature engineering, model training, and evaluation with Python and scikit-learn
- Deployed trained models as **RESTful APIs using Flask**, enabling real-time prediction and seamless integration into client applications
- Conducted **exploratory data analysis** and performance visualization (Pandas, NumPy, Seaborn) to improve model accuracy and interpretability

---

## 🏅 Patent

**Co-inventor** of a patent application **under review** for a novel on-device machine learning framework that distinguishes sensor faults from concept drift using **cross-channel coherence, temporal signatures, and rollback-protected model adaptation**.

---

## 🛠️ Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**ML / AI & Data**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**Deep Learning / VLM Toolkit**
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![timm](https://img.shields.io/badge/timm-4B0082?style=flat-square)
![PEFT](https://img.shields.io/badge/PEFT-2E8B57?style=flat-square)
![OpenCLIP](https://img.shields.io/badge/OpenCLIP-1F6FEB?style=flat-square)
![PyTorch Lightning](https://img.shields.io/badge/PyTorch%20Lightning-792EE5?style=flat-square&logo=lightning&logoColor=white)

**Systems & Infra**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![AWS SageMaker](https://img.shields.io/badge/AWS%20SageMaker-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

**Backend & Databases**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST%20APIs-005571?style=flat-square)

---

## 📊 GitHub Analytics

<table>
<tr>
<td width="60%">
<img src="https://github-readme-stats.vercel.app/api?username=lalith557&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" />
</td>
<td width="40%">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=lalith557&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</td>
</tr>
</table>

<div align="center">

![Streak](https://streak-stats.demolab.com/?user=lalith557&theme=tokyonight&hide_border=true)

![Daily Contributions](https://github-readme-activity-graph.vercel.app/graph?username=lalith557&theme=tokyo-night&hide_border=true&area=true)

</div>

---

## 💻 Competitive Programming

Actively solving DSA & CP problems.

**Focus areas:** Graphs · Dynamic Programming · Greedy · Trees · Binary Search

---

<div align="center">

## 📫 Let's Connect

I'm actively looking for **ML/AI Engineering internship & full-time roles** where I can build things that matter. If that's what you're hiring for — let's talk.

[![LinkedIn](https://img.shields.io/badge/Message%20me%20on-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/glalith)
[![Email](https://img.shields.io/badge/Email%20me-gonalalith2005%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gonalalith2005@gmail.com)

*Always building. Always measuring. Always shipping.*

![Profile Views](https://komarev.com/ghpvc/?username=lalith557&color=blueviolet&style=flat-square&label=Profile+Views)

</div>
