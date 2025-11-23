---
title: "TimeGraph: Synthetic Benchmark Datasets for Robust Time-Series Causal Discovery"
authors:
- admin
- Emam Hossain
- Md Osman Gani
date: "2025-08-01T00:00:00Z"
doi: ""

# Publication type: 1 = Conference paper
publication_types: ["1"]

publication: "In *Proceedings of the 31st ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD 2025)*"
publication_short: "In *KDD '25*"

abstract: "Robust causal discovery in time series datasets depends on reliable benchmark datasets with known ground-truth causal relationships. However, such datasets remain scarce, and existing synthetic alternatives often overlook critical temporal properties inherent in real-world data, including nonstationarity driven by trends and seasonality, irregular sampling intervals, and the presence of unobserved confounders. To address these challenges, we introduceTimeGraph, a comprehensive suite of synthetic time-series benchmark datasets that systematically incorporates both linear and nonlinear dependencies while modeling key temporal characteristics such as trends, seasonal effects, and heterogeneous noise patterns. Each dataset is accompanied by a fully specified causal graph featuring varying densities and diverse noise distributions and is provided in two versions: one including unobserved confounders and one without, thereby offering extensive coverage of real-world complexity while preserving methodological neutrality. We further demonstrate the utility of TimeGraph through systematic evaluations of state-of-the-art causal discovery algorithms including PCMCI+, LPCMCI, and FGES across a diverse array of configurations and metrics. Our experiments reveal significant variations in algorithmic performance under realistic temporal conditions, underscoring the need for robust synthetic benchmarks in the fair and transparent assessment of causal discovery methods. The complete TimeGraph suite, including dataset generation scripts, evaluation metrics, and recommended experimental protocols, is freely available to facilitate reproducible research and foster community-driven advancements in time-series causal discovery."

tags:
- Causal Discovery
- Benchmarking
- Time Series

featured: true

image:
  caption: ''
  focal_point: ""
  preview_only: false

---
