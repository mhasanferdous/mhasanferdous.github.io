---
title: Research
date: 2026-05-10
type: landing

sections:
  - block: markdown
    content:
      title: ''
      text: |
        ## Research Vision

        Contemporary machine learning systems are effective at identifying statistical regularities but offer limited capacity for causal explanation. The distinction matters in domains where decisions depend on understanding the mechanisms behind observed patterns rather than the patterns themselves. My research develops methods for causal discovery in complex time series data and the open-source software through which those methods become accessible to other researchers, students, and practitioners.

        The work is positioned at the intersection of statistics, machine learning, and information systems. My undergraduate training in statistics at the University of Dhaka provides the foundation for formal inference; my graduate training at UMBC in information systems provides the orientation toward deployable, application-grounded research; and my dissertation work in the UMBC Causal AI Lab under Dr. Md Osman Gani provides the algorithmic depth.

        ---

        ## Completed Contributions

        ### Constraint-based causal discovery: CDANs and eCDANs

        Constraint-based causal discovery algorithms condition on the full history of a process, an approach that is computationally expensive and statistically inefficient when data are autocorrelated. The CDANs framework (MLHC 2023) optimizes the conditioning sets used in constraint-based search by explicitly identifying lagged parents, reducing the search space and improving detection power. CDANs also introduces a mechanism for detecting changing modules: components whose causal structure varies over time as a result of distribution shifts. The framework considers both contemporaneous and lagged parents when assessing structural changes.

        eCDANs (AAAI 2023) refines the lagged-adjacency search strategy, preserving the accuracy of CDANs while reducing computational overhead. The resulting method is suitable for larger datasets and for deployment in resource-constrained environments such as bedside monitoring and edge devices.

        CDANs is publicly available as a Python package: `pip install cdans` ([GitHub](https://github.com/hferdous/CDANs)).

        ### Decomposition-based discovery for multi-seasonal data: DCD

        Real-world time series in climate, finance, and operational domains typically contain overlapping seasonal patterns and long-term trends. These structures confound standard causal discovery algorithms. The DCD framework ([arXiv:2602.01433](https://arxiv.org/abs/2602.01433), under review at TMLR) separates each time series into trend, seasonal, and residual components and applies different inference procedures to each: stationarity testing for trends, kernel-based dependence measures for seasonal components, and constraint-based discovery for residuals. The component-level findings are integrated into a unified multi-scale causal graph. Empirical results on synthetic benchmarks and real climate data show consistent improvement over state-of-the-art baselines under strong non-stationarity and autocorrelation.

        ### Open-source benchmarks: TimeGraph and ClassyGlass

        Progress in causal discovery has been constrained by inconsistent evaluation. Researchers test methods on different datasets, often under simplified conditions, which makes cross-method comparison difficult and obscures the conditions under which a given approach succeeds or fails.

        TimeGraph (KDD 2025) is a synthetic benchmark suite that simulates realistic temporal complexities. The suite generates datasets with controlled causal structures, calibrated autocorrelation, non-stationarity, multiple noise distributions, and seasonal patterns. ClassyGlass (under review, KDD 2026 Dataset Track) extends the benchmarking program to multimodal wearable-sensor data for activity and mobility analysis. Both resources are released as open-source software with the aim of lowering the barrier to rigorous and reproducible evaluation, particularly for undergraduate and early-career researchers.

        ### Climate, healthcare, and interdisciplinary applications

        I have applied my methods through several interdisciplinary collaborations. With Dr. Aneesh Subramanian (University of Colorado Boulder), I co-developed a causal deep-learning framework for Arctic sea ice prediction (IEEE PerCom Workshops 2025) and a causal time series model of Greenland supraglacial lake evolution (IEEE ICMLA 2025). Both projects integrate causal discovery with deep learning to produce forecasts that maintain accuracy under distribution shift. In healthcare, I have applied causal discovery to physiological time series and to clinical datasets including the Pima Indian Diabetes database, with the goal of identifying physiological parameters that constitute actionable intervention targets rather than correlational risk markers.

        ---

        ## Five-Year Research Agenda

        My research program will be organized around four interconnected thrusts that advance foundational methods while maintaining connections to real-world applications.

        ### Thrust 1. Foundational causal AI for streaming, non-stationary systems

        I will extend the CDANs and DCD frameworks to streaming and concept-drifting data, which is the regime in which most production information systems operate. Projects include online causal discovery with bounded memory, causal change-point detection, methods for handling missingness arising from sensor failure rather than missing-at-random assumptions, and the integration of causal reasoning with anomaly detection. These methods support trustworthy inference across cyber-physical systems, sensor networks, and operational monitoring.

        ### Thrust 2. Integration of causal inference with deep learning

        Deep learning captures complex patterns but offers limited transparency. Causal models provide explicit structure but face scalability challenges in high-dimensional settings. This thrust develops hybrid neuro-causal frameworks that embed causal discovery into deep representation learning. The goal is to retain predictive performance while gaining the ability to reason about cause and effect under distribution shift. Specific directions include neuro-causal models for transfer learning and the development of interpretable explanations grounded in causal structure. This is a productive area for undergraduate involvement through course projects, summer research, and senior capstones.

        ### Thrust 3. Open-source ecosystem for reproducible causal AI

        My research program has already produced three distinct open-source contributions: the CDANs Python package, the TimeGraph benchmark suite, and the ClassyGlass multimodal benchmark (under review). I will expand this ecosystem with semi-synthetic benchmarks drawn from finance, climate, healthcare, and security data; libraries that implement state-of-the-art causal discovery baselines; and community engagement through workshop organization at KDD, AAAI, and adjacent venues focused on trustworthy machine learning. Software infrastructure provides visibility for a department disproportionate to its cost, and it is sustainable work for dedicated undergraduate research assistants.

        ### Thrust 4. Interdisciplinary collaboration and societal impact

        Causal AI methods become valuable when they touch substantive problems. I plan collaborative projects in three application areas where my methods transfer naturally.

        Healthcare and digital health. Causal modeling of physiological time series, trustworthy clinical decision support, and the identification of actionable intervention targets in chronic disease management.

        Climate and environmental science. Extension of causal time series methods to ice-sheet dynamics, sea ice forecasting, and climate teleconnections, building on existing collaborations.

        Adversarial robustness and security analytics. Causal feature selection for machine learning models with greater resistance to input perturbation, causal discovery for intrusion detection on autocorrelated network traffic, and causal explanations for security incidents in settings where analysts need root-cause reasoning beyond anomaly scores.

        ---

        ## Funding Strategy

        | Source | Program | Focus | Years |
        |---|---|---|---|
        | NSF | CRII; later CAREER | Foundational causal AI methods; open-source infrastructure | 1–3, then 3–5 |
        | NSF | SaTC; CICI | Causal and adversarially robust ML for security analytics | 2–5 |
        | NIH | R03 / R21 / R-series | Trustworthy clinical decision support; causal modeling of physiological time series | 2–5 |
        | DoE / NOAA | Data Science programs | Causal discovery for climate and environmental modeling | 2–5 |
        | Industry | Sponsored research | Finance, enterprise IT, regional and national technology partners | Ongoing |

        ---

        ## Student-Centered Research Program

        My research program is designed for substantive student involvement. Open-source benchmarks and software packages produce work in which well-supervised undergraduates contribute meaningfully, and the resulting artifacts (published code, datasets, reproducibility audits) carry weight on graduate school applications and industry resumes. My objective targets are at least one peer-reviewed publication per year with a student co-author by year three, and at least one student per year placed into industry internships or graduate programs.

        ---

        ## Collaboration

        I welcome collaboration at the intersection of causal inference, time series modeling, and applied decision systems. If your research involves healthcare AI, climate analytics, security analytics, or any domain in which prediction-only models break under distribution shift, please reach out.
    design:
      columns: '1'
---
