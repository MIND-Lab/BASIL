# 🌿 BASIL - Broad AI Safety for Italian Language

A curated collection of publications, datasets, and models focused on broad AI safety in the Italian language.

AI safety research remains overwhelmingly English-centric, leaving Italian comparatively under-evaluated. This list collects the resources that specifically address Italian: safety benchmarks, guardrail models, and the papers that support them.

The repository aims to provide a focused starting point for researchers working on Italian-language AI safety and to make the growing body of Italian-specific work easier to discover and reuse.

> [!NOTE]
> This collection is incomplete and currently under construction. The listings below are not exhaustive: entries are still being gathered and reviewed, and sections, links, and metadata may change as the repository evolves.

## Scope

This repository focuses on broad, holistic AI safety in Italian, covering resources that address multiple dimensions of safety, such as harmful content, bias, toxicity, privacy, security, and robustness. Works narrowly focused on a single dimension are currently out of scope.

## Publications

### 2026

- **The Effects of Benevolent Fine-tuning on the Safety of the Italian Large Language Models** &mdash; Pulerà et al., CLIC-it 2026 [[PDF](https://clic2026.unipa.it/wp-content/uploads/2026/09/82_main_long.pdf)]
- **“Capisci a me”: The Hidden Risks of Regional Language Processing in LLMs** &mdash; Magazzù et al., CLIC-it 2026 [[PDF](https://clic2026.unipa.it/wp-content/uploads/2026/09/63_main_long.pdf)] [[Code](https://github.com/saiteki-kai/safety-italian-dialects)]
- **Mind the Language Gap: Assessing LLM Safety in Italian** &mdash; Marafatto & Navigli, LREC 2026 [[PDF](http://www.lrec-conf.org/proceedings/lrec2026/pdf/2026.lrec2026-1.365.pdf)] [[Poster](https://f003.backblazeb2.com/file/lrec-media/lrec2026/posters/1391.pdf)] [[Code](https://github.com/SapienzaNLP/SafeLLM-it)]
- **AI Safety Lost in Translation: Evaluating the Effectiveness of English-Italian Cross-Lingual LLM Safety Alignment** &mdash; Wu & Brandao, LREC 2026 [[PDF](https://aclanthology.org/2026.lrec-1.296.pdf)]
- **Guarding the Guardrails: A Taxonomy-Driven Approach to Jailbreak Detection** &mdash; Giarrusso et al., IASEAI 2026 [[PDF](https://arxiv.org/abs/2510.13893)]
- **"Learning from Mistakes: Can LLM Self-recover after Misalignment?": Examining the LLM's ability to self-recover after misalignment** &mdash; Sorokoletova et. al., AAAI26 WS37 [[PDF](https://arxiv.org/pdf/2606.00003)]
- **Who Would You Vote For? Auditing Political Alignment in LLMs: An Italian Case-Study** &mdash; Mungari, arXiv 2026 [[PDF](https://arxiv.org/abs/2608.11649)] [[Code](https://github.com/SimoneMungari/AuditingPoliticalAlignmentInLLMs)]

### 2025

- **BeaverTails-IT: Towards A Safety Benchmark for Evaluating Italian Large Language Models** &mdash; Magazzù et al., CLiC-it 2025 [[PDF](https://clic2025.unica.it/wp-content/uploads/2025/09/59_main_long.pdf)]
- **Uncovering Unsafety Traits in Italian Language Models** &mdash; Rizzi et al., CLiC-it 2025 [[PDF](https://aclanthology.org/2025.clicit-1.91.pdf)]

### 2024

- **Compromesso! Italian Many-Shot Jailbreaks Undermine the Safety of Large Language Models** &mdash; Pernisi et al., ACL 2024 [[PDF](https://arxiv.org/abs/2408.04522)] [[Code](https://github.com/fabiopernisi/ita-many-shots-jailbreaking)]
- **Multi-property steering of large language models with dynamic activation composition** &mdash; Scalena et al., BlackboxNLP 2024 [[PDF](https://aclanthology.org/2024.blackboxnlp-1.34.pdf)] [[Code](https://github.com/DanielSc4/Dynamic-Activation-Composition)]

## Datasets

| Dataset | Year | Description | Languages | Links | License |
| --- | --- | --- | --- | --- | --- |
| **SafeLLM-it** | 2026 | Culturally grounded Italian safety benchmark of 1,762 manually categorized Italian Wikipedia pages and 5,286 generated prompts probing refusal behavior, moderation consistency, and unsafe content generation. | Italian | [[GitHub](https://github.com/SapienzaNLP/SafeLLM-it)] [[Paper](http://www.lrec-conf.org/proceedings/lrec2026/pdf/2026.lrec2026-1.365.pdf)] | CC BY-NC-SA 4.0 |
| **MMLU-Redux-IT** | 2026 | MMLU-Redux translated into Italian and local languages to study how dialectal input affects model understanding and safety. | Italian, Venetian, Lombard, Friulian, Ligurian, Sicilian (+ English source) | [[Hugging Face](https://huggingface.co/datasets/saiteki-kai/MMLU-Redux-IT)] [[Paper](https://clic2026.unipa.it/wp-content/uploads/2026/09/63_main_long.pdf)] | CC BY 4.0 |
| **XSTest-IT** | 2026 | XSTest prompts translated into Italian and local languages, preserving the safe/unsafe contrast labels for dialectal safety evaluation. | Italian, Venetian, Lombard, Friulian, Ligurian, Sicilian (+ English source) | [[Hugging Face](https://huggingface.co/datasets/saiteki-kai/XSTest-IT)] [[Paper](https://clic2026.unipa.it/wp-content/uploads/2026/09/63_main_long.pdf)] | CC BY 4.0 |
| **BeaverTails-IT** | 2025 | Italian machine-translated version of BeaverTails, with parallel translations from five state-of-the-art MT models; 330k question-answer pairs. | Italian (from English) | [[Hugging Face](https://huggingface.co/datasets/MIND-Lab/BeaverTails-IT)] [[Paper](https://clic2025.unica.it/wp-content/uploads/2025/09/59_main_long.pdf)] | CC BY-NC 4.0 |
| **BeaverTails-IT-Evaluation** | 2025 | Italian machine-translated version of BeaverTails-Evaluation: 700 prompts spanning 14 safety categories, used with fine-tuned classifiers and human judgment to assess seven Italian LLMs. | Italian (from English) | [[Hugging Face](https://huggingface.co/datasets/MIND-Lab/BeaverTails-IT-Evaluation)] [[Paper](https://aclanthology.org/2025.clicit-1.91.pdf)] | CC BY-NC 4.0 |

## Models

BeaverTails Safety Classifiers:

- [QA-DeBERTa-v3-large](https://huggingface.co/saiteki-kai/QA-DeBERTa-v3-large)
- [QA-Llama-3.1](https://huggingface.co/saiteki-kai/QA-Llama-3.1)
- [QA-Llama-Guard-3-8B](https://huggingface.co/saiteki-kai/QA-Llama-Guard-3-8B)

## Multilingual Resources (coming soon)

Multilingual resources for broad AI safety that include Italian will be added in the future. This section will cover datasets, models, and publications that address AI safety across multiple languages and would be relevant and useful for Italian language research.

Works that merely include Italian as one of many languages will not be listed here, unless they provide specific insights or evaluations for Italian.
