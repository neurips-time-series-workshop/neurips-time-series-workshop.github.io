---
layout: page
permalink: /call-for-papers/
title: Call for Papers
description:
nav: true
nav_order: 1
---

We welcome researchers working in the field of time series analysis to submit their latest original research work to the NeurIPS 2024 workshop on **Time Series in the Age of Large Models**.

## Key Information

- Submission link: [TBD](https://openreview.net)
- Submission deadline: Sep 15, 2024 (11:59 pm AoE)
- Acceptance notification: Oct 14, 2024
- Camera ready deadline: Nov 25, 2024

## Submission Instructions

Submissions should take the form of a short paper of up to **4 pages**. Additional pages containing references and appendices are allowed but the reviewers are _not obliged_ to refer to the appendices when reviewing the paper. Submissions should be made on **[Open Review]()** in a single `.pdf` file using **[this LaTeX style template](../assets/latex/timeseries-workshop-latex-template.zip)**. The review process in _double-blind_, so please ensure that your submission is properly anonymized. Papers that exceed the page limit or have not been properly anonymized will be rejected without review.

All accepted submissions will be accompanied by a poster presentation. A number of selected submissions will be invited for lightning and oral talks. 

**Dual submission policy**: This workshop is **non-archival**; even though all accepted papers will be available on OpenReview and this website, there are no formally-published proceedings. If a paper is currently under review at another venue, it can still be submitted to this workshop. If a paper has previously appeared in a journal, workshop, or conference (including papers accepted to NeurIPS 2024 conference), it should be reasonably extended in order to be accepted at this workshop.

## Scope and Topics

We invite submissions related to time series foundation models (TSFMs). Key topics include, but are not limited to:

- **Building Foundation Models for Time Series Data**: The heterogeneity of time series data and tasks presents unique challenges in developing TSFMs. We welcome contributions exploring various design choices and improving our understanding of how these models scale with the amount and diversity of data.
- **Analyzing Existing Pretrained Time Series Models**: TSFMs are often criticized for their black-box nature, especially compared to interpretable statistical models. We encourage submissions that analyze pretrained time series models to enhance our understanding of their learning processes.
- **Critiques of Foundation Models for Time Series**: Contributions highlighting the limitations of TSFMs through theoretical analysis or systematic empirical evaluations are welcome.
- **Faster and Better Inference Schemes for Autoregressive TSFMs**: Single-step autoregressive TSFMs are generally slower than multi-step models, such as those based on patching. We invite submissions comparing these techniques and developing methods to improve the inference speed and quality of autoregressive models.
- **Leveraging Pretrained Models of Other Modalities for Time Series**: Recent studies show promise in adapting pretrained LLMs to specialized time series tasks. We seek to understand how design choices in leveraging these models—such as prompting techniques, adaptation methods, and fine-tuning—impact performance. We also seek to identify scenarios where these methods excel compared to training TSFMs from scratch, in terms of model capabilities, accuracy, and training and inference times.
- **Multimodal Time Series Models**: Most time series models handle only numerical data, often providing a partial picture of the system of interest. In real-world settings, multiple modalities are available, and incorporating exogenous information, such as text, can enhance performance. We invite submissions exploring time series models that integrate information from other modalities.
- **Large-Scale Time Series Datasets and Benchmarks**: The quality and quantity of publicly available time series data lag behind other modalities, such as text and vision. We welcome contributions of large-scale time series data and benchmarks, both general and domain-specific. We also invite methods for better synthetic time series generation and augmentation to address data challenges.
- **Time Series Evaluation**: We seek contributions on the analysis, comparison, and development of metrics for time series tasks, including metrics for probabilistic forecasting, multivariate forecasting, and use-case motivated metrics.
- **Real-World Applications of TSFMs**: We invite contributions showcasing the potential of TSFMs in real-world domains, such as energy, healthcare, retail, human mobility, and finance.

## Contact

If you have questions about this workshop or are not sure if your paper's topic is suitable for submission, please feel free to contact the organizers at [neurips-time-series-workshop@googlegroups.com](mailto:neurips-time-series-workshop@googlegroups.com).
