# Site Update Checklist

Defense in Summer 2026 (by August). Job market for Fall 2026 and Spring 2027 starts. Target completion: site is content-correct by end of May 2026 and fully polished by end of August 2026.

---

## Week 1. High-priority corrections to existing content

### Publications page (factual corrections)

- [ ] Apply changes from `06-publications-update.md`.
- [ ] Update the Supraglacial Lake entry to ICMLA 2025 (currently labeled "arXiv").
- [ ] Create the eCDANs publication entry (currently missing).
- [ ] Add `url_code: 'https://github.com/hferdous/CDANs'` to the CDANs frontmatter and update the abstract to mention `pip install cdans`.
- [ ] Update DCD to `publication_types: ['manuscript']` with arXiv link and a note that the paper is under review at TMLR.
- [ ] Confirm that CDANs and eCDANs are described as constraint-based with optimized conditioning.
- [ ] Add the Manuscripts Under Review section. Two items only: DCD at TMLR and ClassyGlass at the KDD 2026 Dataset Track. G-DCD is not included; it has not been submitted.
- [ ] Add a Google Scholar link near the top of the Publications page.
- [ ] Verify that author pages exist for all co-authors.

### Add Honors and Service blocks

- [ ] Add the Honors and Awards block (COEIT Summer Student Project Award, COEIT poster Honorable Mention, MLHC Travel Award).
- [ ] Add the Professional Service block (reviewing for AAAI, PerCom, KDD-affiliated venues; UMBC presentations).

### Footer

- [ ] In `config/_default/params.yaml`, replace `"© 2025 Me."` with `"© 2026 Muhammad Hasan Ferdous."`

### Retire the stale blog posts

- [ ] Set `draft: true` in the frontmatter of both May 2024 blog posts.

### News block on homepage

- [ ] Apply the News widget from `07-news-entries.md`.
- [ ] Confirm that the CDANs package release entry is included.

### Bio and hero

- [ ] Apply changes from `01-bio-update.md`.
- [ ] Status line: "Ph.D. Candidate in Information Systems (defending Summer 2026)."
- [ ] Confirmed social URLs:
  - Google Scholar: `https://scholar.google.com/citations?user=fOBzV-QAAAAJ&hl=en`
  - ORCID: `https://orcid.org/0000-0002-7182-1274`
- [ ] Confirm that the bio prose mentions `pip install cdans` in the methodological contributions paragraph.

---

## Week 2. New pages

### Research page

- [ ] Create `content/research/_index.md` from `02-research-page.md`.
- [ ] Add a menu item with weight 20.

### Teaching page

- [ ] Create `content/teaching/_index.md` from `03-teaching-page.md`.
- [ ] Upload the Causal Discovery lecture slides PDF.
- [ ] Upload the lecture notes PDF.
- [ ] Add a menu item with weight 30.

### Software page (new)

- [ ] Create `content/software/_index.md` from `04-software-page.md`.
- [ ] Add a menu item with weight 35.
- [ ] If TimeGraph has a public GitHub repository, add the URL to the Software page.

### Diversity and Inclusion page

- [ ] Create `content/diversity/_index.md` from `05-diversity-page.md`.
- [ ] Add a menu item with weight 40.

### Upload application documents

- [ ] Strip institution-specific headers from the research, teaching, and diversity statements.
- [ ] Export each to PDF and upload to `static/uploads/`:
  - `resume.pdf`
  - `research-statement.pdf`
  - `teaching-statement.pdf`
  - `diversity-statement.pdf`
- [ ] Confirm that links from the bio resolve.

---

## Week 3. CV alignment and review

### CV

- [ ] Update `static/uploads/resume.pdf` to the current academic CV.
- [ ] Move DCD out of "Peer-Reviewed Papers" and into a "Manuscripts Under Review / Preprints" section with arXiv ID 2602.01433.
- [ ] Add `pip install cdans` and the GitHub URL to the CV.
- [ ] Consider adding a Software section to the CV listing CDANs, TimeGraph, and ClassyGlass.

### Review

- [ ] Run `hugo --minify` locally and resolve any errors.
- [ ] Request review from Dr. Md Osman Gani (advisor).
- [ ] Request review from a recently-hired tenure-track faculty member.
- [ ] Run a link checker (htmltest, muffet).
- [ ] Test the site on a mobile device.
- [ ] Add a "Last updated" line to the footer.

### Discoverability

- [ ] Verify that Google indexes the site (`site:mhasanferdous.github.io`).
- [ ] Confirm that Google Scholar lists all six papers.
- [ ] Pin the CDANs repository on your GitHub profile so it is visible to recruiters checking github.com/hferdous.

---

## Week 4. Buffer

Reserved for items that typically run long: reviewer feedback, mobile CSS adjustments, and any decision news from TMLR or KDD 2026 Dataset Track.

---

## Hard deadlines

- End of May 2026. Site functionally complete and content-correct.
- End of July 2026. Site fully polished. Defense done or imminent.
- End of August 2026. Defense complete; site reflects Ph.D. status; uploaded application materials updated.
- September to December 2026. Application season. Architecture frozen; the News feed continues to receive entries.

---

## File inventory

Eight files in this update.

1. `01-bio-update.md`. Bio and hero.
2. `02-research-page.md`. Research page.
3. `03-teaching-page.md`. Teaching page.
4. `04-software-page.md`. Software portfolio page (new).
5. `05-diversity-page.md`. Diversity and inclusion statement page.
6. `06-publications-update.md`. Publications page corrections.
7. `07-news-entries.md`. Homepage news feed.
8. `08-update-checklist.md`. This file.

---

## What this version captures

- Six publications and preprints (CDANs, TimeGraph, Arctic Sea Ice, eCDANs, DCD preprint, Supraglacial Lake).
- CDANs and eCDANs described as constraint-based with optimized conditioning.
- DCD listed as an arXiv preprint (2602.01433) under review at TMLR.
- CDANs available as a Python package (`pip install cdans`), referenced on the bio, Research page, Teaching page, Software page, News feed, and Publications entry.
- Defense in Summer 2026; job market targeting Fall 2026 and Spring 2027 starts.
- G-DCD not referenced anywhere; it remains a work in progress.
- Two manuscripts under review: DCD at TMLR and ClassyGlass at the KDD 2026 Dataset Track.

---

## Open items

1. TimeGraph GitHub URL. If a public repository exists, share the URL and I will add it to the Software page and the Publications entry.
2. UMBC Causal AI Lab. If Dr. Gani's lab maintains a public web page, consider linking to it from the bio.
3. Industry resume. Optional one-page industry-format resume as an alternate download.
4. DCD arXiv ID. The identifier `2602.01433` follows the YYMM convention as February 2026. Confirm that this is the assigned ID once the preprint is live.
