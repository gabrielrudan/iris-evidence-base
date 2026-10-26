# ÍRIS Evidence Base

This repository contains the evidence base used in the development of the ÍRIS taxonomy for the evaluation of Large Language Model (LLM) outputs.

## Repository structure

The repository contains two main versions of the dataset, corresponding to different stages of the methodological process:

- `data/iris_raw_article_data.xlsx`: initial extraction dataset. Each row corresponds to one primary study and contains the information collected directly from the article, including domain, task, quality aspects, evaluation objectives, automation level, risk, evaluation methods/metrics, and the authors' justification for their use.

- `data/iris_standardized_evidence_base.xlsx`: standardized evidence base used in the subsequent analyses. In this version, the information extracted from each article was decomposed into individual evidence lines whenever the study reported different relationships between tasks, quality aspects, evaluation strategies, or automation levels. Terminology was also standardized to enable comparison across studies.

## Scope

The evidence base comprises 47 primary studies published between 2023 and April 2026.

The first version of the review included 44 studies and supported the short survey *A Short Survey on Hybrid and Traditional Evaluation Methods for LLM Outputs*. The evidence base was subsequently updated with three additional studies identified up to April 2026, resulting in the final set of 47 studies used in the development of the ÍRIS taxonomy.

## Extracted information

The initial extraction considered the following information:

- article title;
- publication year;
- evaluated LLM or set of models;
- domain;
- task;
- quality aspect;
- evaluation objective;
- automation level;
- risk;
- evaluation methods or metrics;
- justification for the selected metrics or methods.

## Standardized evidence base

During the standardization stage, studies containing multiple evaluation configurations were decomposed into separate evidence lines.

For example, if the same article evaluated textual similarity using an automatic metric and factuality using human experts, these relationships were represented as distinct evidence lines.

This structure allows the analysis of associations between scenario characteristics and evaluation strategies without losing the traceability to the original studies.

## Research context

The evidence base supports the development of ÍRIS, a multidimensional taxonomy and decision-support approach designed to assist researchers in identifying evaluation strategies for LLM outputs according to the characteristics of different evaluation scenarios.
