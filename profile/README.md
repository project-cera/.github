<p align="center">
  <img src="https://raw.githubusercontent.com/project-cera/cera/main/assets/cera-logo.png" alt="CERA Logo" width="300">
</p>

<p align="center">
  <b>Context-Engineered Reviews Architecture</b><br>
  A training-free framework for generating realistic, controllable synthetic review datasets for Aspect-Based Sentiment Analysis (ABSA).
</p>

---

CERA is a modular three-phase pipeline (Composition, Generation, Evaluation) that produces high-quality synthetic ABSA data using only context engineering and multi-agent verification — no GPU infrastructure, fine-tuning, or pre-existing embeddings required.

Developed as part of an MSc thesis at the University of Windsor.

## Repositories

| Repository | Description |
|------------|-------------|
| [cera](https://github.com/project-cera/cera) | Core framework — CLI, web GUI, and the full generation pipeline |
| [cera-LADy](https://github.com/project-cera/cera-LADy) | Latent Aspect Detection evaluation framework for benchmarking generated datasets |
| [cera-human-eval](https://github.com/project-cera/cera-human-eval) | Human evaluation interface for assessing synthetic review quality |
| [cera-vLLM](https://github.com/project-cera/cera-vLLM) | Self-hosted local LLM server for GPU-accelerated generation |

## Citation

```bibtex
@mastersthesis{thang2026cera,
  title     = {CERA: Context-Engineered Reviews Architecture for
               Synthetic ABSA Dataset Generation},
  author    = {Thang, Kap},
  school    = {University of Windsor},
  year      = {2026},
  type      = {Master's Thesis}
}
```
