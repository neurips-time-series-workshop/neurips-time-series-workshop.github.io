---
layout: about
title: About
permalink: /
subtitle: First Workshop on Time Series in the Age of Large Models at the <a href="https://neurips.cc/">Thirty-eighth Annual Conference on Neural Information Processing Systems (NeurIPS)</a>, December 2024, Vancouver, Canada.

profile:
  align: right

news: false # includes a list of news items. TODO: set to true when needed
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page
---
This workshop will delve into aspects of time series prediction and analysis in the age of large models. The key topics of this workshop include, but are not limited to:

### Building Foundation Models for Time Series
Foundation models (FMs) have significantly changed the approach to building machine learning models in areas like natural language processing, where models are trained generically on vast amounts of diverse data ([1](https://arxiv.org/abs/2005.14165), [2](https://arxiv.org/abs/2108.07258)), and thus can be adapted to perform a range of tasks, even  “zero-shot”. Despite their impressive performance, most deep learning models for time series prediction still operate in the standard regime of training and prediction on a single dataset, on a single task. Foundation models for time series have been explored recently ([7](https://arxiv.org/abs/2310.08278), [8](https://arxiv.org/abs/2403.07815), [9](https://arxiv.org/abs/2402.02592), [10](https://arxiv.org/abs/2402.03885), [11](https://arxiv.org/abs/2310.10688)). We seek to understand the progress so far as well as the usefulness of these models compared to traditional time series models (in terms of factors such as performance, cost etc.), challenges in developing such models, outline a list of desiderata we would like out of these models, understanding the various design choices for such models, as well as the set of downstream time-series tasks to evaluate such models. We welcome contributions dealing with the challenges that come with the vast amounts of heterogeneous data used for training such models, and in understanding how these models scale ([21](https://arxiv.org/abs/2001.08361), [22](https://arxiv.org/abs/2405.13867), [23](https://arxiv.org/abs/2405.15124)) with the amount and diversity of data, with the different design choices. We further welcome contributions on improving the inference cost of such large models, with faster and better inference schemes. Further, it has been difficult to measure progress in FMs for time series due to the different evaluation benchmarks used in papers ([7](https://arxiv.org/abs/2310.08278), [8](https://arxiv.org/abs/2403.07815), [9](https://arxiv.org/abs/2402.02592), [10](https://arxiv.org/abs/2402.03885), [11](https://arxiv.org/abs/2310.10688)). We welcome contributions that explore robust evaluation datasets, metrics and benchmarks for such models focused on various tasks. We further welcome contributions on critiques and failure modes of such foundation models.

## Leveraging Pretrained Models of Other Modalities for Time Series
Pretrained large language models (LLMs) have shown extensive promise when adapted to other modalities (such as vision) with minimal adaptation or fine tuning ([27](https://arxiv.org/abs/2102.01293)). Recent studies have shown promise in the adaptation of pretrained LLMs to downstream specialized time series tasks ([3](https://arxiv.org/abs/2310.07820), [4](https://arxiv.org/abs/2302.11939), [12](https://arxiv.org/abs/2310.01728), [13](https://arxiv.org/abs/2310.04948), [17](https://arxiv.org/abs/2308.08241), [20](https://arxiv.org/abs/2405.15370)). We first seek to understand how the various design choices in leveraging these models, such as the prompting techniques used, adaptation methods used, fine-tuning methods used, etc can have an impact on the performance of the model on various tasks. Further, we also seek to understand in which scenarios such methods can excel, compared to other approaches, specifically such as when training time series FMs from scratch, in terms of the range of capabilities of the model, accuracy, training time, etc. Finally, while the adaptation of LLMs have been explored, the adaptation of pretrained models of other modalities (such as audio, video, images etc.) has been relatively underexplored ([24](https://arxiv.org/abs/2106.09296), [25](https://arxiv.org/abs/2303.12799)). We also welcome contributions that compare the adaptation of pretrained models of several modalities in various time series tasks, and discuss the success and failure modes of these models.

## Multimodal Time Series Models
Most time-series models in the literature are restricted to only handle numerical time-series data. However, numerical data often only paints a partial picture of the state of a system of interest. In real-world settings, multiple modalities are often available as input, and time series analysis or prediction tasks could potentially be improved by appropriately taking them into account. In this segment of the workshop, we seek to discuss the challenges involved in building such models, and welcome contributions including, but not limited to, attempting to build multimodal time series models ([15](https://arxiv.org/abs/2305.16556)), contributions comparing various approaches to fuse different modalities, datasets where time series modalities are paired with data from other modalities (such as text or images). In a similar vein of building multimodal time series models, we welcome contributions that build text-conditioned forecasting models ([16](https://arxiv.org/abs/2405.13522)), where textual cues such as news articles or event-related data can be utilized, in addition to the time series data available in a dataset, to condition a model to produce better predictions. We further invite contributions that explore the ability of such multimodal models to understand or infer semantic (such as causal) information between variables for time series analysis.

## Time Series Evaluation and Real-World Applications
As time-series models grow in capability and move toward real-world impact across business verticals, evaluating progress becomes critical to ensure it translates to deployment. Recent work has exposed shortcomings in current metrics used for evaluation in time series prediction models ([14](https://arxiv.org/abs/2203.10716)), specifically in probabilistic prediction models ([5](https://arxiv.org/abs/2201.08671), [6](https://arxiv.org/abs/2304.09836)). We seek contributions that deepen our understanding of the failure models of these metrics and contributions developing new metrics for probabilistic prediction evaluation. We further invite contributions that delve deeper into specific real-world applications of time series predictions (such as retail or transportation): in understanding objectives important for each of these specific domains, in an aim to build better evaluation setups for time series models. Finally, we invite contributions that showcase the potential of large time series models in domains such as financial forecasting ([19](https://arxiv.org/abs/2306.11025)), human mobility forecasting ([18](https://arxiv.org/abs/2209.05479)), weather forecasting ([26](https://arxiv.org/abs/2301.10343)) etc.

### Key Information

- Submission link: TBD
- Submission deadline: Sep 15, 2024 (11:59 PM AoE)
- Acceptance notification: Oct 14, 2024
- Camera ready deadline: Nov 25, 2024

Please see the [Call for Papers](/call-for-papers/) for more information.

### Contact

You can reach the organizers of the workshop at [neurips-time-series-workshop@googlegroups.com](mailto:neurips-time-series-workshop@googlegroups.com).
