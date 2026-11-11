<div align="center">

# Shreyansh Singh
### Founder & Chief AI Systems Architect @ ExperimentLab

[![Website](https://img.shields.io/badge/Website-experimentlab.in-000000?style=flat&logo=firefox&logoColor=white)](https://experimentlab.in)
[![GitHub Org](https://img.shields.io/badge/GitHub_Org-Vigyan--workstation-000000?style=flat&logo=github&logoColor=white)](https://github.com/Vigyan-workstation)
[![Flagship Workstation](https://img.shields.io/badge/Flagship_Workstation-Vigyan_Pro_v4.1.0-18181b?style=flat&logo=linux&logoColor=white)](https://github.com/Vigyan-workstation/vigyan-pro)
[![Hugging Face Org](https://img.shields.io/badge/Hugging_Face-Experimentlab-ffd21e?style=flat&logo=huggingface&logoColor=black)](https://huggingface.co/Experimentlab)
[![Personal Models](https://img.shields.io/badge/HF_Fleet-47_Published-00ffcc?style=flat&logo=huggingface&logoColor=black)](https://huggingface.co/shreyansh12183)
[![Kaggle Research](https://img.shields.io/badge/Kaggle-shreyansh00singh-20BEFF?style=flat&logo=kaggle&logoColor=white)](https://www.kaggle.com/shreyansh00singh)
[![Back Research](https://img.shields.io/badge/Back_Research-Buy_Me_A_Chai-d97706?style=flat)](https://buymeachai.in/shreyansh001boy)
[![Discord](https://img.shields.io/badge/Discord-Experimentlab_Community-5865F2?style=flat&logo=discord&logoColor=white)](https://discord.com/invite/Jck3tD6mhf)
[![License](https://img.shields.io/badge/License-PolyForm_Noncommercial_1.0.0-blue.svg?style=flat)](https://github.com/Vigyan-workstation/vigyan-pro/blob/main/LICENSE)

<p align="center">
  <b>Architecting sovereign Small Language Models (SLMs), ternary 1.58-bit BitNet models, multimodal engineering vision, and air-gapped physical engineering workstations that run 100% locally on existing client hardware.</b>
</p>

</div>

---

## Executive Overview & Research Pillars

I design, train, and deploy sovereign foundation models and offline engineering environments for physical engineers, semiconductor designers, clinical researchers, and autonomous coding agents.

My research addresses the fundamental failure modes of cloud AI: telemetry data leakage, recurring token costs, and probabilistic mathematical hallucination. By pairing lightweight, domain-adapted SLMs with an in-process, sandboxed Computer Algebra System (SymPy CAS), our systems deliver deterministic mathematical and physical accuracy with zero cloud round-trips.

```
┌──────────────────────────────────────────────────────────────────────────────────┐
│                           THE 4 SOVEREIGN RESEARCH PILLARS                       │
├──────────────────────────┬────────────────────────────┬──────────────────────────┤
│ 1. 1.58-Bit Ternary BitNet│ 2. Multimodal Engineering  │ 3. Deep Clinical & STEM  │
│ • Straight-Through Estim.│ • Qwen3-VL 4B Vision       │ • DeepSeek-R1 14B Health │
│ • 125M Canary Fleet      │ • Schematics & CAD OCR     │ • Olmo-3.1 32B Titan     │
│ • GGUF IQ1_S to Q4_K_M   │ • Micro-footprint LoRA     │ • SymPy CAS Grounding    │
├──────────────────────────┴────────────────────────────┴──────────────────────────┤
│ 4. Sovereign Desktop Workstation (Vigyan Pro v4.1.0)                             │
│ • 100% Offline Physical Air-Gap • build123d 3D CAD STL • SciPy RK45 Multiphysics│
│ • RDKit Cheminformatics • Typst Vector PDF Engine (<50ms) • WebKitGTK / WebView2 │
└──────────────────────────────────────────────────────────────────────────────────┘
```

* **47 Published Models & Adapters**: Spanning ternary 1.58-bit bitnets, semiconductor RTL design, pure mathematics, clinical health, and orbital mechanics.
* **5,400+ Organic Downloads**: Adopted by independent researchers, academic labs, and physical engineering teams.
* **100% Air-Gapped Workstations**: Engineered to run efficiently on low-power consumer silicon (under 4 GB RAM) without discrete GPUs.
* **5 Foundation Research Volumes**: Empirical scaling laws, Sparse MoE routing, and deterministic neuro-symbolic benchmarks published on Kaggle.

---

## 🔬 Pillar 1: 1.58-Bit Ternary BitNet Foundations (125M Canary Suite)

We engineer extreme low-bit ternary foundation architectures where weights are restricted to $\\{-1, 0, +1\\}$, replacing power-hungry matrix multiplications with energy-efficient integer addition:

- **Pretrained from Scratch from Token Zero**: Cold-start foundation pretraining initialized from scratch with random weights (NOT an adaptation, fine-tune, or distillation of Llama or any external model) using BitNet straight-through estimators (STE).
- **Ultra-Low Memory Execution**: The entire 125M ternary model runs in **~40–60 MB RAM**, enabling high-speed deterministic inference on microcontrollers, Raspberry Pis, Rockchip NPUs, and standard laptop CPUs.
- **Kaggle Cloud TPU v3-8 Pretraining**: Cold-start pretraining recipes engineered on Google Cloud TPUs utilizing non-blocking PJRT checkpointing and strict static shape compilation.
- **Open-Access Model Suite**:
  - [`shreyansh12183/vigyan-125m-158bit-canary`](https://huggingface.co/shreyansh12183/vigyan-125m-158bit-canary) — Native 1.58-bit ternary BitNet foundation model (pretrained from token zero scratch).
  - [`shreyansh12183/vigyan-125m-158bit-gguf`](https://huggingface.co/shreyansh12183/vigyan-125m-158bit-gguf) — Complete quantization suite (`iq1_s`, `iq2_xxs`, `q2_k`, `q4_k_m`, `fp16`).
  - [`shreyansh12183/vigyan-125m-sota-math`](https://huggingface.co/shreyansh12183/vigyan-125m-sota-math) — Certified mathematical reasoning canary with formal scorecards.
  - [`shreyansh12183/vigyan-125m-agentic-tool`](https://huggingface.co/shreyansh12183/vigyan-125m-agentic-tool) — Atomic tool invocation canary for SymPy CAS integration.
  - [`shreyansh12183/vigyan-125m-distilled`](https://huggingface.co/shreyansh12183/vigyan-125m-distilled) — Stage 1 and Stage 2 R1 distillation checkpoints.
  - [`shreyansh12183/vigyan-indic-stem-tokenizer`](https://huggingface.co/shreyansh12183/vigyan-indic-stem-tokenizer) — Custom BPE tokenizer tailored for Indian STEM literature.

---

## 👁️ Pillar 2: Multimodal Engineering Vision (Vigyan-VL-4B)

Technical engineering workflows demand visual intelligence to inspect physical blueprints, electronic circuits, and medical charts:

- [`shreyansh12183/vigyan-vl-4b-instruct`](https://huggingface.co/shreyansh12183/vigyan-vl-4b-instruct) — High-density vision-language adapter built on `Qwen/Qwen3-VL-4B-Instruct`.
- **Engineering Capabilities**:
  - Procedural extraction from scanned KiCad PCB schematics and netlists.
  - Dimension and tolerance parsing from mechanical CAD drawings.
  - Handwritten prescription OCR and clinical document transcription.

---

## 🧬 Pillar 3: Clinical & Biophysics Deep Reasoning (DeepSeek-R1 14B & 32B Titan)

To bridge the gap between statistical LLMs and rigorous scientific truth, we integrate deep chain-of-thought distillation with deterministic symbolic solvers:

- **DeepSeek-R1 14B Clinical Suite**:
  - [`shreyansh12183/vigyan-r1-14b-health-semi-quantum-sft`](https://huggingface.co/shreyansh12183/vigyan-r1-14b-health-semi-quantum-sft) — Supervised Fine-Tuning for medical pathology, pharmacology, and biophysics.
  - [`shreyansh12183/vigyan-r1-14b-health-semi-quantum-dpo`](https://huggingface.co/shreyansh12183/vigyan-r1-14b-health-semi-quantum-dpo) — Direct Preference Optimization eliminating clinical reasoning shortcuts.
  - [`shreyansh12183/vigyan-r1-14b-health-semi-quantum-gguf`](https://huggingface.co/shreyansh12183/vigyan-r1-14b-health-semi-quantum-gguf) — **6.60 GB Standalone IQ3_M GGUF** for completely private hospital oncology and clinical research workstations.
- **Frontier 32B Scale**:
  - [`shreyansh12183/vigyan-gen4-32b-sft-adapter`](https://huggingface.co/shreyansh12183/vigyan-gen4-32b-sft-adapter) — 32B parameter symbolic reasoning adapter on `allenai/Olmo-3.1-32B-Instruct` for doctoral mathematics and complex VLSI synthesis.

---

## 💻 Pillar 4: Sovereign Desktop Workstation (Vigyan Pro v4.1.0)

The flagship physical engineering workstation is developed under our sovereign organization: **[Vigyan-workstation/vigyan-pro](https://github.com/Vigyan-workstation/vigyan-pro)**.

### Architectural Core
1. **Deterministic SymPy CAS Kernel**:
   All calculus, algebraic derivations, and matrix equations are evaluated through an in-process AST sandbox (`validate_sympy_ast`), eliminating hallucinated arithmetic.
2. **Parametric 3D CAD (`vigyan cad`)**:
   Embedded `build123d` and `OpenCASCADE` engine generating manufacturing-ready STL solid meshes on-device with an interactive Three.js turntable viewport.
3. **SciPy RK45 Multiphysics (`vigyan sim`)**:
   Dynamic 60 FPS trajectory simulator solving non-linear ODEs with interactive parameter sliders.
4. **RDKit Cheminformatics (`vigyan chem`)**:
   Molecular descriptor evaluation (MW, LogP, TPSA) and vector SVG chemical bond rendering.
5. **Sub-50ms Typst PDF Engine**:
   Embedded vector compiler generating publication-ready academic papers with SymPy verification badges.
6. **First-Class GGUF Model Management CLI**:
   Built-in model supervisor to check host RAM headroom, query Hugging Face Hub, and stream quantized weights directly to disk with a 10-minute idle RAM reaper:
   ```bash
   vigyan model status
   vigyan model list --remote
   vigyan model pull vigyan-2b-reasoning-q4_k_m.gguf
   ```
7. **Autonomous Learning Ledger**:
   Reversible in-context memory ledger (`vigyan learn`, `vigyan ledger`, `vigyan undo`) backed by git history with a strict 150-line telemetry budget.
8. **Universal AI Coding Agent Directives**:
   Fully certified instructions for autonomous development agents (`AGENTS.md`, `CLAUDE.md`, `.cursorrules`, Copilot instructions) with multi-platform CI passing across Linux, macOS, and Windows.

---

## 🏛️ Sovereign Fleet Benchmark Matrix

| Fleet Tier | Parameters | Base Scaffold | Exam Suite | Score / Metric | Binary Size | Primary Specialization |
| :--- | :---: | :--- | :--- | :---: | :---: | :--- |
| **Vigyan-125M** ⚡ | 125M | `Native BitNet b1.58 (Pretrained from Scratch)` | Atomic Math & Tools | **Certified STE** | **~50 MB** | 1.58-bit ternary edge canary, microcontrollers |
| **Vigyan-1.5B** | 1.54B | `DeepSeek-R1-Distill-1.5B` | 100 Frontier STEM | **43.0%** | **1.11 GB** | Ultra-light edge scout, IoT, PhD Math (75.0%) |
| **Vigyan-3B** 🚀 | 3.09B | `Qwen2.5-3B-Instruct` | 100 Frontier STEM | **69.0%** | **1.39 GB (IQ3_M)** | **Flagship Quad-Master:** RTL & EDA (85.0%), Math (85.0%) |
| **Vigyan-VL-4B** 👁️ | 4.10B | `Qwen3-VL-4B-Instruct` | Technical Vision | **Zero-Shot OCR** | **263 MB (LoRA)** | Schematics, PCB netlists, CAD drawings, Radiology |
| **Vigyan-7B** | 7.01B | `OLMo-2-1124-7B` | 100 Frontier STEM | **65.0%** | **3.31 GB (IQ3_M)** | Sovereign Architect, Quantum Chemistry |
| **Vigyan-R1-14B** 🧬 | 14.7B | `DeepSeek-R1-Qwen-14B` | Clinical & Biophysics | **R1 Distill + DPO** | **6.60 GB (IQ3_M)** | Air-gapped medical due diligence, drug discovery |
| **Vigyan-32B Titan** | 32.5B | `Olmo-3.1-32B-Instruct` | GSM8K Arithmetic | **84.2%** | *Cloud / AWS* | Frontier Symbolic Proofs & High-Complexity ASIC RTL |

> 🔍 **Open Verification**: Run `python reproduce_fleet_audit.py --model all` to verify all 100 test cases per model in < 2 seconds via the [Unified Benchmark Harness](https://github.com/shreyansh001boy-tech/vigyan-dpo-benchmark-harness).

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
