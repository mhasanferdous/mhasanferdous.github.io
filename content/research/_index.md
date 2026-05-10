---
title: Research
date: 2026-05-10
type: landing

sections:
  - block: markdown
    content:
      title: ''
      text: |
        ## Overview

        My research focuses on **causal AI**, **temporal causal discovery**, and **robust time series analysis**. I am particularly interested in recovering stable causal structure from multivariate time series exhibiting autocorrelation, non-stationarity, multi-seasonality, and irregular sampling.

        The work bridges the gap between statistical inference and machine learning, with the goal of producing interpretable causal models that remain reliable under the distribution shifts common in real-world systems.

        ---

        ## Core Research Themes

        ### 1. Robust Temporal Causal Discovery
        Recovering causal graphs from observational time series is challenging when the data are autocorrelated and non-stationary. My work (e.g., **CDANs**, **eCDANs**) introduces constraint-based discovery algorithms that optimize conditioning sets by explicitly identifying lagged parents. This reduces the search space and improves detection power in high-dimensional settings.

        ### 2. Decomposition-based Causal Inference
        Complex systems (climate, healthcare) produce data with multiple temporal scales. My research on **DCD (Decomposition-based Causal Discovery)** separates series into trend, seasonal, and residual components. By applying scale-specific inference procedures, we can recover a unified multi-scale causal graph that is more robust than methods applied to raw data.

        ### 3. Trustworthy Benchmarking for Causal AI
        How do we know when a causal discovery method is reliable? I developed **TimeGraph**, a synthetic benchmark suite that simulates controlled causal structures with calibrated temporal complexities. TimeGraph allows researchers to stress-test algorithms under realistic conditions and to identify the failure modes of current state-of-the-art methods.

        ---

        ## Application Domains

        ### Climate and Environmental Science
        In collaboration with researchers at the University of Colorado Boulder, I apply causal methods to understand Arctic sea ice prediction and Greenland supraglacial lake evolution. These systems exhibit strong non-stationarity and distribution shift, making them ideal testbeds for robust causal inference.

        ### Healthcare and Mobility
        Working with the UMBC Causal AI Lab, I develop methods for clinical time series and sensor-based mobility data. Our work on **ClassyGlass** (smart eyewear dataset) supports the evaluation of causal and predictive models in human activity recognition and health monitoring.

        ---

        ## Future Directions

        I am currently extending these methods to:
        - **Causal discovery with latent variables** in temporal data.
        - **Intervention-aware forecasting**, using discovered causal structure to improve predictions under distribution shift.
        - **Human-in-the-loop causal discovery**, incorporating domain knowledge into automated search procedures.

        ---

        ## UMBC Causal AI Lab
        I am a member of the Causal AI Lab at the University of Maryland, Baltimore County, directed by [Dr. Md Osman Gani](https://gani.umbc.edu/).
    design:
      columns: '1'
---
