# Large Language Models for Climate-Related Text Analysis: a review

**Fernando Nakamoto**

A short review paper analyzing the **ClimateIE** framework — a pipeline for
structured information extraction from climate science text — within the
broader context of large language models (LLMs) applied to sustainability and
climate-related tasks.

## Abstract

This mini-paper analyzes the ClimateIE framework, which proposes a dataset and
methodology for structured information extraction in climate science, including
tasks such as entity recognition, relation extraction, and taxonomy alignment.
It begins with a broader contextualization of LLMs in sustainability, followed
by a review of the theoretical foundations underlying these models. It then
discusses the core problems that ClimateIE aims to address, describes its
methodology, and presents its main results. Finally, it provides a critical
analysis of the framework's limitations and discusses possible directions for
improvement.

## Contents

- [`climate-llm-review.pdf`](climate-llm-review.pdf) — full paper (5 pages).

## Topics covered

- LLM pipelines for structured information extraction (tokenization,
  embeddings, transformer self-attention, decoder-only modeling).
- The ClimateIE pipeline: NER, Relation Extraction, and Entity Linking against
  the GCMD+ taxonomy, with hybrid human/AI-assisted annotation.
- Critical analysis: dataset size and bias, semantic ambiguity in
  sustainability terminology, hallucination and factual consistency, and error
  propagation across sequential pipeline stages.

## Key references

- Pan et al. *ClimateIE: A Dataset for Climate Science Information Extraction.*
  ACL Workshop on Climate NLP, 2025.
- Jo-Pan. *ClimateIE: Information Extraction for Climate Science.*
  https://github.com/Jo-Pan/ClimateIE, 2025.
- Jurafsky, D., & Martin, J. H. *Speech and Language Processing* (3rd ed. draft),
  Stanford University.

---

© 2026 Fernando Nakamoto. Shared for reference and portfolio purposes.
