---
title: Software
date: 2026-05-10
type: landing

sections:
  - block: markdown
    content:
      title: ''
      text: |
        ## Open-Source Software

        Reproducible research and accessible tools are central commitments of my research program. The software listed below is publicly released, documented, and designed for use by other researchers, students, and practitioners.

        ---

        ### CDANs

        Constraint-based causal discovery with optimized conditioning sets, designed to handle autocorrelation, non-stationarity, and time-varying causal structure in multivariate time series. The package implements the methods described in our MLHC 2023 paper with a refined API and an emphasis on resource efficiency suitable for bedside monitoring and edge deployment.

        ```
        pip install cdans
        ```

        Repository: [github.com/hferdous/CDANs](https://github.com/hferdous/CDANs)

        Reference: Ferdous, Hasan, and Gani. *CDANs: Temporal Causal Discovery from Autocorrelated and Non-Stationary Time Series Data.* MLHC 2023. [Paper](/publications/cdans/)

        Status: Stable release on PyPI.

        ---

        ### TimeGraph

        A synthetic benchmark suite for time series causal discovery. The suite simulates realistic temporal complexities, including controlled causal structures, calibrated autocorrelation, non-stationarity, multiple noise distributions, and seasonal patterns. The intent is to allow honest comparison across methods and to expose the conditions under which each method succeeds or fails.

        Reference: Ferdous, Hossain, and Gani. *TimeGraph: Synthetic Benchmark Datasets for Robust Time-Series Causal Discovery.* KDD 2025. [Paper](/publications/timegraph/) · [DOI](https://doi.org/10.1145/3711896.3737439)

        Status: Published at KDD 2025; released as open-source software.

        ---

        ### ClassyGlass

        A benchmark dataset for activity and mobility analysis using smart eyewear. The dataset provides annotated multimodal sensor data and is intended to support the evaluation of causal and predictive methods in human activity recognition and health monitoring.

        Reference: Mahmud, Emmert, Ferdous, et al. *ClassyGlass: A Benchmark Dataset for Activity and Mobility Analysis using Smart Eyewear.* Submitted to KDD 2026 Dataset Track.

        Status: Under review.

        ---

        ## Citation

        If you use any of these tools in your research, please cite the corresponding paper. BibTeX entries are provided on each publication page.

        ---

        ## Contributions

        I welcome contributions, bug reports, and feature requests. Students or researchers interested in extending these tools (additional baselines, support for new data modalities, application to new domains) are encouraged to open an issue on the relevant GitHub repository or contact me by email.
    design:
      columns: '1'
---
