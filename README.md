# Clinician exploring Machine Learning, AI & Computational Biology

I am a clinician currently working in **neurosurgery**, with a broader interest in **neuroscience, computational biology, and the application of emerging technologies to medicine**.

This GitHub documents my journey into **machine learning, deep learning, biomedical data science, and computational research**—from learning the fundamentals of data science and building my first models to developing increasingly rigorous projects addressing real-world clinical and biological questions.

My clinical experience shapes many of the questions I am interested in exploring computationally. In particular, I am interested in how clinical, imaging, physiological, and biological data can be used to better understand neurological disease, predict clinically meaningful outcomes, and support medical decision-making.

My research interests have included **neuro-oncology, neuroimaging, neurocognition, cerebrovascular disease, brain-computer interface, and minimally invasive spine surgery**. Exposure to technologies such as **robotic-assisted spine surgery** has further encouraged my interest in how emerging computational and engineering technologies may influence future clinical practice.

Alongside clinical and research work, I have pursued training in **machine learning and artificial intelligence**, as well as **healthcare design and 3D printing**, as part of a broader interest in medical technology and innovation.

My current computational work is primarily focused on **neuroscience and neurosurgically relevant problems**, while projects outside medicine provide opportunities to develop transferable technical skills across different types of data and modelling problems.

Rather than presenting only finished products, I aim to document the process: **the code, experiments, unsuccessful approaches, model comparisons, evaluation methods, and lessons learned** while developing these projects.

---

## Featured Projects

### 🧠 Traumatic Brain Injury Outcome Prediction
**Clinical prediction modelling | Machine learning | Explainable AI**

**Clinical question:** Can information available during the early assessment of patients with traumatic brain injury predict unfavourable functional outcome at 90 days?

This project investigates conventional statistical and machine-learning approaches to clinical prognostication using clinical and neuroimaging variables from a multinational traumatic brain injury dataset.

The analysis compares **logistic regression, Random Forest, and XGBoost**, with emphasis on rigorous evaluation rather than predictive performance alone. Particular attention is given to discrimination, calibration, internal validation, information leakage, missing data, and model interpretability.

The underlying research repository remains private while the work is under active development. A standalone report presents the project in an accessible format, including its methodology, results, interpretation, and limitations.

**Methods:** Logistic Regression · Random Forest · XGBoost · ROC-AUC · Calibration · Brier Score · Bootstrap Validation · Explainability

**→ [View TBI project report](https://github.com/T-Y-Ang/NES-AI-portfolio/blob/main/projects/tbi-outcome-prediction.md)**

---

### 🧠 Glioma MRI Segmentation
**Medical imaging | Deep learning | Computational neuro-oncology**

Can deep learning automatically identify and segment glioma from multimodal brain MRI?

This project explores **deep-learning-based segmentation of glioma using multimodal MRI**, applying U-Net-based architectures to a clinically relevant neuro-oncology imaging problem.

The repository documents the complete development process, including data preparation, preprocessing, model development, training, evaluation, visualisation of predicted tumour masks, and interpretation of model performance.

Beyond developing a segmentation model, the project explores the practical challenges involved in applying deep learning to three-dimensional medical imaging data and provides an introduction to the intersection of **neurosurgery, neuro-oncology, computer vision, and computational imaging**.

**Methods:** Python · PyTorch · U-Net · Multimodal MRI · Medical Image Segmentation · Dice Score · Deep Learning

**→ [View Glioma MRI Segmentation repository](https://github.com/T-Y-Ang/glioma-mri-segmentation)**

---

## Planned Projects

### ⚡ EEG Seizure Detection
**Biomedical signal processing | Deep learning | Neuroscience**

Detection and classification of epileptic activity using signal-processing and deep-learning methods applied to EEG data.

This project will explore the computational analysis of neurophysiological signals, including EEG preprocessing, time-series modelling, patient-level validation, and deep-learning approaches to seizure detection.

**Planned methods:** Signal Processing · EEG · Time-Series Analysis · 1D CNN · Deep Learning

---

### 📈 Intracranial Pressure Crisis Forecasting
**Physiological time series | Machine learning | Neurocritical care**

Time-series modelling of physiological signals to investigate whether impending episodes of intracranial hypertension can be predicted from preceding physiological changes.

This project will explore the challenges of modelling dynamic physiological data in a clinically relevant neurological setting.

---

## Other Machine Learning & Data Science Work

Alongside my clinical projects, I use non-medical datasets to explore machine learning and computational methods across different problem domains.

This includes my earlier **machine-learning capstone project**, coursework, and smaller projects spanning deep learning, SQL, MLOps, and data analysis.

I am also developing an exploratory project investigating **deep-learning approaches to financial time-series and candlestick price prediction**. This remains a **work in progress**, with my current development efforts prioritised toward the neuroscience and neurosurgical projects above.

These projects form part of the same learning process: developing a stronger understanding of computational methods themselves before considering how they can be applied appropriately to biomedical and clinical questions.

---

## Research & Technical Interests

**Neuroscience & Medicine**

Neurosurgery · Neuroscience · Neuro-oncology · Neuroimaging · Neurocritical Care · Clinical Prediction

**Computational & Biomedical**

Computational Biology · Biomedical Data Science · Medical Imaging · Biomedical Signal Processing · Computational Neuroscience

**Machine Learning & AI**

Machine Learning · Deep Learning · Explainable AI · Natural Language Processing · Computer Vision · Time-Series Modelling

**Engineering & Reproducibility**

Python · SQL · PyTorch · MLOps · Model Validation · Reproducible Research

**Medical Technology**

Artificial Intelligence in Medicine · Surgical Technology · Robotics · 3D Printing · Healthcare Design · Brain-Computer Interfaces

---

## About This Portfolio

This portfolio documents the development of my computational work as a clinician working in neurosurgery and developing skills at the intersection of **neuroscience, medicine, machine learning, and computational biology**.

**My clinical background provides the questions; computational methods provide a growing set of tools with which to investigate them.**

For clinical projects, particular attention is given to methodological issues that determine whether an apparently successful model is actually meaningful: **data provenance, information leakage, missing data, appropriate validation, calibration, interpretability, and the limitations of clinical prediction models**.

The objective is not simply to build models with high performance metrics, but to understand **what the models have learned, how reliably they generalise, where they fail, and whether their predictions could ultimately be meaningful in a clinical or biological context**.

Over time, I hope this portfolio will document a progression from foundational machine-learning projects toward increasingly sophisticated work in **computational neuroscience, computational biology, medical AI, and clinically relevant translational research**.
