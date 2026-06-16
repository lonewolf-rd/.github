# LoneWolf RD

Independent research and development in **natural language processing**, with a focus on **low-resource languages**, **retrieval-augmented systems**, and **morphology-aware modeling**. Solo-author publications and open-source releases.

---

## Active Projects

| Repository | Description | Scope | Status |
|---|---|---|---|
| [**TurkishMorpheus**](https://github.com/lonewolf-rd/TurkishMorpheus) | **Morpheus** — neural morpheme-aware tokenizer **and word embedder** for Turkish. Lossless, low-BPC, morphology-aware, embedding-producing — the only such tokenizer usable in Turkish LLMs. | Research + Release | v4 complete, paper preprint forthcoming |
| [**CorpusCollector**](https://github.com/lonewolf-rd/CorpusCollector) | Reproducible Turkish corpus collection from Ekşisözlük + Dergipark + news sites. Used to build the Morpheus training corpus. | Tooling | Stable |
| [**CogOS**](https://github.com/lonewolf-rd/CogOS) | Cognitive Operating System. | Research | Early |

---

## Hugging Face

- 🤗 **Model**: [`Morpheus-TR-50K`](https://huggingface.co/lonewolflab/Morpheus-TR-50K) — Neural morpheme-aware tokenizer and word embedder for Turkish
- 🚀 **Live demo**: [`morpheus-tr-demo`](https://huggingface.co/spaces/lonewolflab/morpheus-tr-demo) — interactive segmentation + embedding explorer

---

## Publications

**2025**
- Şakar, T., & Emekci, H. *Maximizing RAG efficiency: A comparative analysis of RAG methods.* **Natural Language Processing**, 31(1), Cambridge University Press. [[link](https://www.cambridge.org/core/journals/natural-language-processing/article/maximizing-rag-efficiency-a-comparative-analysis-of-rag-methods/D7B259BCD35586E04358DF06006E0A85)]

**2026 (forthcoming)**
- Şakar, T. *Morpheus: A Morphology-Aware Neural Tokenizer and Word Embedder for Turkish.* arXiv preprint.

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

- 🐦 [Twitter / X](https://twitter.com/) <!-- TODO: add handle -->
- 💼 [LinkedIn](https://linkedin.com/in/) <!-- TODO: add profile -->
- 📧 Open an issue on any repository for technical discussion
