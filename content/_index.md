---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        My work sits at the intersection of **causal discovery**, **time series
        analysis**, and **machine learning**. I focus on developing methods that
        can recover meaningful causal structure from *autocorrelated* and
        *non-stationary* multivariate time series—exactly the kind of data that
        appears in real-world systems.

        Methodologically, I work on:
        - **Temporal causal discovery** from complex, high-dimensional time series  
        - **Decomposition-based approaches** that separate trend, seasonal, and
          residual components (e.g., DCD)  
        - **Attention-based and deep learning models** (CDANs, eCDANs) for
          scalable structure learning  
        - **Benchmarking frameworks** (TimeGraph) to stress-test causal discovery
          algorithms under realistic temporal conditions

        Application domains include:
        - **Healthcare**, where robust causal structure can support early
          warning, treatment policy evaluation, and patient monitoring  
        - **Climate and environmental systems**, such as Arctic sea ice prediction
          and climate teleconnections

        I am particularly interested in questions like:
        - How can we make causal discovery robust to temporal dependence
          and non-stationarity?
        - How should we evaluate causal graphs when the data are messy,
          irregular, and partially observed?
        - How can causal structure be integrated into downstream decision-making
          and forecasting systems?

        I am actively looking for collaborations at the interface of **causal
        inference**, **time series**, and **real-world decision systems**.
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: markdown
    id: news
    content:
      title: 'News'
      text: |
        - **Summer 2026.** Ph.D. defense at UMBC. On the academic job market for Fall 2026 and Spring 2027 starts.
        - **February 2026.** DCD preprint released ([arXiv:2602.01433](https://arxiv.org/abs/2602.01433)) and submitted to *Transactions on Machine Learning Research*.
        - **2026.** CDANs released as an open-source Python package: `pip install cdans` ([GitHub](https://github.com/hferdous/CDANs)).
        - **December 2025.** *Causal Time Series Modeling of Supraglacial Lake Evolution in Greenland under Distribution Shift* accepted at IEEE ICMLA 2025 ([arXiv](https://arxiv.org/abs/2510.15265)).
        - **October 2025.** *ClassyGlass: A Benchmark Dataset for Activity and Mobility Analysis using Smart Eyewear* submitted to the KDD 2026 Dataset Track.
        - **August 2025.** Awarded the COEIT Summer Student Project Award ($5,000) from UMBC for student-led research.
        - **August 2025.** *TimeGraph: Synthetic Benchmark Datasets for Robust Time-Series Causal Discovery* published at KDD 2025 ([paper](/publications/timegraph/), [DOI](https://doi.org/10.1145/3711896.3737439)).
        - **May 2025.** Honorable Mention for Research Poster, COEIT Research Day, UMBC.
        - **March 2025.** *Correlation to Causation: A Causal Deep Learning Framework for Arctic Sea Ice Prediction* presented at IEEE PerCom Workshops 2025 ([DOI](https://doi.org/10.1109/PerComWorkshops65533.2025.00042)).
        - **2023.** *CDANs: Temporal Causal Discovery from Autocorrelated and Non-Stationary Time Series Data* published at MLHC 2023 (New York). MLHC Travel Award ([paper](/publications/cdans/)).
        - **2023.** *eCDANs: Efficient Temporal Causal Discovery from Autocorrelated and Non-Stationary Data* (Student Abstract) at AAAI 2023 ([paper](/publications/ecdans/)).
    design:
      columns: '1'
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: 'bg-primary-300 dark:bg-primary-700'
        css_style: ''
---
