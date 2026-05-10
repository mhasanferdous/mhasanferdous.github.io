# News / Recent Updates

The two May 2024 blog posts currently anchor the "Recent News" section and read as stale. Replace that section with a hand-curated, dated feed.

---

## News block for the homepage

Edit `content/_index.md` and replace the blog-feed widget with the following markdown block.

```yaml
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
```

Verify the month estimates for Supraglacial Lake (ICMLA), Arctic Sea Ice (PerCom), the CDANs package release, and the ClassyGlass submission. Adjust any that are off.

---

## Retire the May 2024 blog posts

Set `draft: true` in the frontmatter of:

- `content/blog/data-visualization/index.md`
- `content/blog/project-management/index.md`

These will then be hidden from the rendered site without deletion.

---

## Forward-looking entries to add over the summer

Maintain one substantive entry every four to six weeks between now and application season (September through December 2026).

- June 2026. Reviewing assignments accepted.
- July 2026. TMLR decision on DCD.
- August 2026. Ph.D. defense and degree conferred.
- September 2026. KDD 2026 Dataset Track decision on ClassyGlass.
- September 2026. Applications open for Fall 2027.
