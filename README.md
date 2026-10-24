# 🧠 Folarera Ayobami Kassim

### Independent Researcher · Computational Neuroscience · Scientific Computing

Exploring how brains learn, how feedback shapes closed-loop systems, and how mathematical models can be tested against evidence.

📍 Lagos, Nigeria / South Carolina, USA · She/her
📫 [Email](mailto\:folarera.kassim@gmail.com) · [GitHub](https://github.com/FolatheDuckofDuckingburg) · [ORCID](https://orcid.org/0009-0007-2148-5675)

**Research interests:** Neural feedback · Brain–computer interfaces · Numerical methods · Adaptive educational AI · Mathematical physics

---

## 🧪 Research at a Glance

| Project            | Focus                                    | Current stage                                      |
| ------------------ | ---------------------------------------- | -------------------------------------------------- |
| ⚡ NFOT             | Feedback timing and closed-loop learning | Observational analysis; prospective testing needed |
| 🧠 bigP3BCI        | Trial-level P300 BCI analysis            | Public-dataset analysis                            |
| 🌊 Cavity-Flow-Lab | Incompressible Navier–Stokes simulation  | Numerical validation                               |
| 🧠 AXIOM           | Python-powered language for computational neuroscience | Early development; LIF simulation and numerical solvers |
| 🤖 Noggimigo       | Socratic tutoring systems                | Research and development                           |
| 🕸️ Graphify       | Programming-language analysis            | Open-source contribution                           |

---

## ⚡ NFOT — Neural Feedback Optimization Theory

**Can the variability of feedback timing help explain performance in closed-loop learning systems?**

NFOT investigates the relationship between the timing of completed feedback and subsequent performance. Its central variable, the **Write-Back Gap** ($L$), is the interval between a defined starting event and the completion of feedback.

### Preliminary findings · v5

Analysis of public bigP3BCI data produced the following reported results:

- **444 trials** across 15 participants
- **82.9%** overall selection accuracy in the analyzed sample
- Negative estimated within-participant association between the Write-Back Gap and selection accuracy
- Negative estimated associations across all 15 leave-one-subject-out evaluations
- Reported cross-validated AUC increased from **0.656 to 0.731** when a trial-level variability measure was added

### What these results mean

These findings are observational. They do not establish that manipulating feedback timing causes performance changes, and predictive improvements require further checks for leakage, model selection, uncertainty, and alternative explanations.

**Next experiment:** Compare controlled feedback-delay distributions with different variability but matched mean delay, then test whether variability adds predictive information beyond mean timing.

🔬 **Research pipeline:** Operational definitions → Reproducible analysis → Falsifiable predictions → Controlled experiment → Independent replication

📄 [Preprint — Zenodo](https://zenodo.org/records/23140358)
💻 [NFOT repository](https://github.com/Noggin-Labs/Neural-Feedback-Optimization-Theory)

---

## 🧠 AXIOM — A Programming Language for Computational Neuroscience

**Python · Domain-specific language (DSL) · Neuron simulation · Numerical methods**

Building AXIOM, a Python-powered scientific programming language designed to make computational neuroscience models more readable, explicit, and reproducible.

The project aims to give neuroscience workflows a clear language for defining neuron models, stimuli, simulation settings, and recorded outputs while retaining access to Python.

### Current implementation

- Readable `.ax` domain-specific language with an interpreter and command-line interface.
- Current-driven Leaky Integrate-and-Fire (LIF) neuron simulation.
- Explicit Forward Euler, RK2 (Midpoint), and RK4 numerical solvers.
- Unit-aware quantities for common neuroscience and simulation units.
- Stimulus abstractions, simulation recording, and CSV export.
- Tests and runnable examples to support development and validation.

### Development approach

AXIOM is under active development. Current capabilities are an initial foundation, not a claim that the language covers all of computational neuroscience. Priorities include readable syntax, tested numerical behavior, clear documentation, and reproducible examples.

💻 **[AXIOM repository](https://github.com/AXIOM-Neuro/AXIOM)** · 📘 [Project README](https://github.com/AXIOM-Neuro/AXIOM#readme)

---

## 🧠 bigP3BCI — Trial-Level BCI Analysis

**Python · P300 BCI · PhysioNet · Statistical modeling**

Investigating how trial-level feedback timing relates to selection outcomes in a publicly available brain–computer interface dataset.

### Implementation and analysis

- Reverse-engineered Study M event and channel encodings.
- Implemented the cell-index mapping for `SelectedTarget`.
- Examined how selected-cell events differ from target information.
- Built a trial-level dataset linking feedback intervals to selection outcomes.
- Evaluated within-participant associations and leave-one-subject-out generalization.
- Identified controlled-delay experiments as the next step toward testing causal hypotheses.

**Research question:** Does feedback-timing variability explain or predict performance beyond average timing?

**Important distinction:** Predictive association in an existing dataset is not proof of a causal mechanism.

---

## 🌊 Cavity-Flow-Lab — Numerical Fluid Dynamics

**Python · NumPy · Numerical PDEs · Scientific computing**

A two-dimensional incompressible Navier–Stokes solver for the lid-driven cavity problem at (Re=100).

### Numerical methods

- MAC staggered-grid discretization
- Backward-Euler treatment of diffusion
- Projection method for incompressibility
- Grid refinement and benchmark comparisons
- Comparison against reference profiles from Ghia et al.

### Reported numerical checks

| Grid           | Velocity (u) RMSE | Velocity (v) RMSE |
| -------------- | ----------------: | ----------------: |
| (32 x 32) |           0.01122 |           0.00862 |
| (64 x 64) |           0.00545 |           0.00339 |

The reported errors decrease with refinement. These values are useful numerical checks, not by themselves proof of convergence or full physical correctness. Further validation includes boundary conditions, pressure–velocity consistency, and systematic refinement studies.

💻 [Cavity-Flow-Lab on GitHub](https://github.com/FolatheDuckofDuckingburg/Cavity-Flow-Lab)

---

## 🕸️ Graphify — Open-Source Contribution

**Python · TypeScript · Abstract syntax trees · Code analysis**

Contributing to Graphify, an open-source knowledge-graph tool for AI-assisted codebase exploration.

My work in this area includes programming-language structure and AST-based analysis, with an interest in how code relationships can be extracted without introducing false or ambiguous inferences.

[**v0.9.32:**](https://github.com/Graphify-Labs/graphify/releases/tag/v0.9.32) Fix: Ruby mixins declared with compact/nested syntax now resolve, and a qualified external mixin can no longer fabricate a phantom hub. `module Foo::Bar` and `module Foo; module Bar` canonicalize to the same label; `extend ActiveSupport::Concern` no longer binds to a local module named `Concern`; a genuine in-corpus `include Foo::Concern` still resolves.

[**v0.9.92**](https://github.com/Graphify-Labs/graphify/releases/tag/v0.9.92)**:** Fix: Ruby mixins declared with compact/nested syntax now resolve, and a qualified external mixin can no longer fabricate a phantom hub. `module Foo::Bar` and `module Foo; module Bar` canonicalize to the same label; `extend ActiveSupport::Concern` no longer binds to a local module named `Concern`; a genuine in-corpus `include Foo::Concern` still resolves.



## 🤖 Noggimigo — Socratic Tutoring Engine

**Python · Educational AI · Adaptive learning**

An open-source tutoring-engine project exploring how educational software can respond to a learner's reasoning and misconceptions instead of simply returning answers.

### Planned and developing components

- Local intent classification
- Structured misconception taxonomy
- Learner-accommodation adapters
- Accessibility considerations for learners with different cognitive and learning needs
- Python-based architecture

**Goal:** Explore tutoring systems that encourage independent reasoning and adapt their questions and explanations to the learner's approach.

[https://github.com/Noggin-Labs/Noggin](https://github.com/Noggin-Labs/Noggin)
[https://github.com/Noggin-Labs/noggimigo](https://github.com/Noggin-Labs/noggimigo)

---

## ⚛️ Foundations of Spacetime

**Causal set theory · Discrete models · Mathematical physics**

Exploring approaches to spacetime based on discrete causal structure, with particular interest in phase transitions in three-dimensional causal set models.

Current work focuses on understanding existing literature, identifying assumptions, and finding a tractable direction for numerical investigation.

This is an evolving research interest, not a claim to have established a new physical theory.

---

## 🛠️ Technical Stack

**Programming:** `Python` · `JavaScript` · `TypeScript` · `HTML` · `CSS` · `LaTeX`

**Scientific computing:** `NumPy` · `pandas` · `SciPy` · `Matplotlib` · `Jupyter`

**Neuroscience and data:** `MNE-Python` · `BIDS` · `EDF` · `P300 BCI` · `PhysioNet`

**Neuroscience software development:** `AXIOM` · `Python DSLs` · `LIF Models` · `Numerical ODE Solvers` · `pytest`\n\n**Development and workflow:** `Git` · `GitHub` · `Visual Studio Code` · `Google Colab` · `AST Analysis` · `Statistical Modeling`

---

## 🌱 Noggin-Labs

**Independent research and development**

Noggin-Labs brings together projects spanning:

- Computational neuroscience and closed-loop neural systems
- Adaptive educational technology
- Scientific computing and numerical simulation
- Reproducible, open-source research

[Noggin-Labs on GitHub](https://github.com/Noggin-Labs)

---

## 📬 Research Links

- **GitHub:** [FolatheDuckofDuckingburg](https://github.com/FolatheDuckofDuckingburg)
- **Research organization:** [Noggin-Labs](https://github.com/Noggin-Labs)
- **AXIOM:** [AXIOM-Neuro/AXIOM](https://github.com/AXIOM-Neuro/AXIOM)
- **ORCID:** [0009-0007-2148-5675](https://orcid.org/0009-0007-2148-5675)
- **NFOT preprint:** [Zenodo](https://zenodo.org/records/23140358)
- **Contact:** [folarera.kassim@gmail.com](mailto\:folarera.kassim@gmail.com)

---

##
