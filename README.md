# Shreyansh Singh

**Founder & AI Systems Architect @ [ExperimentLab.in](https://experimentlab.in)** · India  
*Building **Vigyan AI** — Sovereign Small Language Models (SLMs) and Sparse MoE architectures for formal mathematics, silicon semiconductor engineering, and edge robotics.*

[![Hugging Face Showcase](https://img.shields.io/badge/🤗%20Hugging%20Face-Sovereign%20Fleet%20Hub-orange?style=for-the-badge)](https://huggingface.co/shreyansh12183)
[![Verified Benchmark Harness](https://img.shields.io/badge/🏛️%20GitHub-Verified%20Benchmark%20Harness-black?style=for-the-badge)](https://github.com/shreyansh001boy-tech/vigyan-dpo-benchmark-harness)
[![Live Interactive Studio](https://img.shields.io/badge/⚛️%20Live%20Space-Vigyan--AI--Demo-blue?style=for-the-badge)](https://huggingface.co/spaces/shreyansh12183/Vigyan-AI-Demo)
[![Kaggle Research](https://img.shields.io/badge/Kaggle-shreyansh00singh-20BEFF?style=for-the-badge)](https://www.kaggle.com/shreyansh00singh)

---

## ⚡ Executive Overview

I design and train sovereign domain-specialized language models that achieve frontier-level accuracy on consumer edge hardware with zero synthetic contamination:

- **The 3B Parameter Breakthrough**: Using high-density **DARE-TIES Weight Fusion (0.75 density)** and targeted **DPO alignment**, our **Vigyan-3B-Quad-Master** achieved **69.0%** on 100 unseen graduate STEM problems—officially surpassing our earlier 7B model (**65.0%**) while occupying under **2 GB in RAM**.
- **Deterministic Peer Evaluation**: 100% auditable via SymPy Computer Algebra System (CAS) and IEEE 1364 Verilog AST synthesizability checks (zero LLM-judge bias).
- **Zero-Cost Sovereign Cloud Infrastructure**: Complete post-training recipes engineered on Kaggle Dual Tesla T4 GPUs and ephemeral AWS SageMaker Spot instances.
- **Air-Gapped Offline Deployment**: Packaged in Q4_K_M GGUF format for 100% offline desktop execution (30–45 tok/s on standard CPU).

---

## 🏛️ Sovereign Fleet Benchmark Matrix

| Fleet Tier | Parameters | Base Scaffold | Exam Suite | Score | Binary Size | Primary Specialization |
| :--- | :---: | :--- | :--- | :---: | :---: | :--- |
| **Vigyan-1.5B** | 1.54B | `DeepSeek-R1-Distill-1.5B` | 100 Frontier STEM | **43.0%** | **1.11 GB** | Ultra-light edge scout, IoT, PhD Math (75.0%) |
| **Vigyan-3B** 🚀 | 3.09B | `Qwen2.5-3B-Instruct` | 100 Frontier STEM | **69.0%** | **1.93 GB** | **Surpassed 7B!** RTL & EDA (85.0%), Pure Math (85.0%) |
| **Vigyan-7B** | 7.01B | `OLMo-2-1124-7B` | 100 Frontier STEM | **65.0%** | **4.20 GB** | Sovereign Architect, Quantum Chemistry (65.0%) |
| **Vigyan-32B Titan** | 32.5B | `OLMo-2-1124-32B` | GSM8K Arithmetic | **84.2%** | *Cloud / AWS* | Frontier Symbolic Proofs & High-Complexity RTL |

> 🔍 **Open Verification**: Run `python reproduce_fleet_audit.py --model all` to verify all 100 test cases per model in < 2 seconds via the [Unified Benchmark Harness](https://github.com/shreyansh001boy-tech/vigyan-dpo-benchmark-harness).

---

## 🤗 Curated Hugging Face Hub Portfolios

Explore curated model weights, interactive demos, and pre-training corpora on Hugging Face:

- 🏛️ [**Vigyan Sovereign STEM Fleet Collection**](https://hf.co/collections/shreyansh12183/vigyan-sovereign-stem-fleet) — Flagship 3B, 7B, 32B Titan models and specialized engineering adapters (Verilog RTL, PhD Pure Math, Biomed, Astro).
- 📚 [**Sovereign Pretraining Corpora Collection**](https://hf.co/collections/shreyansh12183/sovereign-stem-datasets-and-pretraining-corpora) — 1.5B+ curated tokens, including `shreyansh-1B-SLM-pretrain-stem-english` (420+ downloads) and `shreyansh-hinglish-english-stem-500k`.
- ⚛️ [**Vigyan-AI-Demo Space**](https://huggingface.co/spaces/shreyansh12183/Vigyan-AI-Demo) — Interactive browser showcase for 3D CAD (`/cad3d`), semiconductor physics (`/semiconductor`), and orbital mechanics.

---

## 🖥️ Flagship Product: Vigyan Pro Desktop (v2.8.0)

**Vigyan Pro** is an air-gapped, 100% offline AI science & 3D engineering studio built for R&D labs, aerospace engineers, and STEM institutions:

- **8 Native In-Chat Interactive Engines**: Live 3D CAD modeling, semiconductor band diagrams, orbital simulations, electronic schematics, and SymPy AST derivations.
- **Smart GPU + CPU Hybrid Inference**: Automatic dynamic layer splitting balancing integrated/discrete GPUs and CPU threads with zero cloud dependency.
- **Enterprise Air-Gapped Security**: Zero telemetry, zero external API keys, 100% private data sovereignty.

---

## 🛠️ 10+ Critical Industry Problems Solved by Vigyan AI & Vigyan Pro

| # | Domain & Real-World Bottleneck | Vigyan Technical Solution | Real-World Impact & Deployment |
| :---: | :--- | :--- | :--- |
| **01** | **Air-Gapped Semiconductor IP Protection**<br/>*Foundries & chip designers cannot send RTL code to cloud LLMs due to IP leaks and export controls.* | Sovereign **Vigyan-3B RTL Specialist** generates synthesizable IEEE 1364 Verilog, CDC flip-flop synchronizers, and Gray converters **100% offline**. | Zero network egress; ASIC/FPGA teams generate verified HDL locally with no IP risk. |
| **02** | **Static Timing Analysis (STA) Slack Errors**<br/>*Complex setup/hold timing violations require tedious manual slack calculations.* | Built-in STA mathematical solvers computing $T_{\text{comb\_max}}$ and hold margins with deterministic validation. | **85.0% pass rate** on silicon timing and clock-gating test suites. |
| **03** | **LLM Hallucinations in Formal Mathematics**<br/>*Standard LLMs routinely hallucinate calculus limits, contour integrals, and ODE solutions.* | **Neuro-Symbolic SymPy AST Engine** that symbolically verifies algebraic equivalence (`sp.simplify(pred - truth) == 0`) before answering. | **85.0% PhD Pure Math accuracy** with certified zero false positives. |
| **04** | **Disconnected CAD Workflows in Engineering**<br/>*Engineers waste hours switching between generative LLMs and external heavy CAD software.* | Native procedural **`/cad3d` engine** rendering parametric 3D mechanical assemblies and STL solids directly in conversational chat. | Instant mechanical prototyping inside Vigyan Pro Desktop without external licenses. |
| **05** | **Prohibitive Aerospace Trajectory Licensing**<br/>*Satellite orbit planning often requires expensive proprietary astrodynamics packages.* | Embedded **60 FPS orbital mechanics simulator** calculating Hohmann transfer $\Delta v$, vis-viva velocities, and orbital perturbations. | **65.0% accuracy** on aerospace frontier mechanics; instant trajectory derivations. |
| **06** | **Semiconductor Physics & Band Visualization**<br/>*Engineering students & fab technicians struggle to visualize carrier dynamics and Fermi levels.* | Interactive **`/semiconductor` engine** rendering live energy band bending, depletion widths, and MOSFET $I$-$V$ curves. | Deployed across academic labs for real-time solid-state electronics pedagogy. |
| **07** | **Offline Biochemical Reaction Screening**<br/>*Biotech labs lack fast, private screening tools for Arrhenius kinetics and molecular structures.* | Local biomedical reasoning engine evaluating reaction rate constants, partition functions, and IUPAC SMILES representations. | **60.0% accuracy** in chemistry; zero cloud latency for private drug target research. |
| **08** | **Bilingual Hinglish STEM Education Gap**<br/>*Tier-2/3 Indian university students learn in code-mixed Hinglish; western LLMs sound unnatural.* | Pretrained on **500k+ bilingual STEM instruction pairs** (`shreyansh-hinglish-english-stem-500k`) for natural contextual tutoring. | Fluent, culturally authentic technical explanations across physics, math, and coding. |
| **09** | **Indian Statutory Jurisprudence Gaps**<br/>*Generalist LLMs lack precision on the Indian Penal Code (IPC) and Bharatiya Nyaya Sanhita (BNS).* | Domain-adapted **`Vidhi-AI-Instruct`** fine-tuned on legal statutes, court rulings, and regulatory compliance frameworks. | Structured statutory retrieval and legal reasoning with 119+ community downloads. |
| **10** | **\$50,000+ Prohibitive Cloud GPU Costs**<br/>*Small labs and deep-tech startups are priced out of sovereign model development.* | Engineered **Zero-Cost Cloud Post-Training Recipe** utilizing Kaggle Dual Tesla T4s with prompt loss masking and DARE-TIES fusion. | Trained 36+ models and adapters for **\$0.00 cloud spend**. |
| **11** | **Low-Spec Hardware Freezes on 7B+ Models**<br/>*Standard 8GB–16GB laptops crash or throttle when running dense local foundation models.* | **Vigyan Pro Smart Governor** dynamically balancing layers between integrated/discrete GPUs and physical CPU threads. | Delivers **30–45 tok/s** smooth generation on standard consumer laptops. |
| **12** | **Catastrophic Model Merge Degradation**<br/>*DARE-TIES merges stripped 1D QK-Norm weights in 32B models, crashing math from 70% to 3.4%.* | **768 KB 15th Shard QK-Norm re-injection** recovering self-attention equilibrium on AWS SageMaker. | Fully restored **84.2% GSM8K** accuracy with zero compute waste. |

---

## 📜 Research Repositories & Whitepapers

- 🏛️ [**vigyan-dpo-benchmark-harness**](https://github.com/shreyansh001boy-tech/vigyan-dpo-benchmark-harness) — Rigorous 100-Problem Empirical Benchmark & Deterministic Chief Judge Evaluation Harness.
- 📖 [**vigyan-ai-journey-docs**](https://github.com/shreyansh001boy-tech/vigyan-ai-journey-docs) — 10-Chapter Technical Architecture on MoE upcycling, DARE-TIES fusion, and Neuro-Symbolic integration.
- 🔬 [**vigyan-32b-benchmark-reports**](https://github.com/shreyansh001boy-tech/vigyan-32b-benchmark-reports) — Forensic Math Recovery Audits & AWS SageMaker CloudWatch telemetry logs.

---

```
Founder: Shreyansh Singh
Email / Inquiries: Available via LinkedIn & ExperimentLab.in
Platform: https://experimentlab.in
```
