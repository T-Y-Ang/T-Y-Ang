# Clinician Exploring Machine Learning, AI & Computational Neurosurgery

I am a clinician currently working in neurosurgery, with a broader interest in neuroscience, computational biology, biomedical data science, and the application of emerging technologies to medicine.

This GitHub documents my journey into machine learning, deep learning, computational modelling, and biomedical research — from learning the fundamentals of data science and building my first models to developing increasingly rigorous projects addressing real-world clinical and biological questions.

My clinical experience shapes many of the questions I am interested in exploring computationally. In particular, I am interested in how clinical, imaging, physiological, and anatomical data can be used to better understand neurological disease, investigate biomechanical and haemodynamic processes, predict clinically meaningful outcomes, and support medical decision-making.

My research interests include neuro-oncology, neuroimaging, neurocognition, cerebrovascular disease, brain-computer interfaces, and minimally invasive spine surgery. Exposure to technologies such as robotic-assisted spine surgery has further encouraged my interest in how computational and engineering technologies may influence future clinical practice.

Alongside clinical and research work, I have pursued training in machine learning and artificial intelligence, as well as healthcare design and 3D printing, as part of a broader interest in medical technology and innovation.

My current computational work is primarily focused on neuroscience and neurosurgically relevant problems. More recently, I have begun exploring computational fluid dynamics and structural biomechanics alongside machine learning and deep learning, with the aim of developing a broader set of tools for investigating neurosurgical questions.

Rather than presenting only finished products, I aim to document the process: the code, experiments, unsuccessful approaches, model comparisons, numerical simulations, evaluation methods, and lessons learned while developing these projects.

---

## Featured Projects

### 🧠 Traumatic Brain Injury Outcome Prediction

**Clinical prediction modelling | Machine learning | Explainable AI**

**Status: Completed portfolio study**

**Clinical question:** Can information available during the early assessment of patients with traumatic brain injury predict unfavourable functional outcome at 90 days?

This project investigates conventional statistical and machine-learning approaches to clinical prognostication using clinical and neuroimaging variables from a multinational traumatic brain injury dataset.

The analysis compares logistic regression, Random Forest, and XGBoost, with emphasis on rigorous evaluation rather than predictive performance alone. Particular attention is given to discrimination, calibration, internal validation, information leakage, missing data, and model interpretability.

The underlying research repository remains private while the work is under consideration for further academic dissemination. A standalone report presents the project in an accessible format, including its methodology, results, interpretation, and limitations.

**Methods:** Logistic Regression · Random Forest · XGBoost · ROC-AUC · Calibration · Brier Score · Bootstrap Validation · Explainability

