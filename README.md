# Clinician exploring Machine Learning, AI & Computational Biology

I am a clinician currently working in **neurosurgery**, with a broader interest
in **neuroscience, computational biology, and the application of emerging
technologies to medicine**.

This GitHub documents my journey into **machine learning, deep learning,
biomedical data science, and computational research** — from learning the
fundamentals of data science and building my first models to developing
increasingly rigorous projects addressing real-world clinical and biological
questions.

My clinical experience has shaped many of the questions I am interested in
exploring computationally. In particular, I am interested in how clinical,
imaging, physiological, and ultimately biological data can be used to better
understand neurological disease, predict clinically meaningful outcomes, and
support medical decision-making.

My research interests have included areas across **neuro-oncology,
neuroimaging, neurocognition, cerebrovascular disease, neurorehabilitation, and
minimally invasive spine surgery**. Exposure to technologies such as
**robotic-assisted spine surgery** has further encouraged my interest in how
emerging computational and engineering technologies may influence the future
of clinical practice.

Alongside clinical and research work, I have pursued training in **machine
learning and artificial intelligence**, as well as areas including **healthcare
design and 3D printing**, as part of a broader interest in medical technology
and innovation.

My current computational work is primarily focused on **neuroscience and
neurosurgically relevant problems**. I also maintain interests in applying
machine learning outside medicine as a way of developing transferable
technical skills across different types of data and modelling problems.

Rather than presenting only finished products, I aim to document the process:
**the code, experiments, unsuccessful approaches, model comparisons, evaluation
methods, and lessons learned** while developing these projects.

> **[View my Neurosurgery & AI Project Portfolio →](https://github.com/T-Y-Ang/NES-AI-portfolio)**

---

## Current Projects

### 🧠 Glioma MRI Segmentation
**Medical imaging | Deep learning | Computational neuro-oncology**

**Status: In development**

Developing a deep-learning pipeline for automated segmentation of glioma on
multimodal MRI using U-Net-based architectures.

This project extends my work from structured clinical prediction into
**three-dimensional medical imaging and computer vision**, at the intersection
of neurosurgery, neuro-oncology, radiology and computational neuroscience.

The project will examine not only quantitative segmentation performance, but
also visualisation and analysis of segmentation failures. I also intend to
explore how predicted tumour masks can be converted into three-dimensional
models for downstream visualisation and potential **3D-printing workflows**.

---

## Completed Projects

### 🧠 Traumatic Brain Injury Outcome Prediction
**Clinical prediction modelling | Machine learning | Explainable AI**

Can information available during the early assessment of patients with
traumatic brain injury predict unfavourable functional outcome at 90 days?

Using the multinational **GNS-I cohort**, I developed and evaluated logistic
regression, Random Forest and XGBoost models using early clinical and
neuroimaging information.

The project placed particular emphasis on rigorous evaluation rather than
predictive performance alone, including **held-out testing, discrimination,
calibration, Brier score, bootstrap uncertainty, incremental value of imaging,
model comparison, explainability, and assessment of missing follow-up**.

A clinical + imaging Random Forest achieved a held-out **ROC-AUC of 0.854**,
with an average precision of **0.706** and Brier score of **0.114**. Imaging
provided relatively modest incremental discrimination beyond early clinical
information, while Glasgow Coma Scale, pupil reactivity and age were the
dominant contributors to model predictions.

The project reinforced several important principles of clinical prediction
research: more complex algorithms do not necessarily produce meaningfully
better models; discrimination should be considered alongside calibration; and
strong internal performance does not establish clinical generalisability.

**[View the public TBI project showcase →](https://github.com/T-Y-Ang/NES-AI-portfolio/blob/main/projects/tbi-outcome-prediction.md)**

---

## Upcoming Projects

### ⚡ EEG Seizure Detection
**Biomedical signal processing | Deep learning | Neuroscience**

Detection and classification of epileptic activity using signal-processing and
deep-learning methods applied to EEG data.

The project will provide an opportunity to explore computational analysis of
neurophysiological signals and the relationship between machine learning and
**clinical neuroscience**.

### 📈 Intracranial Pressure Crisis Forecasting
**Physiological time series | Machine learning | Neurocritical care**

Time-series modelling of physiological signals to investigate whether impending
episodes of intracranial hypertension can be predicted from preceding
physiological changes.

This project will explore the challenges of modelling dynamic physiological
data in a clinically relevant neurological setting.

---

## Other Machine Learning & Data Science Work

Alongside my clinical projects, I use non-medical datasets to explore machine
learning and computational methods across different problem domains.

This includes my earlier **machine-learning capstone project**, coursework and
smaller projects spanning deep learning, SQL, MLOps, and data analysis.

I am also developing an exploratory project investigating **deep-learning
approaches to financial time-series and candlestick price prediction**. This
remains a **work in progress**, with my current development efforts prioritised
toward the neuroscience and neurosurgical projects above.

These projects form part of the same learning process: developing a stronger
understanding of computational methods themselves before considering how they
can be applied appropriately to biomedical and clinical questions.

---

## Research & Technical Interests

**Neuroscience & Medicine**

Neurosurgery · Neuroscience · Neuro-oncology · Neuroimaging · Neurocritical Care · Clinical Prediction

**Computational & Biomedical**

Computational Biology · Biomedical Data Science · Medical Imaging · Biomedical Signal Processing · Computational Neuroscience

**Machine Learning & AI**

Machine Learning · Deep Learning · Explainable AI · Natural Language Processing · Computer Vision · Time-Series Modelling

**Engineering & Reproducibility**

Python · SQL · MLOps · Model Validation · Reproducible Research

**Medical Technology**

Artificial Intelligence in Medicine · Surgical Technology · Robotics · 3D Printing · Healthcare Design

---

## About This Portfolio

This portfolio documents the development of my computational work as a clinician
working in neurosurgery and developing skills at the intersection of
**neuroscience, medicine, machine learning, and computational biology**.

My clinical background provides the questions; computational methods provide a
growing set of tools with which to investigate them.

For clinical projects, particular attention is given to methodological issues
that can determine whether an apparently successful model is actually
meaningful: **data provenance, information leakage, missing data, appropriate
validation, calibration, interpretability, and the limitations of clinical
prediction models**.

The objective is not simply to build models with high performance metrics, but
to understand **what the models have learned, how reliably they generalise,
where they fail, and whether their predictions could ultimately be meaningful
in a clinical or biological context**.

Over time, I hope this portfolio will document a progression from foundational
machine-learning projects toward increasingly sophisticated work in
**computational neuroscience, computational biology, medical AI, and clinically
relevant translational research**.
