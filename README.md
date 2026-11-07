# Folarera Kassim

### Independent Researcher | Computational Neuroscience · Neural Engineering · Theoretical Physics

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Scientific_Computing-4B8BBE?style=for-the-badge" alt="Scientific Computing" />
  <img src="https://img.shields.io/badge/Neuroscience-6A5ACD?style=for-the-badge" alt="Neuroscience" />
</p>

I work at the intersection of neuroscience, mathematics, physics, computation, and intelligent systems.

My interests include computational models of neural systems, temporal credit assignment, brain–computer interfaces, numerical simulation, causal set theory, string theory, and educational AI.

I build scientific software, investigate research questions, and develop computational methods with an emphasis on reproducibility, explicit assumptions, and testable results.

📍 Lagos, Nigeria / South Carolina, USA · She/her

[GitHub](https://github.com/FolatheDuckofDuckingburg) · [ORCID](https://orcid.org/0009-0007-2148-5675) · [Email](mailto:folarera.kassim@gmail.com)

---

## Research at a Glance

| Project | Area | Focus |
|---|---|---|
| ⚡ NFOT | Computational Neuroscience | Feedback timing and temporal credit assignment |
| 🧠 AXIOM | Scientific Programming | A programming language for computational neuroscience |
| 🔬 RADIANT | AI Evaluation | Reasoning and evidence evaluation in AI tutoring |
| 🤖 Noggimigo | Educational AI | Local-model-assisted Socratic tutoring |
| 🌊 Cavity-Flow-Lab | Computational Physics | Numerical Navier–Stokes simulation |
| 🕸️ Graphify | Software Engineering | AST-based code analysis and knowledge graphs |

---

## ⚡ Neural Feedback Optimization Theory (NFOT)

**Research areas:** Computational Neuroscience · Brain–Computer Interfaces · Closed-Loop Learning

NFOT investigates how feedback timing relates to performance in closed-loop neural and learning systems.

A central concept is the **Write-Back Gap**: the time interval between the initial stimulus onset and the completion of feedback.

It is operationally measured using two timestamps:

- **Stimulus onset:** the first recorded onset of a stimulus.
- **Feedback completion:** the rising edge of `DisplayResults`, marking the completion of the feedback event.

The research explores connections between temporal credit assignment, eligibility traces, neuromodulatory timing, and feedback-dependent learning.

### Research development

- Operationalization of the Write-Back Gap.
- Analysis of public bigP3BCI data.
- Participant-level statistical analysis.
- Leave-one-subject-out evaluation.
- Investigation of temporal variability as a potential predictive feature.
- Provenance and reproducibility auditing.

### Research status

The v5 analysis produced preliminary observational findings. The current **v6** research iteration focuses on provenance, methodological scrutiny, and strengthening the evidential foundation.

A major experimental direction is the **Paired Temporal Stability Protocol (PTSP)**.

PTSP investigates feedback-delay distributions with matched means but different levels of variability. Its purpose is to test whether temporal variability contributes information beyond average feedback timing.

The experiment does not assume that lower variability is inherently beneficial. That relationship remains a question to investigate.

**Current priorities:**

- Establish reproducibility.
- Audit data provenance and analytical decisions.
- Test falsifiable predictions.
- Distinguish exploratory observations from confirmatory evidence.
- Develop controlled experimental validation.

**Research links:**

- [NFOT Research Repository](https://github.com/Noggin-Labs/Neural-Feedback-Optimization-Theory)
- [Historical Preprint — Zenodo](https://zenodo.org/records/23140358)

---

## 🧠 AXIOM — Computational Neuroscience Programming Language

**Python · C++ · Scientific Computing · Domain-Specific Languages**

AXIOM is a scientific programming language project designed to make computational neuroscience models explicit, readable, and reproducible.

The project explores a Python-powered language with dedicated syntax for describing neural models, simulation parameters, stimuli, and recorded outputs.

### Implemented foundations

- `.ax` domain-specific language.
- Interpreter and command-line interface.
- Leaky Integrate-and-Fire neuron simulation.
- Forward Euler, RK2, and RK4 numerical integration.
- Unit-aware quantities.
- Stimulus and recording abstractions.
- CSV output.
- Automated tests and executable examples.

### Development direction

- Numerical correctness and solver validation.
- Expanded neuron-model support.
- Python and C++ implementation work.
- Scientific workflow interoperability.
- Improved simulation abstractions and documentation.

**Repository:** [AXIOM-Neuro/AXIOM](https://github.com/AXIOM-Neuro/AXIOM)

---

## 🔬 RADIANT — Reasoning and Evidence Evaluation

**Artificial Intelligence · Educational Technology · Evaluation**

RADIANT explores the evaluation of reasoning and evidence in AI-powered tutoring systems.

The central research interest is moving beyond answer accuracy toward examining whether a tutoring system can provide justified, evidence-supported reasoning.

### Research directions

- Reasoning quality evaluation.
- Evidence-grounded explanations.
- Answer verification.
- Assessment of tutoring responses.
- Reliability and consistency.
- Evaluation frameworks for educational AI.

The broader objective is to investigate how intelligent tutoring systems can be evaluated for more than their ability to produce plausible answers.

**Meet our lab rat, Noggin:** [Noggin-Labs](https://github.com/Noggin-Labs)

---

## 🤖 Noggimigo — Socratic Tutoring Engine

**Python · Local Language Models · Educational AI**

Noggimigo is an open-source tutoring-engine project exploring reasoning-oriented educational software.

Its architecture combines deterministic verification with optional language-model assistance.

### Current development

- Local Hugging Face model integration.
- Structured tutoring interactions.
- Deterministic answer verification.
- Optional language-model-generated explanations.
- Socratic tutoring.
- Learner accessibility and accommodation considerations.

The system explores how software can guide learners through problems without making language-model-generated answers the authority on correctness.

**Repository:** [Noggin-Labs/Noggimigo](https://github.com/Noggin-Labs/Noggimigo)

---

## 🌊 Cavity-Flow-Lab — Computational Fluid Dynamics

**Python · NumPy · Numerical PDEs · Computational Physics**

Cavity-Flow-Lab is a numerical solver for the two-dimensional incompressible Navier–Stokes equations, using the lid-driven cavity problem.

### Numerical methods

- MAC staggered-grid discretization.
- Projection method.
- Backward-Euler diffusion treatment.
- Grid refinement.
- Comparison against Ghia et al. reference profiles.

### Reported numerical results

| Grid | u RMSE | v RMSE |
|---|---:|---:|
| 32 × 32 | 0.01122 | 0.00862 |
| 64 × 64 | 0.00545 | 0.00339 |

The reduction in reported errors with grid refinement provides an initial numerical validation result. Further systematic convergence and physical-consistency checks remain important.

**Repository:** [Cavity-Flow-Lab](https://github.com/FolatheDuckofDuckingburg/Cavity-Flow-Lab)

---

## 🕸️ Graphify — Open-Source Software Engineering

**Python · TypeScript · AST Analysis · Knowledge Graphs**

Contributing to Graphify, an open-source project for AI-assisted codebase exploration.

My interests in this area include extracting meaningful programming-language relationships, resolving syntax variations, and preventing false connections in generated code graphs.

Selected contributions include Ruby mixin-resolution improvements and TypeScript `this.field` inference improvements.

**Selected links:**

- [Graphify Repository](https://github.com/Graphify-Labs/graphify)
- [Release v0.9.32](https://github.com/Graphify-Labs/graphify/releases/tag/v0.9.32)
- [Release v0.9.92](https://github.com/Graphify-Labs/graphify/releases/tag/v0.9.92)

---

## ⚛️ Mathematical Physics

**Causal Set Theory · String Theory · Numerical Methods · Theoretical Physics**

Exploring mathematical approaches to fundamental questions in physics, with particular interests in discrete spacetime, causal set theory, and string theory.

### Current interests

- Discrete causal structures.
- Mathematical foundations of spacetime.
- Phase transitions in three-dimensional causal set models.
- Computational approaches to theoretical models.
- Numerical investigation of discrete systems.
- Mathematical structures underlying physical theories.

This remains an exploratory research direction grounded in studying existing literature and identifying tractable mathematical and computational questions.

---

## Technical Interests & Tools

**Programming Languages**

`Python` · `C++` · `JavaScript` · `TypeScript` · `LaTeX`

**Scientific Computing**

`NumPy` · `SciPy` · `pandas` · `Matplotlib` · `Jupyter` · `Google Colab`

**Neuroscience**

`MNE-Python` · `BIDS` · `EDF` · `P300 BCI` · `PhysioNet`

**AI & Machine Learning**

`Hugging Face` · `PyTorch` · `Local Language Models` · `Model Evaluation`

**Development**

`Git` · `GitHub` · `VS Code` · `pytest` · `Node.js` · `Next.js`

---

## Noggin-Labs

**Independent Research & Development**

Noggin-Labs is an independent research and software-development initiative focused on:

- Computational neuroscience.
- Neural feedback and closed-loop systems.
- Brain–computer interfaces.
- Scientific programming.
- Adaptive educational technology.
- Reproducible computational research.

[Explore Noggin-Labs](https://github.com/Noggin-Labs)

---

<p align="center">
  <a href="https://github.com/FolatheDuckofDuckingburg">
    <img src="https://img.shields.io/badge/GitHub-FolatheDuckofDuckingburg-181717?style=for-the-badge&logo=github" alt="GitHub profile" />
  </a>
  <a href="https://orcid.org/0009-0007-2148-5675">
    <img src="https://img.shields.io/badge/ORCID-0009--0007--2148--5675-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID profile" />
  </a>
</p>
