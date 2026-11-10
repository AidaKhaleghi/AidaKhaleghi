<h1 align="center">Hi, I'm Aida Khaleghi 👋</h1>
<h3 align="center">M.Sc. Student in AI & Robotics @ Iran University of Science and Technology (IUST)</h3>

<p align="center">
  <a href="https://aidakhaleghi.github.io/">
    <img src="https://img.shields.io/badge/Website-9E2A5E?style=for-the-badge&logo=googlechrome&logoColor=white" />
  </a>
  <a href="https://aidakhaleghi.github.io/Aida_Khaleghi_CV.pdf">
    <img src="https://img.shields.io/badge/CV-555555?style=for-the-badge&logo=readthedocs&logoColor=white" />
  </a>
  <a href="mailto:aiida.khaleghi@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/aidakhaleghi/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://orcid.org/0009-0005-0686-1498">
    <img src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" />
  </a>
  <a href="https://t.me/AidaKhaleghi">
    <img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" />
  </a>
</p>

<p align="center">
  <i>Interpretable machine learning for biomedical data, from medical images to single-cell and spatial omics 🧬</i><br/>
  <b>🎓 Applying for PhD positions starting in 2027</b>
</p>

---

### 🔬 About Me

I'm an M.Sc. student in Artificial Intelligence and Robotics at **Iran University of Science and Technology (IUST)**, working in the Data Mining Lab with Prof. Behrouz Minaei-Bidgoli and Dr. Maryam Amoozegar. I hold a B.Sc. in Computer Engineering from Shahid Bahonar University of Kerman.

- 🩻 **Now — Interpretable models for medical imaging.** My thesis, *"Deep Unfolding-Based Anomaly Detection in Medical Imaging,"* unfolds robust PCA into a trainable network with convolutional and attention modules, evaluated on brain MRI (BraTS).
- 🎥 **Also — Online, unsupervised video segmentation.** At Kerman Graduate University of Technology, I extended a tensor-based moving object segmentation method into a hybrid ConvLSTM/CNN network that learns online without labels, improving F-measure by 0.1+ on LASIESTA and CDNet2014.
- 🧬 **Next — Machine learning for computational biology.** This is where I want to do my PhD: **single-cell and spatial omics**, **perturbation response modeling**, **foundation models for biology**, and **interpretable models of biological systems**. I'm learning the biology from the ground up through coursework and hands-on projects.
- 📝 **Before — NLP.** My B.Sc. project adapted a heterogeneous graph neural network for Persian sentiment analysis (grade 20/20).

---

### 📄 Publications

- **A. Khaleghi**, M. Amoozegar. *Online Unsupervised Hybrid Network for Moving Object Segmentation in Videos.* Manuscript in preparation, 2026.
- A. Ghasemi, B. Minaei-Bidgoli, **A. Khaleghi**. *Universal Noise Augmentation (UNA): A Language-Agnostic Framework for Robust Multilingual Text Classification.* Under review at *Machine Learning with Applications*, 2026. [[Preprint]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7513373)

---

### 🚀 Featured Projects

**🧪 Computational Biology & Drug Discovery**

