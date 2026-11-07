# Joshua Terranova

**B.Sc. Computer Science** · University of Southern California, Expected May 2028

Undergraduate researcher in USC LiraLab (Prof. Erdem Bıyık) and with Prof. Jiapeng Zhang; Lead Systems Engineer on NASA L'SPACE MCA Team 19 and NPWEE Team 10; autonomy software for University Rover Challenge 2026. I work where ML, robotics, and systems meet real constraints: distribution shift, sparse preference feedback, exact verified reuse, and permanently shadowed lunar operations.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-jterranovacs-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jterranovacs)
[![Website](https://img.shields.io/badge/Portfolio-jcompsci.com-2563EB?style=flat-square&logo=vercel&logoColor=white)](https://www.jcompsci.com)
[![CV](https://img.shields.io/badge/CV-LaTeX-990000?style=flat-square&logo=latex&logoColor=white)](https://github.com/thatrandomasiandev/curriculum-vitae)
[![arXiv](https://img.shields.io/badge/arXiv-2611.02182-b31b1b?style=flat-square&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2611.02182)

---

## Research

| Work | Status | Links |
|------|--------|-------|
| **TARE** — Tool Annotation Reuse, Exact. Black-box pin-and-replay across reference database releases; byte-identical to a full stock rerun or refuse. First author with Prof. Jiapeng Zhang. | Preprint · targeting USENIX OSDI '27 | [`tare`](https://github.com/thatrandomasiandev/tare) · [arXiv:2611.02182](https://arxiv.org/abs/2611.02182) · [project site](https://sites.google.com/usc.edu/tare/home) |
| **LiraLab** — Few-shot latent preference adaptation / PEBBLE Experiment 1 under noisy teachers | Active undergraduate research | [`liralab`](https://github.com/thatrandomasiandev/liralab) · [`liralab-experiment-1`](https://github.com/thatrandomasiandev/liralab-experiment-1) |
| **Visual Compounding Problem** — Closed-loop vision stacks that pass isolated tests and fail when errors couple | Independent benchmark + manuscript prep | [`visual-robot-learning`](https://github.com/thatrandomasiandev/visual-robot-learning) |

---

## ML Research Benchmark Suite

Ten independent, reproducible research frameworks — ~33,000 lines of Python, ~5,300 lines of tests, 310 pytest cases. Each module implements synthetic ground-truth DGPs, YAML-configured benchmarks, and structured evaluation reports. The unifying question: *how do modern ML estimators degrade as their identifying assumptions are systematically violated?*

| # | Module | Description | Repo |
|---|--------|-------------|------|
| 01 | **Causal ML** | Meta-learners (S/T/X/R/Causal Forest), TMLE, NOTEARS, PCMCI, off-policy evaluation | [`causal-ml-decision-making`](https://github.com/thatrandomasiandev/causal-ml-decision-making) |
| 02 | **Foundation Model Adaptation** | LoRA, adapter bottlenecks, prefix tuning, influence functions (LiSSA, TracIn), calibration | [`foundation-model-adaptation`](https://github.com/thatrandomasiandev/foundation-model-adaptation) |
| 03 | **Reinforcement Learning** | CQL, IQL offline RL; CMDP Lagrangian safe RL; ensemble world models; CEM planning | [`reinforcement-learning-real-environments`](https://github.com/thatrandomasiandev/reinforcement-learning-real-environments) |
| 04 | **Bayesian Deep Learning** | Variational BNNs, MC Dropout, deep ensembles, conformal prediction (RAPS), calibration | [`probabilistic-bayesian-deep-learning`](https://github.com/thatrandomasiandev/probabilistic-bayesian-deep-learning) |
| 05 | **Generative Modeling** | DDPM/DDIM, classifier-free guidance, flow matching, diffusion posterior sampling | [`generative-modeling-scientific`](https://github.com/thatrandomasiandev/generative-modeling-scientific) |
| 06 | **Graph ML** | GCN, GAT, GIN, GraphSAGE, DiffPool, temporal GNNs, link prediction | [`graph-ml-relational-systems`](https://github.com/thatrandomasiandev/graph-ml-relational-systems) |
| 07 | **Self-Supervised Learning** | SimCLR, MoCo, BYOL, VICReg, Barlow Twins, MAE; linear probe + k-NN eval | [`self-supervised-representation-learning`](https://github.com/thatrandomasiandev/self-supervised-representation-learning) |
| 08 | **Neurosymbolic Reasoning** | Differentiable forward chaining, neural theorem prover, typed program synthesis | [`neurosymbolic-reasoning`](https://github.com/thatrandomasiandev/neurosymbolic-reasoning) |
| 09 | **Federated & Privacy ML** | FedAvg/FedProx/FedNova, DP-SGD, Rényi DP accounting, pFedMe, secure aggregation | [`federated-privacy-preserving-ml`](https://github.com/thatrandomasiandev/federated-privacy-preserving-ml) |
| 10 | **Scientific ML** | PINNs, E(3)-equivariant GNNs, scVAE, FNO, Bayesian optimization for materials | [`ml-for-science`](https://github.com/thatrandomasiandev/ml-for-science) |

---

## Highlighted Projects

| Project | Description | Repo |
|---------|-------------|------|
| **TARE** | Exact incremental re-annotation wrapper for unmodified CLI tools (HMMER / Infernal bake-offs; refuse path for DIAMOND) | [`tare`](https://github.com/thatrandomasiandev/tare) |
| **SpaAIder** | Local-first multi-agent runtime — TypeScript orchestration, Python FastAPI memory substrate, episodic–semantic–vector memory, dependency-aware parallel scheduling | [`SpaAIder`](https://github.com/thatrandomasiandev/SpaAIder) |
| **URC Autonomy Stack** | ROS 2 (Humble) autonomy for University Rover Challenge 2026 — 7-target mission orchestrator, EKF fusion, GNSS waypoint nav, ArUco visual servoing, YOLO detection | [`urc-cv`](https://github.com/thatrandomasiandev/urc-cv) |
| **ClinRad-Bench** | Clinical ML evaluation under prevalence shift (2% / 12% / 35%), calibration (ECE), selective prediction, bootstrap CIs | [`ClinRad-Bench`](https://github.com/thatrandomasiandev/ClinRad-Bench) |
| **KumonScan** | Desk + QR attendance for Kumon centers (Neon Postgres, Math / Reading / Both session rules, timeapi.io clock) | [`KumonScan`](https://github.com/thatrandomasiandev/KumonScan) |
| **Curriculum Vitae** | LaTeX academic CV (auto-compiled) | [`curriculum-vitae`](https://github.com/thatrandomasiandev/curriculum-vitae) |

---

<sub>Curated featured work. GitHub pins only six repos; this profile is the full directory.</sub>
