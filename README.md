<div align="center">

# Shreyansh Singh
### Founder & Chief AI Systems Architect @ ExperimentLab

[![Website](https://img.shields.io/badge/Website-experimentlab.in-000000?style=flat&logo=firefox&logoColor=white)](https://experimentlab.in)
[![GitHub Org](https://img.shields.io/badge/GitHub_Org-Vigyan--workstation-000000?style=flat&logo=github&logoColor=white)](https://github.com/Vigyan-workstation)
[![Flagship Workstation](https://img.shields.io/badge/Flagship_Repository-vigyan--pro_v4.0.0-18181b?style=flat&logo=linux&logoColor=white)](https://github.com/Vigyan-workstation/vigyan-pro)
[![Hugging Face Org](https://img.shields.io/badge/Hugging_Face-Experimentlab-ffd21e?style=flat&logo=huggingface&logoColor=black)](https://huggingface.co/Experimentlab)
[![Personal Models](https://img.shields.io/badge/Models-47_Published-00ffcc?style=flat&logo=huggingface&logoColor=black)](https://huggingface.co/shreyansh12183)
[![Back Research](https://img.shields.io/badge/Back_Research-Buy_Me_A_Chai-d97706?style=flat)](https://buymeachai.in/shreyansh001boy)
[![Discord](https://img.shields.io/badge/Discord-Experimentlab_Community-5865F2?style=flat&logo=discord&logoColor=white)](https://discord.com/invite/Jck3tD6mhf)
[![License](https://img.shields.io/badge/License-PolyForm_Noncommercial_1.0.0-blue.svg?style=flat)](https://github.com/Vigyan-workstation/vigyan-pro/blob/main/LICENSE)

<p align="center">
  <b>Architecting sovereign Small Language Models (SLMs), ternary 1.58-bit BitNet models, and air-gapped physical engineering workstations that run 100% locally on existing client hardware.</b>
</p>

</div>

---

## Executive Overview

I design, train, and deploy sovereign foundation models and offline engineering environments for physical engineers, semiconductor designers, mathematicians, and autonomous coding agents.

My research addresses the fundamental failure modes of cloud AI: telemetry data leakage, recurring token costs, and probabilistic mathematical hallucination. By pairing lightweight, domain-adapted SLMs with an in-process, sandboxed Computer Algebra System (SymPy CAS), our systems deliver deterministic mathematical and physical accuracy with zero cloud round-trips.

* **47 Published Models & Adapters**: Spanning semiconductor RTL design, pure mathematics, orbital mechanics, biochemistry, and Indian statutory law.
* **5,400+ Organic Downloads**: Adopted by independent researchers, academic labs, and physical engineering teams.
* **100% Air-Gapped Workstations**: Engineered to run efficiently on low-power consumer silicon (under 4 GB RAM) without discrete GPUs.
* **5 Foundation Research Volumes**: Empirical scaling laws, Sparse MoE routing, and deterministic neuro-symbolic benchmarks published on Kaggle.

---

## Flagship Platform: Vigyan Pro v4.0.0

The flagship workstation is developed under our sovereign organization: **[Vigyan-workstation/vigyan-pro](https://github.com/Vigyan-workstation/vigyan-pro)**.

### Architectural Core
1. **Deterministic SymPy CAS Kernel**:
   All calculus, algebraic derivations, and matrix equations are evaluated through an in-process AST sandbox (`validate_sympy_ast`), eliminating hallucinated arithmetic.
2. **First-Class GGUF Model Management CLI**:
   Built-in model supervisor to check host RAM headroom, query Hugging Face Hub, and stream quantized weights directly to disk:
   ```bash
   vigyan model status
   vigyan model list --remote
   vigyan model pull vigyan-2b-reasoning-q4_k_m.gguf
   ```
3. **Autonomous Learning Ledger**:
   Reversible in-context memory ledger (`vigyan learn`, `vigyan ledger`, `vigyan undo`) backed by git history with a strict 150-line telemetry budget.
4. **Universal AI Coding Agent Directives**:
   Fully certified instructions for autonomous development agents (`AGENTS.md`, `CLAUDE.md`, `.cursorrules`, Copilot instructions) with multi-platform CI passing across Linux, macOS, and Windows.

---

## Foundation Research Papers (2026)

* **Volume 01: Sparse MoE Upcycling & Router Stabilization**  
  [Read on Kaggle](https://www.kaggle.com/datasets/shreyansh00singh/vigyan-moe-upcycling-research-paper)
* **Volume 02: Depth Up-Scaling (DUS) & Seam Healing**  
  [Read on Kaggle](https://www.kaggle.com/datasets/shreyansh00singh/vigyan-dus-seam-healing-research-paper)
* **Volume 03: Tool-Augmented Direct Preference Optimization**  
  [Read on Kaggle](https://www.kaggle.com/datasets/shreyansh00singh/vigyan-tool-dpo-symbolic-grounding-paper)
* **Volume 04: Test-Time Compute Elicitation via GRPO**  
  [Read on Kaggle](https://www.kaggle.com/datasets/shreyansh00singh/vigyan-grpo-reasoning-rl-paper)
* **Volume 05: Neuro-Symbolic Hybrid Evaluation Harness**  
  [Read on Kaggle](https://www.kaggle.com/datasets/shreyansh00singh/vigyan-neuro-symbolic-eval-paper)

---

## Interactive 1-Click Demos (Google Colab T4)

Each demo launches an interactive Gradio session on a free Google Colab Tesla T4 instance:

| Model | Domain & Architecture | Footprint | Interactive Demo |
| :--- | :--- | :---: | :---: |
| [**Vidhi AI 1.5B Masterpiece**](https://huggingface.co/shreyansh12183/vidhi-ai-1.5b-sovereign-masterpiece) | Indian Law, BNS/BNSS 2023 Statutory Mapping | 1.06 GB | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/shreyansh001boy-tech/97736d594721ab8e37912cd381fdf968/colab_demo_vidhi_1_5b.ipynb) |
| [**Vigyan 7B Quad-Master**](https://huggingface.co/shreyansh12183/vigyan-olmo2-7b-quad-master) | SLERP Merge of 4 Specialists (Math, RTL, Bio, Astro) | 4.26 GB | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/shreyansh001boy-tech/94f86027e672aa60dbda383eca6cf122/colab_demo_vigyan_7b_quad_master.ipynb) |
| [**Vigyan OLMoE 1B-7B DPO**](https://huggingface.co/shreyansh12183/vigyan-olmoe-1b-7b-dpo-masterpiece) | Sparse MoE (1.3B active params/token), STEM Reasoning | 4.02 GB | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/shreyansh001boy-tech/1222eec06995b9b046bb76096495a653/colab_demo_vigyan_olmoe_1b_7b.ipynb) |
| [**Vigyan 1.5B 4x-MoE**](https://huggingface.co/shreyansh12183/Vigyan-1.5B-4x-MoE) | 4-Expert Sparse MoE running smoothly under 1 GB RAM | 0.98 GB | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/shreyansh001boy-tech/18daf8e5416d3e25ca0065b9052e1688/colab_demo_vigyan_1_5b_moe.ipynb) |
| [**olmo2-7b-phd-pure-math**](https://huggingface.co/shreyansh12183/olmo2-7b-phd-pure-math) | Advanced Mathematics, Topology & Formal Proofs | 4.10 GB | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/shreyansh001boy-tech/f13664784d899f9a72509d6003b3b791/colab_demo_olmo2_pure_math.ipynb) |
| [**olmo2-7b-silicon-rtl-eda**](https://huggingface.co/shreyansh12183/olmo2-7b-silicon-rtl-eda) | Synthesizable Verilog HDL & Semiconductor EDA | 4.10 GB | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/shreyansh001boy-tech/d7e16e7f902372db11ba5b9490f28adf/colab_demo_olmo2_silicon_rtl.ipynb) |
| [**olmo2-7b-biomed-chem**](https://huggingface.co/shreyansh12183/olmo2-7b-biomed-chem) | Molecular Chemistry, Pharmacology & Kinetics | 4.10 GB | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/shreyansh001boy-tech/12fa1afcfe242451f0f2d31a1ccccd58/colab_demo_olmo2_biomed_chem.ipynb) |
| [**olmo2-7b-astro-logic**](https://huggingface.co/shreyansh12183/olmo2-7b-astro-logic) | Celestial Mechanics & Relativistic Physics | 4.10 GB | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/shreyansh001boy-tech/6a524659f571f0cd0ed5d218868a4863/colab_demo_olmo2_astro_logic.ipynb) |

---

## Foundation Datasets on Hugging Face

* [**shreyansh-1B-SLM-pretrain-stem-english**](https://huggingface.co/datasets/shreyansh12183/shreyansh-1B-SLM-pretrain-stem-english): 1 Billion token pretraining corpus balanced for cold-start STEM intelligence.
* [**shreyansh-hinglish-english-stem-500k**](https://huggingface.co/datasets/shreyansh12183/shreyansh-hinglish-english-stem-500k): 500,000 sample bilingual Hinglish-English dataset for engineering education.
* [**vigyan-ai-research-papers**](https://huggingface.co/datasets/Experimentlab/vigyan-ai-research-papers): Technical literature and empirical benchmarks.

---

## Back Sovereign Open-Source Research

Independent foundation model pretraining, mathematical AST verification, and edge SLM optimization require continuous compute. If our open-weight models, datasets, or offline workstations support your work or research, you can support our independent civilian STEM lab via [Buy Me A Chai](https://buymeachai.in/shreyansh001boy).

---

## Community & Discussions

Real-time technical discussions, architecture brainstorming, and workstation support:
* **Discord Guild**: [Experimentlab Community](https://discord.com/invite/Jck3tD6mhf) (65+ Members)
* **GitHub Organization**: [@Vigyan-workstation](https://github.com/Vigyan-workstation)
* **Hugging Face Hub**: [@Experimentlab](https://huggingface.co/Experimentlab) · [@shreyansh12183](https://huggingface.co/shreyansh12183)

---

## Legal, Intellectual Property & Non-Commercial Licensing

All models, benchmark suites, pretraining datasets, research papers, and software released across the Vigyan and ExperimentLab ecosystems are governed by the **PolyForm Noncommercial License 1.0.0**:

* **Academic, Educational & Personal Research Use**: Free to inspect, evaluate, run offline, and modify for non-commercial scientific research.
* **AI Model Distillation Restriction (Section 8)**: You may not use any model outputs, datasets, code, or documentation to train, fine-tune, distill, or evaluate competing artificial intelligence or foundation models without prior written permission.
* **Trademark Protection (Section 9)**: No trademark, service mark, or brand rights in "ExperimentLab AI" or "Vigyan Pro" are granted.
* **Commercial Enterprise Licensing**: For commercial licensing, enterprise deployment, or OEM integration, contact **support@experimentlab.in**.

---

## Academic Attribution & Citation

```bibtex
@article{singh2026vigyan,
  title={Vigyan Sovereign Trilogy: Empirical Scaling Laws and Deterministic Symbolic-AST Evaluation of Edge Small Language Models},
  author={Singh, Shreyansh},
  institution={ExperimentLab AI Open Research},
  year={2026},
  url={https://github.com/Vigyan-workstation/vigyan-pro}
}
```

---

<div align="center">
  <sub>Developed by <a href="https://experimentlab.in">ExperimentLab AI</a>. Built for physical engineers who value sovereignty and mathematical precision.</sub>
</div>
