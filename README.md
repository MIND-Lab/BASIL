# 🌿 BASIL - Broad AI Safety for Italian Language

A curated collection of publications, datasets, and models focused on broad AI safety in the Italian language.

AI safety research remains overwhelmingly English-centric, leaving Italian comparatively under-evaluated. This list collects the resources that specifically address Italian: safety benchmarks, guardrail models, and the peer-reviewed work behind them.

The repository aims to provide a focused starting point for researchers working on Italian-language AI safety and to make the growing body of Italian-specific work easier to discover and reuse.

## Scope

This repository focuses on broad, holistic AI safety in Italian, covering resources that address multiple dimensions of safety, such as harmful content, bias, toxicity, privacy, security, and robustness. Works narrowly focused on a single dimension are currently out of scope.

## Publications

### 2026

- **The Effects of Benevolent Fine-tuning on the Safety of the Italian Large Language Models** &mdash; Pulerà et al., CLIC-it 2026
- **"Capisci a me": The Hidden Risks of Regional Language Processing in LLMs** &mdash; Magazzù et al., CLIC-it 2026 [[Code](https://github.com/saiteki-kai/safety-italian-dialects)]
- **Mind the Language Gap: Assessing LLM Safety in Italian** &mdash; Marafatto & Navigli, LREC 2026 [[PDF](http://www.lrec-conf.org/proceedings/lrec2026/pdf/2026.lrec2026-1.365.pdf)] [[Poster](https://f003.backblazeb2.com/file/lrec-media/lrec2026/posters/1391.pdf)] [[Code](https://github.com/SapienzaNLP/SafeLLM-it)]
- **Guarding the Guardrails: A Taxonomy-Driven Approach to Jailbreak Detection** &mdash; Giarrusso et al., IASEAI 2026 [[PDF](https://arxiv.org/abs/2510.13893)]
- **Who Would You Vote For? Auditing Political Alignment in LLMs: An Italian Case-Study.** &mdash; Mungari, arXiv 2026 [[PDF](https://arxiv.org/abs/2608.11649)] [[Code](https://github.com/SimoneMungari/AuditingPoliticalAlignmentInLLMs)]

### 2025

- **BeaverTails-IT: Towards A Safety Benchmark for Evaluating Italian Large Language Models** &mdash; Magazzù et al., CLiC-it 2025 [[PDF](https://clic2025.unica.it/wp-content/uploads/2025/09/59_main_long.pdf)]
- **Uncovering Unsafety Traits in Italian Language Models** &mdash; Rizzi et al., CLiC-it 2025 [[PDF](https://aclanthology.org/2025.clicit-1.91.pdf)]

### 2024

- **Compromesso! Italian Many-Shot Jailbreaks Undermine the Safety of Large Language Models** &mdash; Pernisi et al., ACL 2024 [[PDF](https://arxiv.org/abs/2408.04522)] [[Code](https://github.com/fabiopernisi/ita-many-shots-jailbreaking)]

## Datasets

- [SafeLLM-it](https://github.com/SapienzaNLP/SafeLLM-it)
- [BeaverTails-IT](https://huggingface.co/datasets/MIND-Lab/BeaverTails-IT)
- [BeaverTails-IT-Evaluation](https://huggingface.co/datasets/MIND-Lab/BeaverTails-IT-Evaluation)
- [MMLU-Redux Dialects](https://huggingface.co/datasets/saiteki-kai/mmlu-redux-dialects)
- [XSTest Dialects](https://huggingface.co/datasets/saiteki-kai/xstest-dialects)

## Models

BeaverTails Safety Classifiers:

- [QA-DeBERTa-v3-large](https://huggingface.co/saiteki-kai/QA-DeBERTa-v3-large)
- [QA-Llama-3.1](https://huggingface.co/saiteki-kai/QA-Llama-3.1)
- [QA-Llama-Guard-3-8B](https://huggingface.co/saiteki-kai/QA-Llama-Guard-3-8B)

## Multilingual Resources (coming soon)

Multilingual resources for broad AI safety that include Italian will be added in the future. This section will cover datasets, models, and publications that address AI safety across multiple languages and would be relevant and useful for Italian language research.
