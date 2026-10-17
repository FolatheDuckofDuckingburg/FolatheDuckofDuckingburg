# 🧠 Folarera Ayobami Kassim

**Independent Researcher · Computational Neuroscience · Brain–Computer Interfaces · Scientific Computing**

> Building, testing, and questioning ideas at the intersection of brains, machines, and mathematical models.

📍 **Lagos, Nigeria / South Carolina, USA**
🏷️ **Pronouns:** she/her
📫 **Email:** [folarera.kassim@gmail.com](mailto\:folarera.kassim@gmail.com)

---

## 🔬 CURRENT RESEARCH

### ⚡ Neural Feedback Optimization Theory (NFOT)

**The Write-Back Gap as a Trial-Level Temporal Variable in Closed-Loop Learning Systems**

NFOT investigates whether the timing and trial-to-trial variability of completed feedback are associated with subsequent performance in closed-loop systems.

The current analysis examines trial-level data from a public P300 brain–computer interface dataset, treating the Write-Back Gap (L) as the interval between a defined starting event and completed feedback.

**Latest analysis — v5**

- 📊 **444 trials** across 15 participants from the public bigP3BCI dataset
- 🎯 **82.9%** overall selection accuracy
- 📉 Negative within-participant association between the Write-Back Gap and selection accuracy

- 🔁 Negative estimated association in all 15 leave-one-subject-out evaluations
- 📈 Adding the trial-level variability measure improved the reported cross-validated AUC from **0.656 to 0.731**

**Current scientific question:** Does trial-to-trial variability in feedback timing provide predictive information beyond mean timing?

**Important limitation:** These are observational findings. They do not establish that manipulating feedback timing causes improved or reduced performance. Prospective testing with controlled timing manipulations is needed.

📄 **Preprint:** [NFOT v5 — Zenodo](https://zenodo.org/records/23140358)
💻 **Repository:** [Noggin-Labs/Neural-Feedback-Optimization-Theory](https://github.com/Noggin-Labs/Neural-Feedback-Optimization-Theory)

> **Hypothesis → Prediction → Measurement → Replication → Falsification**

---

### 🧠 bigP3BCI Analysis

**Trial-level feedback timing and BCI selection accuracy**

Analyzing publicly available P300 BCI data from PhysioNet to investigate relationships between feedback timing and selection outcomes.

**Methods and progress**

- 🧩 Reverse-engineered the event and channel encodings used in Study M.
- 🎯 Decoded `SelectedTarget` using the cell-index mapping.
- 🔎 Distinguished the selected cell from the actual target represented by `CurrentTarget`.
- 📊 Built a trial-level dataset linking feedback timing with selection accuracy.
- 🔁 Evaluated within-participant associations and leave-one-subject-out generalization.
- 🧪 Identified prospective controlled-delay experiments as a necessary next step.

**Goal:** Develop a reproducible, falsifiable analysis of temporal variables in closed-loop BCI performance.

---

### 🤖 Noggimigo

**An open-source Python-based Socratic tutoring engine**

Noggimigo explores how educational software can support structured reasoning by adapting to a learner's expressed reasoning and misconceptions rather than simply supplying answers.

**Core components**

- 🧠 Local intent classification
- 🔎 Structured misconception taxonomy
- 🧩 Learner-accommodation adapters
- ♿ Design considerations for ADHD, autism, and dyslexia
- 🐍 Python-based architecture

**Goal:** Explore adaptive tutoring systems that respond to how a learner approaches a problem, not only whether their answer is correct.

---

### 🌊 Numerical Fluid Dynamics

**Two-dimensional incompressible Navier–Stokes solver**

Developing a lid-driven cavity solver for incompressible flow at Reynolds number (Re=100).

**Methods**

- MAC staggered-grid discretization
- Backward-Euler treatment of diffusion
- Projection method for incompressibility
- Grid-refinement studies
- Comparison with established Ghia et al. benchmark profiles

**Goal:** Evaluate numerical accuracy, convergence, and physical consistency through reproducible tests rather than relying on a single error metric.

---

### ⚛️ Causal Set Theory

Exploring the emergence of spacetime from discrete causal structure.

**Current focus:** Understanding the literature on phase transitions in three-dimensional causal set models and identifying a tractable direction for future numerical investigation.

**Mathematical learning path:**

`Single-variable calculus → Multivariable calculus → Vector calculus → Electrodynamics`

---

## 🛠️ TECHNICAL STACK

### 🐍 Programming

`Python` · `JavaScript` · `TypeScript` · `HTML` · `CSS` · `LaTeX`

### 🧮 Scientific Computing

`NumPy` · `pandas` · `SciPy` · `Matplotlib` · `Jupyter`

### 🧠 Neuroscience and Data

`MNE-Python` · `BIDS` · `EDF` · `P300 BCI` · `PhysioNet`

### 💻 Research Workflow

`Git` · `GitHub` · `Google Colab` · `Reproducible Analysis` · `Statistical Modeling`

---

## 🌱 BUILDING — NOGGIN-LABS

**An independent research and development space** for projects spanning:

- 🧠 Computational neuroscience and closed-loop neural systems
- 🤖 AI and adaptive educational technology
- 💻 Scientific computing and numerical simulation
- 🔬 Reproducible, open-source research

---

## 🔗 RESEARCH LINKS

- **ORCID:** [0009-0007-2148-5675](https://orcid.org/0009-0007-2148-5675)
- **GitHub Organization:** [Noggin-Labs](https://github.com/Noggin-Labs)
- **Contact:** [folarera.kassim@gmail.com](mailto\:folarera.kassim@gmail.com)

---

## 🧪 RESEARCH PHILOSOPHY

*"What's philosophy? I hate philosophy."*

**Measure it. Test it. Question it. Make the evidence reproducible.**

