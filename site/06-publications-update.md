# Publications Page (academic tone)

Total: 6 publications and preprints visible on Google Scholar. 2 manuscripts currently under review (DCD at TMLR, ClassyGlass at KDD 2026 Dataset Track).

Items to fix on the existing page: eCDANs is missing entirely, Supraglacial Lake is mislabeled as "arXiv" (it appeared at ICMLA 2025), the CDANs publication entry does not link to the Python package, and DCD should be presented as an arXiv preprint under review at TMLR rather than as a working paper.

---

## Published papers. Update each existing entry.

### TimeGraph

`content/publications/timegraph/index.md`

```yaml
title: 'TimeGraph: Synthetic Benchmark Datasets for Robust Time-Series Causal Discovery'
authors:
  - admin
  - emam-hossain
  - md-osman-gani
date: '2025-08-01'
publishDate: '2025-08-01'
publication_types: ['paper-conference']
publication: 'Proceedings of the 31st ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD ''25)'
publication_short: 'KDD ''25'
doi: '10.1145/3711896.3737439'
featured: true
tags:
  - Causal Discovery
  - Benchmark
  - Time Series
abstract: 'TimeGraph is a synthetic benchmark suite for time series causal discovery. The suite simulates controlled causal structures, calibrated autocorrelation, non-stationarity, multiple noise distributions, and seasonal patterns. It is designed to support honest comparison across methods and to expose the conditions under which each method succeeds or fails.'
```

### CDANs

`content/publications/cdans/index.md`. Add the code link in frontmatter.

```yaml
title: 'CDANs: Temporal Causal Discovery from Autocorrelated and Non-Stationary Time Series Data'
authors:
  - admin
  - uzma-hasan
  - md-osman-gani
date: '2023-08-01'
publishDate: '2023-08-01'
publication_types: ['paper-conference']
publication: 'Proceedings of the 8th Machine Learning for Healthcare Conference (MLHC ''23)'
publication_short: 'MLHC ''23'
publication_pages: '186–207'
url_code: 'https://github.com/hferdous/CDANs'
featured: true
tags:
  - Causal Discovery
  - Time Series
  - Healthcare
  - Software
abstract: 'CDANs is a constraint-based framework for temporal causal discovery that optimizes the conditioning sets used in constraint-based search. The method explicitly identifies lagged parents to reduce the search space and improve detection power in autocorrelated and non-stationary time series. CDANs also detects changing modules, components whose causal structure varies over time as a result of distribution shifts, by considering both contemporaneous and lagged parents. The algorithm is publicly available as a Python package (`pip install cdans`).'
```

### Supraglacial Lake

`content/publications/supraglacial-lake/index.md`. Currently labeled "arXiv." Update to ICMLA 2025.

```yaml
title: 'Causal Time Series Modeling of Supraglacial Lake Evolution in Greenland under Distribution Shift'
authors:
  - emam-hossain
  - admin
  - devon-dunmire
  - aneesh-subramanian
  - md-osman-gani
date: '2025-12-01'
publishDate: '2025-12-01'
publication_types: ['paper-conference']
publication: 'IEEE International Conference on Machine Learning and Applications (ICMLA ''25)'
publication_short: 'ICMLA ''25'
url_preprint: 'https://arxiv.org/abs/2510.15265'
tags:
  - Causal Discovery
  - Climate
  - Deep Learning
```

### Arctic Sea Ice

`content/publications/arctic-sea-ice/index.md`. Verify the venue fields.

```yaml
publication: 'IEEE International Conference on Pervasive Computing and Communications Workshops (PerCom Workshops ''25)'
publication_short: 'PerCom Workshops ''25'
publication_pages: '62–67'
doi: '10.1109/PerComWorkshops65533.2025.00042'
```

### DCD (preprint, under review)

`content/publications/dcd/index.md`. Present as an arXiv preprint under review at TMLR.

