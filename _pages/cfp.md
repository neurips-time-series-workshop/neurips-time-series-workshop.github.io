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

**Update Nov 26**: The list of accepted papers is available [here](/accepted-papers/) and the PDFs are available at the linked OpenReview pages.

<del>**Update Oct 10**: Decisions have been released. **Titles and abstracts of all accepted papers are available [here](https://openreview.net/group?id=NeurIPS.cc/2024/Workshop/TSALM#tab-accept).** PDFs will be made public at the camera-ready stage.</del>

<del>**Update Oct 9:** Due to a large number of submissions, we will announce the decisions on Oct 10 instead of on Oct 9.</del>  

- Submission link: **[OpenReview](https://openreview.net/group?id=NeurIPS.cc/2024/Workshop/TSALM)**
- Submission deadline: Sep 15, 2024 (11:59 pm AoE)
- Acceptance notification: <del>Oct 09, 2024</del> Oct 10, 2024 (anytime before 11:59 AoE)
- Camera ready deadline: <del>Nov 15, 2024</del> Nov 25, 2024 (7 PM EST) 

## Submission Instructions

Submissions should take the form of a short paper of up to **4 pages**. Additional pages containing references and appendices are allowed but the reviewers are _not obliged_ to refer to the appendices when reviewing the paper. Submissions should be made on **[OpenReview](https://openreview.net/group?id=NeurIPS.cc/2024/Workshop/TSALM)** in a single `.pdf` file using **[this LaTeX style template](../assets/latex/timeseries-workshop-latex-template.zip)**. The review process in _double-blind_, so please ensure that your submission is properly anonymized. Papers that exceed the page limit or have not been properly anonymized will be desk-rejected without review. Please note that there is no rebuttal phase and the final decisions will be made based solely on the submission and the reviews. Rejected and withdrawn submissions will not be made public.

All accepted submissions will be accompanied by a poster presentation. A number of selected submissions will be invited for lightning and oral talks. 

**Dual submission policy**: This workshop is **non-archival**; even though all accepted papers will be available on OpenReview and this website, there are no formally-published proceedings. If a paper is currently under review at another venue, it can still be submitted to this workshop. If a paper has previously appeared in a journal, workshop, or conference, it should be reasonably extended in order to be accepted at this workshop. Parallel submission of papers under review at NeurIPS 2024 is allowed.

## Scope and Topics

We invite submissions related to the theme of time series in the age of large models. Key topics include, but are not limited to:

- **Building Time Series Foundation Models**: The heterogeneity of time series data and tasks presents unique challenges in developing time series foundation models. We welcome contributions exploring various design choices and improving our understanding of how these models scale with the amount and diversity of data.
- **Analysis of Pretrained Time Series Models**: Pretrained time series models are often criticized for their black-box nature, especially compared to interpretable statistical models. We encourage submissions that analyze pretrained time series models to enhance our understanding of their learning processes.
- **Critiques on Time Series Foundation Models**: Contributions highlighting the limitations and failure modes of time series foundation models through theoretical analysis or systematic empirical evaluations are welcome.
- **Faster and Better Inference Schemes for Autoregressive Time Series Models**: Single-step autoregressive time series foundation models are generally slower than multi-step models, such as those based on patching. We invite submissions comparing these techniques and developing methods to improve the inference speed and quality of autoregressive time series models.
- **Leveraging Pretrained Models of Other Modalities for Time Series**: Recent studies show promise in adapting pretrained LLMs to specialized time series tasks. We seek to understand how design choices in leveraging these models—such as prompting techniques, adaptation methods, and fine-tuning—impact performance. We also seek to identify scenarios where these methods excel compared to training time series foundation models from scratch, in terms of model capabilities, accuracy, and training and inference times.
- **Multimodal Time Series Models**: Most time series models handle only numerical data, often providing a partial picture of the system of interest. In real-world settings, multiple modalities are available, and incorporating exogenous information, such as text, can enhance performance. We invite submissions exploring time series models that integrate information from other modalities.
- **Large-Scale Time Series Datasets and Benchmarks**: The quality and quantity of publicly available time series data lag behind other modalities, such as text and vision. We welcome contributions of large-scale time series data (both general and domain-specific) and benchmarks comparing various time series foundation models. We also invite methods for better synthetic time series generation and augmentation to address data challenges.
- **Time Series Evaluation**: We seek contributions on the analysis, comparison, and development of metrics for time series tasks, including metrics for probabilistic forecasting, multivariate forecasting, and use-case motivated metrics.
- **Real-World Applications of Large Time Series Models**: We invite contributions showcasing the potential of large time series models in real-world domains, such as energy, healthcare, retail, human mobility, and finance.

## Call for reviewers (closed)

We are also looking for reviewers for the workshop. If you would like to nominate someone (or yourself), please fill this [google form](https://docs.google.com/forms/d/e/1FAIpQLSdOa2gEKTmpSvqa9tbQGEQbm7uxmGlht-04qA3u0agoWIaO5w/viewform).

## Reviewer Guidelines

Reviewers should follow these guidelines when evaluating a paper. These guidelines are based on the [reviewer guidelines for TMLR](https://jmlr.org/tmlr/acceptance-criteria.html). 

The acceptance decision for a submission is based on the answers to the following questions:

**Are the claims made in the submission supported by accurate, convincing and clear evidence?**   

This is the most important criterion. This implies assessing the technical soundness as well as the clarity of the narrative and arguments presented. Papers with large gaps between claims and evidence must be rejected. 

- Papers presenting a new method/model with a reasonable proof of concept should be seen as satisfying this criterion. 
- Papers solely presenting empirical analysis should present rigorous comparisons before making general claims. 

**Would at least some individuals in this workshop’s audience be interested in knowing the findings of this paper?**    

This is arguably the most subjective criterion, and therefore needs to be treated carefully. Generally, a reviewer that is unsure as to whether a submission satisfies this criterion should assume that it does. Crucially, it should not be used as a reason to reject work that isn't considered “significant” or “impactful” because it isn't achieving a new state-of-the-art on some benchmark. Nor should it form the basis for rejecting work on a method considered not “novel enough”, as novelty of the studied method is not a necessary criteria for acceptance. We explicitly avoid these terms (“significant”, “impactful”, “novel”), and focus instead on the notion of “interest”. If the authors make it clear that there is something to be learned by some researchers in their area from their work, then the criterion of interest is considered satisfied.

Papers should be accepted if they meet these criteria, even if the contribution or significance of the work is modest. 

Papers that should not be accepted include 
- papers that make bold statements unsupported by empirical or rigorous evidence,
- papers that aren’t clearly written,
- papers that incorrectly claim novelty over existing published work, and
- papers that merely re-implement an idea that has already been reproduced before.

### Review Format

A review should have the following content.

**Summary of contributions**: Brief description, in the reviewer's words, of the contributions and new knowledge presented by the submission.      
**Strengths and weaknesses**: List of the strong aspects of the submission as well as weaker elements (if any) that you think require attention from the authors.     
**Suggestions**: Any suggestions to improve the paper for future versions.

## Contact

If you have questions about this workshop or are not sure if your paper's topic is suitable for submission, please feel free to contact the organizers at [neurips-time-series-workshop@googlegroups.com](mailto:neurips-time-series-workshop@googlegroups.com).
