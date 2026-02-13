# FAIRMetadataCuration
# FAIRMetadataCuration

**Enhancing FAIR Metadata Curation with AI‑Assisted Models and Structured Templates**

Scientific metadata often suffer from incompleteness, inconsistency, and formatting errors, which hinder effective discovery, reuse, and interoperability of associated data. The **FAIRMetadataCuration** project provides tools and notebooks for improving metadata quality by combining large language models with structured metadata templates to standardize, refine, and correct metadata at scale.

This repository implements workflows that leverage GPT‑based models and community‑driven metadata structures to bring metadata closer to **FAIR** principles (Findable, Accessible, Interoperable, Reusable).

---

## 🚀 Features

- 🧠 **AI‑Assisted Metadata Correction**  
  Correct and standardize metadata records using GPT models in batch workflows.

- 📊 **Evaluation of Metadata Quality**  
  Tools to compute recall, precision, and F1 scores against gold‑standard metadata.

- 📦 **Dataset Creation Utilities**  
  Scripts and notebooks for generating datasets from public sources like GEO and BioSample.

- 📘 Based on research demonstrating improved metadata recall with automated FAIRification methods, significantly enhancing downstream search performance.:contentReference[oaicite:0]{index=0}

---

## 📦 Repository Structure

| File / Folder | Description |
|---------------|-------------|
| `MetadataCorrection-gpt.ipynb` | Notebook to run GPT‑driven metadata correction workflows. |
| `metadata-refine.ipynb` | Notebook for computing evaluation metrics against gold standards. |
| `GEODatasetGenerator.ipynb` | Script to generate curated GEO datasets for experiments. |
| `Rules.ipynb` | Notebook used to derive gold‑standard rules for metadata refinement. |
| `README.md` | This documentation file. |
| `LICENSE` | MIT License for open reuse. |

---

## 🛠️ Getting Started

### 🔁 Prerequisites

- Python environment with necessary packages (e.g., Jupyter, OpenAI SDK)  
- OpenAI API key if using notebooks with GPT‑based correction  
- Access to raw metadata sources (BioSample, GEO, or others)

## Data
The data is available [here](https://doi.org/10.5281/zenodo.15617182).



## Citation
The paper is available [here](https://arxiv.org/abs/2504.05307). Please consider using the following BibTex for citation.
```
@misc{sundaram2025totalrecallenhancingfairness,
      title={Toward Total Recall: Enhancing FAIRness through AI-Driven Metadata Standardization}, 
      author={Sowmya S Sundaram and Rafael S. Gonçalves and Mark A Musen},
      year={2025},
      eprint={2504.05307},
      archivePrefix={arXiv},
      primaryClass={cs.IR},
      url={https://arxiv.org/abs/2504.05307}, 
}
```

## License
MIT License

Copyright (c) 2025 Mark Musen's Lab

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

