# Shreyansh Singh

**AI Systems Engineer & Founder** · Varanasi, India · [experimentlab.in](https://experimentlab.in)  
*Building sovereign domain-specialized Small Language Models (SLMs) and edge-native reasoning systems.*

[![Hugging Face](https://img.shields.io/badge/🤗%20Hugging%20Face-shreyansh12183-orange.svg?style=flat-square)](https://huggingface.co/shreyansh12183)
[![Kaggle](https://img.shields.io/badge/Kaggle-shreyansh00singh-blue.svg?style=flat-square)](https://kaggle.com/shreyansh00singh)
[![GitHub](https://img.shields.io/badge/GitHub-shreyansh001boy--tech-black.svg?style=flat-square)](https://github.com/shreyansh001boy-tech)
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg?style=flat-square)](https://creativecommons.org/licenses/by-nc/4.0/)

> *"Building efficient, domain-expert AI models that run 100% locally or on low-cost hardware with zero API lock-in."*

---

### 🌟 Highlights & Open Assets

- 🚀 **12 Live Colab Demos**: Full interactive Gradio web UIs running on free T4 GPUs.
- 📦 **29 Open-Weight Models**: Specialized models across Law, Math, STEM, and Hardware on Hugging Face.
- 📑 **5 Research Papers**: Sovereign training recipes, MoE upcycling, DUS, and test-time reasoning on Kaggle.
- 📊 **3 Curated Datasets**: Over 1 billion tokens of clean STEM & Legal training data.

---

## 🎮 Live Interactive Demos (Run Free on Google Colab)

Every demo launches an interactive **Gradio chat interface** connected to the real model running in 4-bit precision on a free Google Colab T4 GPU. No API keys or accounts required.

### 🥇 Generation 3: Unified Masterpieces & Production Models
*State-of-the-art models combining multi-task expertise, test-time reasoning, and efficient routing.*

| Model | Focus / Domain | Footprint | Interactive Demo |
| :--- | :--- | :---: | :---: |
| [**Vidhi AI 1.5B Masterpiece**](https://huggingface.co/shreyansh12183/vidhi-ai-1.5b-sovereign-masterpiece) | Indian Law, BNS/BNSS 2023, IPC cross-mapping | 1.06 GB | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/shreyansh001boy-tech/97736d594721ab8e37912cd381fdf968/colab_demo_vidhi_1_5b.ipynb) |
| [**Vigyan 7B Quad-Master**](https://huggingface.co/shreyansh12183/vigyan-olmo2-7b-quad-master) | SLERP Merge of 4 Specialists (Math, RTL, Bio, Astro) | 4.26 GB | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/shreyansh001boy-tech/94f86027e672aa60dbda383eca6cf122/colab_demo_vigyan_7b_quad_master.ipynb) |
| [**Vigyan OLMoE 1B-7B DPO**](https://huggingface.co/shreyansh12183/vigyan-olmoe-1b-7b-dpo-masterpiece) | Sparse MoE (1.3B active params/token), STEM reasoning | 4.02 GB | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/shreyansh001boy-tech/1222eec06995b9b046bb76096495a653/colab_demo_vigyan_olmoe_1b_7b.ipynb) |

---

### 🥈 Generation 2: Reasoning & Architecture Experiments
*Explorations in depth up-scaling, test-time reasoning RL (GRPO), and compact mixture-of-experts.*

| Model | Architecture & Technique | Footprint | Interactive Demo |
| :--- | :--- | :---: | :---: |
| [**Vigyan 2B GRPO Reasoner**](https://huggingface.co/shreyansh12183/vigyan-2b-reasoning-grpo) | Reinforcement learning with `<think>` reasoning traces | 1.45 GB | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/shreyansh001boy-tech/ff2d815ac5810c7d3729e9b8ee6f9894/colab_demo_vigyan_2b_grpo.ipynb) |
| [**Shreyansh STEM 2B (DUS)**](https://huggingface.co/shreyansh12183/Shreyansh-STEM-AI-2B-v3) | 22-Layer Depth Up-Scaled foundation model | 1.45 GB | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/shreyansh001boy-tech/1f517b4c146d36fd2aee72c0d4dacc85/colab_demo_shreyansh_stem_2b_dus.ipynb) |
| [**Vigyan 7B STEM DPO**](https://huggingface.co/shreyansh12183/Vigyan-7B-STEM-DPO-v1) | Direct Preference Optimization for rigorous STEM math | 4.26 GB | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/shreyansh001boy-tech/df09e101004eafae5c86cd2d7fb80a8c/colab_demo_vigyan_7b_stem_dpo.ipynb) |
| [**Vigyan 1.5B 4x-MoE**](https://huggingface.co/shreyansh12183/Vigyan-1.5B-4x-MoE) | Compact 4-Expert MoE running under 1GB RAM | 0.98 GB | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/shreyansh001boy-tech/18daf8e5416d3e25ca0065b9052e1688/colab_demo_vigyan_1_5b_moe.ipynb) |

---

### 🥉 Generation 1: Domain Specialist Foundations
*Specialized domain models fine-tuned on dedicated expert corpora.*

| Model | Domain | Highlight | Interactive Demo |
| :--- | :--- | :---: | :---: |
| [**Vidhi AI 7B Instruct**](https://huggingface.co/shreyansh12183/Vidhi-AI-Instruct) | Indian Law & Statutory Guidance | 88.2% BNS Accuracy | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/shreyansh001boy-tech/46a6c9e902e161ff947be68fc156e709/colab_demo_vidhi_7b.ipynb) |
| [**OLMo2 7B Pure Math**](https://huggingface.co/shreyansh12183/olmo2-7b-phd-pure-math) | Advanced Math & Proof Synthesis | 76.8% MATH L5 Benchmark | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/shreyansh001boy-tech/f13664784d899f9a72509d6003b3b791/colab_demo_olmo2_pure_math.ipynb) |
| [**OLMo2 7B Silicon RTL**](https://huggingface.co/shreyansh12183/olmo2-7b-silicon-rtl-eda) | Verilog HDL & Semiconductor Design | Synthesizable RTL Generation | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/shreyansh001boy-tech/d7e16e7f902372db11ba5b9490f28adf/colab_demo_olmo2_silicon_rtl.ipynb) |
| [**OLMo2 7B Biomed Chem**](https://huggingface.co/shreyansh12183/olmo2-7b-biomed-chem) | Molecular Chemistry & Drug Action | Biochemical Reaction Pathways | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/shreyansh001boy-tech/12fa1afcfe242451f0f2d31a1ccccd58/colab_demo_olmo2_biomed_chem.ipynb) |
| [**OLMo2 7B Astro Logic**](https://huggingface.co/shreyansh12183/olmo2-7b-astro-logic) | Celestial Mechanics & Relativistic Physics | Formal Symbolic Derivations | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/shreyansh001boy-tech/6a524659f571f0cd0ed5d218868a4863/colab_demo_olmo2_astro_logic.ipynb) |

---

## 📑 Research Papers Series (2026)

Open-access technical papers documenting empirical methodologies and architectures:

- **Volume 01: Sparse MoE Upcycling & Router Stabilization**  
  *Techniques for upcycling dense SLMs into sparse mixture-of-experts with calibrated routing.*  
  [📖 Read on Kaggle](https://www.kaggle.com/datasets/shreyansh00singh/vigyan-moe-upcycling-research-paper)

- **Volume 02: Depth Up-Scaling (DUS) & Seam Healing**  
  *Extending transformer depth via manifold splicing and continued pretraining.*  
  [📖 Read on Kaggle](https://www.kaggle.com/datasets/shreyansh00singh/vigyan-dus-seam-healing-research-paper)

- **Volume 03: Tool-Augmented Direct Preference Optimization**  
  *Grounding language models with SymPy and symbolic solvers to eliminate mathematical hallucination.*  
  [📖 Read on Kaggle](https://www.kaggle.com/datasets/shreyansh00singh/vigyan-tool-dpo-symbolic-grounding-paper)

- **Volume 04: Test-Time Compute Elicitation via GRPO**  
  *Lightweight reinforcement learning pipelines for producing verified reasoning traces in edge models.*  
  [📖 Read on Kaggle](https://www.kaggle.com/datasets/shreyansh00singh/vigyan-grpo-reasoning-rl-paper)

- **Volume 05: Neuro-Symbolic Hybrid Evaluation Harness**  
  *Dual-engine evaluation framework combining C++ KùzuDB GraphRAG and SymPy AST verifiers.*  
  [📖 Read on Kaggle](https://www.kaggle.com/datasets/shreyansh00singh/vigyan-neuro-symbolic-eval-paper)

---

## 📊 Open Datasets on Hugging Face

- [**shreyansh-1B-SLM-pretrain-stem-english**](https://huggingface.co/datasets/shreyansh12183/shreyansh-1B-SLM-pretrain-stem-english): 1B-token curated corpus covering mathematics, physics, computing, and engineering.
- [**shreyansh-hinglish-english-stem-500k**](https://huggingface.co/datasets/shreyansh12183/shreyansh-hinglish-english-stem-500k): 500k high-quality STEM instruction pairs in English and Hinglish.
- [**vidhi-ai-1k-curated**](https://huggingface.co/datasets/shreyansh12183/vidhi-ai-1k-curated): Targeted dataset focusing on new Indian criminal laws (BNS, BNSS, BSA 2023).

---

## 💻 Systems & Engineering Projects

- **[Craftora Studio](https://craftora.vercel.app)** — Production in-browser vector graphics editor and design suite built with React 19, TypeScript, and Fabric.js 6. Fully client-side, zero latency.
- **[ExperimentLab.in](https://experimentlab.in)** — Educational initiative making deep tech, AI research, and engineering principles accessible.
- **BITS Pilani Automated Exam Evaluation System** — Production automated scoring and OCR pipeline for high-throughput academic exam assessments.

---

## 📬 Contact & Licensing

- **Email**: [shreyansh@experimentlab.in](mailto:shreyansh@experimentlab.in)
- **Hugging Face**: [@shreyansh12183](https://huggingface.co/shreyansh12183)
- **GitHub**: [@shreyansh001boy-tech](https://github.com/shreyansh001boy-tech)
- **Kaggle**: [@shreyansh00singh](https://www.kaggle.com/shreyansh00singh)

*All models, datasets, and code are distributed under the [CC BY-NC 4.0 License](https://creativecommons.org/licenses/by-nc/4.0/). For commercial licensing or partnerships, please reach out via email.*
