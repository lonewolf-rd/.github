# LoneWolf RD

Independent research and development in **natural language processing**, with a focus on **low-resource languages**, **retrieval-augmented systems**, and **morphology-aware modeling**. Solo-author publications and open-source releases.

---

## Active Projects

| Repository | Description | Scope | Status |
|---|---|---|---|
| [**TurkishTokenizer-Alpha-v1**](https://github.com/lonewolf-rd/TurkishTokenizer-Alpha-v1) | **Morpheus** — neural morpheme-aware tokenizer for Turkish. Best-in-class BPC + structured root-family embeddings. | Research + Release | v3 complete, paper preprint forthcoming |
| [**CorpusCollector**](https://github.com/lonewolf-rd/CorpusCollector) | Reproducible Turkish corpus collection from Ekşisözlük + Dergipark + news sites. Used to build the Morpheus training corpus. | Tooling | Stable |
| [**CogOS**](https://github.com/lonewolf-rd/CogOS) | Cognitive Operating System. | Research | Early |

---

## Hugging Face

- **Model**: [`morpheus-tr-50k`](https://huggingface.co/lonewolf-rd/morpheus-tr-50k) — Neural morpheme-aware tokenizer for Turkish
- **Live demo**: [`morpheus-tr-demo`](https://huggingface.co/spaces/lonewolf-rd/morpheus-tr-demo) — interactive segmentation

---

## Publications

**2025**
- Şakar, T., & Emekci, H. *Maximizing RAG efficiency: A comparative analysis of RAG methods.* **Natural Language Processing**, 31(1), Cambridge University Press. [[link](https://www.cambridge.org/core/journals/natural-language-processing/article/maximizing-rag-efficiency-a-comparative-analysis-of-rag-methods/D7B259BCD35586E04358DF06006E0A85)]

**2026 (forthcoming)**
- Şakar, T. *Morpheus: A Morphology-Aware Tokenizer for Turkish.* arXiv preprint.

---

## Research Areas

- **Low-resource and morphologically-rich language modeling** (esp. Turkish and other agglutinative languages)
- **Tokenization design** for downstream language model efficiency
- **Retrieval-augmented generation** systems and their comparative efficiency
- **Open, reproducible NLP pipelines** — full data collection → training → evaluation chains

---

## Philosophy

Research as a solo practitioner: complete pipelines released as working code, not slideware. Every model release ships with the corpus collector, training scripts, and evaluation suite that produced it — so anyone can reproduce or adapt.

---

## Connect

- [LinkedIn](www.linkedin.com/in/tolga-şakar) 
- Open an issue on any repository for technical discussion