```yaml
title: 'DCD: Decomposition-based Causal Discovery from Autocorrelated and Non-Stationary Temporal Data'
authors:
  - admin
  - md-osman-gani
date: '2026-02-01'
publishDate: '2026-02-01'
publication_types: ['manuscript']
publication: 'arXiv preprint arXiv:2602.01433 (under review at Transactions on Machine Learning Research)'
publication_short: 'arXiv 2602.01433 · Under review, TMLR'
url_preprint: 'https://arxiv.org/abs/2602.01433'
tags:
  - Causal Discovery
  - Time Series
  - Climate
abstract: 'DCD is a decomposition-based framework for causal discovery in multi-seasonal and non-stationary time series. The framework separates each series into trend, seasonal, and residual components and applies different inference procedures to each: stationarity testing for trends, kernel-based dependence measures for seasonal components, and constraint-based discovery for residuals. Component-level findings are integrated into a unified multi-scale causal graph. Empirical results on synthetic benchmarks and real climate data show consistent improvement over state-of-the-art baselines under strong non-stationarity and autocorrelation.'
```

Setting `publication_types: ['manuscript']` rather than `'paper-conference'` ensures Hugo Blox groups this entry as a preprint rather than as a conference publication.

---

## Create new publication entry

### eCDANs

`content/publications/ecdans/index.md`. This entry is currently missing from the site.

```yaml
---
title: 'eCDANs: Efficient Temporal Causal Discovery from Autocorrelated and Non-Stationary Data (Student Abstract)'
authors:
  - admin
  - uzma-hasan
  - md-osman-gani
date: '2023-02-07'
publishDate: '2023-02-07'
publication_types: ['paper-conference']
publication: 'Proceedings of the AAAI Conference on Artificial Intelligence (AAAI ''23)'
publication_short: 'AAAI ''23'
publication_volume: '37(13)'
publication_pages: '16208'
tags:
  - Causal Discovery
  - Time Series
abstract: 'eCDANs refines the search strategy for lagged adjacencies in the CDANs constraint-based framework, preserving accuracy while reducing computational overhead. The result is suitable for larger datasets and for deployment in resource-constrained environments such as bedside monitoring and edge devices.'
---
```

---

## Manuscripts Under Review section

Add this section to `content/publications/_index.md` or as a separate section block. Only two items are listed; G-DCD has not yet been submitted and is not included.

```markdown
## Manuscripts Under Review

- Ferdous, M. H., and Gani, M. O. *DCD: Decomposition-based Causal Discovery from Autocorrelated and Non-Stationary Temporal Data.* Submitted to *Transactions on Machine Learning Research (TMLR)*, 2026. [arXiv:2602.01433](https://arxiv.org/abs/2602.01433)

- Mahmud, N., Emmert, N., Ferdous, M. H., et al. *ClassyGlass: A Benchmark Dataset for Activity and Mobility Analysis using Smart Eyewear.* Submitted to *ACM SIGKDD 2026 Dataset Track*.
```

---

## Google Scholar link

A single line near the top of the Publications page directs visitors to the live citation record.

```markdown
> Citation counts are maintained on [Google Scholar](https://scholar.google.com/citations?user=fOBzV-QAAAAJ&hl=en).
```

---

## Author pages

Each co-author needs a page at `content/authors/{slug}/` for the author links on publication pages to resolve correctly.

- `admin`, `md-osman-gani`, `emam-hossain`, `uzma-hasan`, `aneesh-subramanian`, `devon-dunmire`, `jianwu-wang`
- `nazia-mahmud`, `nicholas-emmert` (for ClassyGlass once accepted)

---

## Honors and Awards section

```markdown
## Honors and Awards

- COEIT Summer Student Project Award ($5,000), UMBC, Summer 2025. Competitive award supporting student-led research and innovation.
- Honorable Mention for Research Poster, COEIT Research Day 2025, UMBC.
- Travel Award, Machine Learning for Healthcare (MLHC) Conference, New York, 2023.
```

---

## Professional Service section

```markdown
## Professional Service

Reviewer and sub-reviewer for AAAI, IEEE PerCom Workshops, and ACM SIGKDD-affiliated venues.

Presenter at COEIT Research Day (UMBC, 2024 and 2025) and the Information Systems Student Research Symposium (UMBC, 2022).
```
