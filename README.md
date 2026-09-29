# Shreyansh Singh

Private language models, deployed inside your own network.
[ExperimentLab](https://experimentlab.in) · Varanasi, India

I fine-tune small language models for one domain, evaluate them against your own documents, and
install them behind your firewall — together with the website, API and automation built around them.
No prompt or document leaves your network, and there is no per-token bill.

---

## Domain-specialised adapters

Five Apache-2.0 LoRA adapters, with a Colab chat demo for each. Adapters are weights only — apply
them to the base model named in the row.

| Model | Domain | Base model | Adapter | Try |
| :--- | :--- | :--- | :--- | :--- |
| [Vidhi-AI-Instruct](https://huggingface.co/shreyansh12183/Vidhi-AI-Instruct) | Indian legal reasoning, statutory compliance, contract risk | Qwen2.5-7B-Instruct, r=8 | 10 MB | [Colab](https://colab.research.google.com/gist/shreyansh001boy-tech/6ba6a61ee99c4cf94044fe49dd509ba7/1_test_vidhi_ai_legal_colab.ipynb) |
| [olmo2-7b-silicon-rtl-eda](https://huggingface.co/shreyansh12183/olmo2-7b-silicon-rtl-eda) | Verilog HDL, RTL synthesis, timing closure | OLMo-2-1124-7B-Instruct, r=16 | 160 MB | [Colab](https://colab.research.google.com/gist/shreyansh001boy-tech/76305fa14b9252e71d409c99ce3fd206/2_test_silicon_rtl_eda_colab.ipynb) |
| [olmo2-7b-phd-pure-math](https://huggingface.co/shreyansh12183/olmo2-7b-phd-pure-math) | Proof synthesis, algebra, differential geometry | OLMo-2-1124-7B-Instruct, r=16 | 160 MB | [Colab](https://colab.research.google.com/gist/shreyansh001boy-tech/1d1120606c91b8fb734d26116ab0edae/4_test_phd_pure_math_colab.ipynb) |
| [olmo2-7b-biomed-chem](https://huggingface.co/shreyansh12183/olmo2-7b-biomed-chem) | Molecular informatics, organic synthesis, pathways | OLMo-2-1124-7B-Instruct, r=16 | 160 MB | [Colab](https://colab.research.google.com/gist/shreyansh001boy-tech/d194cb0b92c5478dc8c88e3fdff72dae/3_test_biomed_chem_colab.ipynb) |
| [olmo2-7b-astro-logic](https://huggingface.co/shreyansh12183/olmo2-7b-astro-logic) | Orbital dynamics, stellar mechanics, relativistic calculation | OLMo-2-1124-7B-Instruct, r=16 | 160 MB | [Colab](https://colab.research.google.com/gist/shreyansh001boy-tech/ea36f050bf1fdf992c8858348e10ffd8/5_test_astro_logic_colab.ipynb) |

Each Colab loads the base model plus adapter in 4-bit NF4 on a free T4 and opens a Gradio chat — it
is a hands-on demo, not a benchmark harness.

Corpora I built and published: [Hinglish-English STEM 500k](https://huggingface.co/datasets/shreyansh12183/shreyansh-hinglish-english-stem-500k) · [1B STEM pretrain set](https://huggingface.co/datasets/shreyansh12183/shreyansh-1B-SLM-pretrain-stem-english) · [Vidhi-AI 1k curated](https://huggingface.co/datasets/shreyansh12183/vidhi-ai-1k-curated)

---

## What I build

**Backend.** Product APIs, admin panels and data stores deployed as a single self-hosted binary on a
VPS you own: schema and row permissions, authentication, file storage, realtime updates and
server-side hooks. You get the repository, the server and the backup schedule — not a vendor lock-in.

**Web frontends.** TypeScript and React product UI, shipped on static hosting. Public example:
[craftora](https://github.com/shreyansh001boy-tech/craftora) — 28 production dependencies, IndexedDB
persistence, and no server code anywhere in the repository.

**Model integration.** The adapters above, or your model selection, behind your own endpoint:
retrieval over your documents, streamed responses, per-key rate limits, and an evaluation set that
stays with you.

**Workflow automation.** WhatsApp, Google Sheets, PDF and Tally or ERP pipelines. The model handles
the judgement step — classify, extract, draft — and deterministic code handles the transaction.
Every rule is readable, because a business cannot audit a prompt.

---

## How engagements work

1. **Readiness audit** — 2 to 3 weeks, fixed fee. We benchmark candidate models on a sample of your
   documents and give you a written go/no-go: accuracy ceiling, failure modes, hardware sizing, cost
   of ownership. If a small model will not do the job, the report says so.
2. **Pilot** — fine-tuning on your corpus, scored against the same held-out set, so improvement is
   measured rather than asserted.
3. **Deployment** — weights, adapters and vector store on hardware you own, on your network, with a
   documented rebuild path. Retainer covers refresh, re-evaluation and uptime.

Stack: Unsloth, Hugging Face TRL, PEFT/LoRA, NF4 quantization, vLLM, Docker, Qdrant.
Product side: TypeScript, React, Vite, IndexedDB, static and edge hosting, self-hosted single-binary
backends.

---

## Limits, stated plainly

- These are 7B-class models. They win on privacy, latency and cost — not on open-ended reasoning.
  An audit tells you which one you need before you buy hardware.
- Air-gapped deployment supports your DPDP or ISO 27001 obligations. It does not discharge them.
- You deal with the engineer who builds and deploys it. No account managers, no bench.

Every model, dataset and demo above links to something you can open right now. If I cannot link it,
I do not claim it. Client work is described under NDA where the client asks for it; references come
before you commit to anything.

---

**Email:** [shreyansh@experimentlab.in](mailto:shreyansh@experimentlab.in)
**Hugging Face:** [shreyansh12183](https://huggingface.co/shreyansh12183)
