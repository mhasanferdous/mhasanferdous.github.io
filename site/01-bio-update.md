# Bio / Hero update (academic tone)

**File to edit:** `content/authors/admin/_index.md`

---

## Frontmatter changes

```yaml
role: Ph.D. Candidate in Information Systems (defending Summer 2026)
# After defense: role: Ph.D., Information Systems
```

```yaml
interests:
  - Causal Discovery and Inference
  - Trustworthy and Robust Machine Learning
  - Time Series Analysis
  - Open-Source Benchmarks for AI Reproducibility
  - Adversarial and Robust ML for Cybersecurity
```

```yaml
education:
  - area: PhD in Information Systems
    institution: University of Maryland, Baltimore County (UMBC)
    date_start: 2021-01
    date_end: 2026-08
    thesis_title: 'Bridging Theory and Practice. Robust Causal Discovery from Autocorrelated, Non-Stationary, and Irregular Time Series Data'
    advisor: 'Dr. Md Osman Gani'
  - area: MS in Information Systems
    institution: University of Maryland, Baltimore County (UMBC)
    date_start: 2021-01
    date_end: 2023-12
  - area: BSc in Statistics
    institution: University of Dhaka, Bangladesh
    date_end: 2010
```

```yaml
profiles:
  - icon: at-symbol
    url: 'mailto:h.ferdous@umbc.edu'
    label: E-mail Me
  - icon: brands/google-scholar
    url: https://scholar.google.com/citations?user=fOBzV-QAAAAJ&hl=en
  - icon: brands/linkedin
    url: https://linkedin.com/in/hasanferdous/
  - icon: brands/github
    url: https://github.com/hferdous
  - icon: brands/orcid
    url: https://orcid.org/0000-0002-7182-1274
```

---

## Bio prose (replace body of `_index.md`)

```markdown
I am a Ph.D. candidate in Information Systems at the University of Maryland, Baltimore County, and will defend my dissertation in Summer 2026. My research addresses causal discovery in multivariate time series data exhibiting autocorrelation, non-stationarity, multi-seasonality, and irregular sampling. The work synthesizes statistical inference, machine learning, and information systems, building on a B.Sc. in Statistics from the University of Dhaka and graduate training in the UMBC Causal AI Lab under Dr. Md Osman Gani.

My work has appeared in KDD, MLHC, AAAI, ICMLA, and IEEE PerCom Workshops, with two manuscripts currently under review at TMLR and the KDD 2026 Dataset Track. The methodological contributions include CDANs and eCDANs, constraint-based discovery algorithms with optimized conditioning sets for autocorrelated and non-stationary time series; DCD, a decomposition-based framework for multi-seasonal data; and the TimeGraph benchmark suite for evaluating temporal causal discovery methods. The CDANs algorithm is publicly available as a Python package (`pip install cdans`). I have applied these methods through collaborations with climate scientists at the University of Colorado Boulder on Arctic sea ice prediction and Greenland supraglacial lake evolution, and with the UMBC Causal AI Lab on healthcare informatics.

I have served as a Graduate Teaching Assistant at UMBC for five consecutive semesters across four courses: Database Program Development, Advanced Database Project, Management Information Systems, and Structured Systems Analysis and Design. I have also developed a graduate lecture module on Causal AI. My pedagogical approach emphasizes active learning through the Flipped Classroom model and Think-Pair-Share exercises, the integration of authentic research datasets from healthcare and climate science, and frequent low-stakes assessment via embedded quizzes. Inclusive instruction that supports students across varying levels of preparation is central to my practice.

> *I am on the academic job market for Fall 2026 or Spring 2027 starts and am applying for tenure-track Assistant Professor positions in Computer Science, Information Systems, and Data Science. I welcome inquiries from departments seeking faculty at the intersection of methodological research and undergraduate mentorship. Email: [h.ferdous@umbc.edu](mailto:h.ferdous@umbc.edu).*

[Download CV (PDF)](/uploads/resume.pdf) · [Research Statement (PDF)](/uploads/research-statement.pdf) · [Teaching Statement (PDF)](/uploads/teaching-statement.pdf) · [Diversity Statement (PDF)](/uploads/diversity-statement.pdf)
```

---

## Notes on the rewrite

- Replaced em dashes with colons, periods, parentheses, or restructured sentences.
- Removed taglines such as "trustworthy AI for complex and dynamic systems" from the lead. The methodological contributions and venues do the work instead.
- Cut phrases including "I am committed to," "messy time-series data real systems produce," and "the community needs to use and evaluate them."
- Dropped bolding of common terms. Method names (CDANs, eCDANs, DCD, TimeGraph) keep their bold treatment on the page body if your theme styles them, but the prose itself reads cleanly without internal emphasis.
- Spelled out "University of Maryland, Baltimore County" on first reference; subsequent references can use "UMBC."