→ [View TBI project report](https://github.com/T-Y-Ang/NES-AI-portfolio/blob/main/projects/tbi-outcome-prediction.md)

---

### 🧠 Glioma MRI Segmentation

**Medical imaging | Deep learning | Computational neuro-oncology**

**Status: Completed**

**Clinical question:** Can deep learning identify and segment tumour-related regions on postoperative multimodal glioma MRI?

This project investigates three-dimensional deep-learning segmentation of postoperative glioma MRI using a multilabel U-Net architecture and the BraTS 2024 GLI dataset.

The repository documents multimodal MRI preprocessing, model development, training, validation, held-out testing, and anatomical interpretation of segmentation errors.

The selected model was evaluated on **198 held-out MRI examinations from 92 subjects**, with subject-level separation from the development cohorts. Validation-informed post-processing improved the four-region macro-average Dice score from **0.6525 to 0.6630**, although anatomical failure analysis identified individual cases in which segmentation performance deteriorated.

The project highlights the importance of interpreting quantitative medical-imaging metrics alongside anatomical findings, reference annotation quality, and clinically relevant limitations.

**Methods:** Python · PyTorch · MONAI · 3D U-Net · Multimodal MRI · Dice Score · Statistical Evaluation · Anatomical Failure Analysis

→ [View Glioma MRI Segmentation project overview](https://github.com/T-Y-Ang/NES-AI-portfolio/blob/main/projects/glioma-mri-segmentation.md)

→ [Explore the public research repository](https://github.com/T-Y-Ang/glioma-mri-segmentation)

---

### 🩸 Intracranial Aneurysm Haemodynamics — Computational Fluid Dynamics

**Cerebrovascular haemodynamics | Computational fluid dynamics | Numerical simulation**

**Status: In progress — preliminary simulations completed**

**Research question:** How does intracranial aneurysm geometry influence local blood-flow behaviour, including velocity distributions, flow recirculation, and wall shear stress?

This project explores computational fluid dynamics (CFD) as a method for investigating the haemodynamic environment of intracranial aneurysms.

The initial phase involved constructing a synthetic three-dimensional sidewall aneurysm, generating a computational mesh, and simulating steady-state laminar blood flow using OpenFOAM.

Preliminary results include:

- Three-dimensional synthetic aneurysm geometry and tetrahedral meshing using Gmsh.
- Successful OpenFOAM simulation with solver residual convergence and a global mass-conservation check.
- Visualisation of velocity distributions, flow streamlines, apparent intra-aneurysmal recirculation, and wall shear stress.
- Extension to a patient-derived left middle cerebral artery bifurcation aneurysm using an openly available TOF-MRA vascular dataset.
- Generation of a patient-derived computational mesh and preliminary flow simulations, including velocity streamline and vorticity visualisations.

The project is now focused on further mesh refinement, numerical verification, boundary-condition assessment, and more detailed haemodynamic analysis.

These simulations are exploratory. Their purpose is to demonstrate computational workflows and investigate flow behaviour, rather than to provide clinically validated estimates of aneurysm rupture risk.

**Methods:** Python · Gmsh · OpenFOAM · ParaView · Finite Volume Method · Computational Meshing · Navier–Stokes Equations · Scientific Visualisation

→ [Explore the Intracranial Aneurysm CFD repository](https://github.com/T-Y-Ang/aneurysm-cfd)

---

## Planned Projects

### 🦴 Spinal Biomechanics — Finite Element Analysis

**Structural biomechanics | Finite element analysis | Computational spine surgery**

**Status: Planned — next major project**

**Research question:** How do structural defects or simulated surgical bone removal alter mechanical loading, deformation, and stiffness in spinal structures?

This project will explore finite element analysis (FEA) as a computational approach to spinal biomechanics, particularly the mechanical consequences of vertebral fractures and surgical removal of stabilising anatomical structures.

The initial demonstration will compare simplified intact and structurally modified models under controlled loading conditions, examining changes in stress distribution, displacement, and mechanical stiffness.

The longer-term objective is to develop more anatomically representative models incorporating vertebral geometry, intervertebral discs, ligamentous constraints, facet joints, and potentially spinal instrumentation.

Such models may eventually support research into post-traumatic or postoperative spinal instability, although meaningful clinical prediction would require substantially more detailed modelling and experimental validation.

**Planned methods:** Finite Element Analysis · Structural Mechanics · Computational Meshing · Material Modelling · Stress and Strain Analysis · Scientific Visualisation

---

### ⚡ EEG Seizure Detection — Future Direction

**Biomedical signal processing | Deep learning | Neuroscience**

A future project investigating detection and classification of epileptic activity using signal-processing and deep-learning methods applied to EEG data.

Potential methods include EEG preprocessing, time-series modelling, patient-level validation, and convolutional neural networks.

This project has been deferred while current development efforts focus on neurovascular CFD and spinal biomechanics.

---

### 📈 Intracranial Pressure Crisis Forecasting — Future Direction

**Physiological time series | Machine learning | Neurocritical care**

A potential future project investigating whether episodes of intracranial hypertension can be anticipated from preceding physiological changes.

This would explore time-series modelling, longitudinal physiological data, and the challenges of predicting clinically significant deterioration.

---

## Other Machine Learning & Data Science Work

Alongside my clinical projects, I use non-medical datasets to explore machine learning and computational methods across different problem domains.

This includes my earlier machine-learning capstone project, coursework, and smaller projects spanning deep learning, SQL, MLOps, and data analysis.

I am also developing an exploratory project investigating deep-learning approaches to financial time-series and candlestick price prediction. This remains a work in progress, with my current development efforts prioritised toward the neuroscience and neurosurgical projects above.

These projects form part of the same learning process: developing a stronger understanding of computational methods themselves before considering how they can be applied appropriately to biomedical and clinical questions.

---

## Research & Technical Interests

**Neuroscience & Medicine**

Neurosurgery · Neuroscience · Neuro-oncology · Neuroimaging · Neurocritical Care · Cerebrovascular Disease · Spinal Surgery · Clinical Prediction

**Computational & Biomedical**

Computational Biology · Biomedical Data Science · Computational Neuroscience · Medical Imaging · Biomedical Signal Processing · Computational Haemodynamics · Biomechanics

**Machine Learning & AI**

Machine Learning · Deep Learning · Explainable AI · Natural Language Processing · Computer Vision · Time-Series Modelling

**Computational Engineering & Simulation**

Computational Fluid Dynamics · Finite Element Analysis · Numerical Methods · Computational Meshing · Structural Mechanics · Scientific Visualisation

**Engineering & Reproducibility**

Python · SQL · PyTorch · MONAI · OpenFOAM · Gmsh · ParaView · MLOps · Model Validation · Reproducible Research

**Medical Technology**

Artificial Intelligence in Medicine · Surgical Technology · Robotics · 3D Printing · Healthcare Design · Brain-Computer Interfaces

---

## About This Portfolio

This portfolio documents the development of my computational work as a clinician working in neurosurgery and developing skills at the intersection of neuroscience, medicine, machine learning, computational biology, and engineering.

**My clinical background provides the questions; computational methods provide a growing set of tools with which to investigate them.**

For machine-learning projects, particular attention is given to methodological issues that determine whether an apparently successful model is meaningful: data provenance, information leakage, missing data, appropriate validation, calibration, interpretability, and generalisability.

For computational simulation projects, similar emphasis is placed on geometric assumptions, material properties, boundary conditions, mesh quality, numerical convergence, reproducibility, and the limitations of translating simulated physical behaviour into clinical conclusions.

The objective is not simply to build models with high performance metrics or generate visually compelling simulations, but to understand what computational methods can reliably demonstrate, where they fail, and what further validation would be required before clinical application.

Over time, I hope this portfolio will document a progression from foundational machine-learning projects towards increasingly sophisticated work in computational neuroscience, computational biology, medical AI, neurovascular haemodynamics, spinal biomechanics, and clinically relevant translational research.