- **[Perturbench](https://github.com/AidaKhaleghi/Perturbench)** — Benchmarks a CPA-style conditional VAE against additive and mean baselines for predicting unseen double gene perturbations (Norman 2019 Perturb-seq), with 5 seeds and bootstrap CIs. The additive baseline wins (MSE 0.045 vs. 0.057), and CPA fails on perturbations unlike those seen in training.
- **[Drug-Drug Interaction Prediction with GNNs](https://github.com/AidaKhaleghi/Drug-Drug-Interaction_GNN)** — Link prediction on the `ogbl-ddi` graph with a GraphSAGE encoder and MLP pair scorer. Test Hits@20 of 0.896 on 500 drugs and 0.845 on 2,134 drugs without retuning.

**🩻 Medical Imaging**

- **[Breast Tumor Segmentation](https://github.com/AidaKhaleghi/Breast_Tumor_Segmentation)** — Multi-task MONAI U-Net for breast ultrasound (BUS-BRA) that jointly segments tumors and classifies them as benign or malignant. 0.82 Dice and 0.84 ROC-AUC on a held-out test set.

**🧠 Generative & Representation Learning**

- **[VAE on MNIST](https://github.com/AidaKhaleghi/VAE_MNIST)** — Convolutional variational autoencoder built from scratch in PyTorch, with latent-space interpolation and a full 2D latent sweep.

**👁️ Computer Vision**

- **[YOLOv11 Segmentation in Adverse Weather (CARLA)](https://github.com/AidaKhaleghi/YOLOv11_Carla_Segmentation)** — 3,704-frame CARLA dataset across clear, rain, fog and night with automated GroundedSAM labels; YOLOv11 instance segmentation with a 4.1× inference speedup via FP16 TensorRT.
- **[MVAM: Multi-View Steering Angle Prediction](https://github.com/AidaKhaleghi/MVAM_Steering_Angle)** — Predicts steering angle from three dashboard camera views using a shared ResMLP backbone with multi-head attention for view fusion.
- **[Multi-Scale Featured LBP for Facial Expression Recognition](https://github.com/AidaKhaleghi/Multi-Scale-Featured-Local-Binary-Pattern)** — Implementation of a published multi-scale Local Binary Pattern descriptor for facial expression recognition.
- **[Iranian License Plate Tamper Detection](https://github.com/AidaKhaleghi/Plate_Tamper_Detection)** — Classical OpenCV pipeline that localizes, verifies and scores license plates for signs of tampering.

**🤖 LLMs, Agents & NLP**

- **[Multi-Agent HPO](https://github.com/AidaKhaleghi/Multi-agent-HPO)** — Collaborating on a multi-agent approach to hyperparameter optimization.
- **[Multi-Agent Debate System](https://github.com/AidaKhaleghi/Multi-Agent_Debate_System)** — LangGraph simulation where two LLM agents debate and a judge panel scores the outcome, comparing single-model vs. multi-model judging.
- **[Plan-and-Solve Prompting Reproduction](https://github.com/AidaKhaleghi/Plan_and_Solve_Reproduction)** — Reproduces *Plan-and-Solve* zero-shot prompting on four reasoning benchmarks with LLaMA 3.3, compared against the original GPT-3 results.

**📚 Learning Computational Biology**

- **[Single-Cell Best Practices](https://github.com/AidaKhaleghi/single-cell-best-practices)** — My fork of the Theis lab's open book, which I'm working through from preprocessing and clustering to perturbation and spatial analysis.
- **[Advanced Bioinformatics](https://github.com/AidaKhaleghi/Advanced-Bioinformatics)** — My fork of a hands-on roadmap from Linux, Python and R to RNA-seq, genomics and Bioconductor.

<p align="center"><i>See <a href="https://github.com/AidaKhaleghi?tab=repositories">all repositories →</a></i></p>

---

### 🧰 Skills & Tools

**Languages**

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" /> <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white" />

**Computational Biology & Graph ML**

<img src="https://img.shields.io/badge/Scanpy-1B9E77?style=for-the-badge" /> <img src="https://img.shields.io/badge/AnnData-2E7D32?style=for-the-badge" /> <img src="https://img.shields.io/badge/PyTorch%20Geometric-3C2179?style=for-the-badge&logo=pytorch&logoColor=white" /> <img src="https://img.shields.io/badge/NetworkX-4B8BBE?style=for-the-badge" />

**Machine Learning & Deep Learning**

<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" /> <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" /> <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" /> <img src="https://img.shields.io/badge/🤗%20Transformers-FFD21E?style=for-the-badge&logoColor=black" /> <img src="https://img.shields.io/badge/TensorBoard-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />

**Medical Imaging & Vision**

<img src="https://img.shields.io/badge/MONAI-0FA0CE?style=for-the-badge" /> <img src="https://img.shields.io/badge/nnU--Net-2C5F8A?style=for-the-badge" /> <img src="https://img.shields.io/badge/Nilearn-F7941E?style=for-the-badge" /> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" /> <img src="https://img.shields.io/badge/YOLO-111F68?style=for-the-badge" /> <img src="https://img.shields.io/badge/Albumentations-FF6F61?style=for-the-badge" /> <img src="https://img.shields.io/badge/Roboflow-6706CE?style=for-the-badge" />

**Data & Visualization**

<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" /> <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" /> <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge" /> <img src="https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge" />

**LLMs, Agents & Apps**

<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge" /> <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge" /> <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" /> <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />

**Deployment & Tools**

<img src="https://img.shields.io/badge/TensorRT-76B900?style=for-the-badge&logo=nvidia&logoColor=white" /> <img src="https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white" /> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" /> <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" /> <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" /> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white" />

---

<p align="center">
  📫 I'm happy to talk about research, collaborations or PhD positions. Reach out via <a href="mailto:aiida.khaleghi@gmail.com">email</a>, <a href="https://www.linkedin.com/in/aidakhaleghi/">LinkedIn</a>, or <a href="https://t.me/AidaKhaleghi">Telegram</a>, or visit <a href="https://aidakhaleghi.github.io/">my website</a>. ✨
</p>
