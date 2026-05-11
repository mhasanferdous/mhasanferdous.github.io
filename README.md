# mhasanferdous.github.io

Personal academic website. Plain HTML, CSS, and PDFs. No build step.

## File structure

```
mhasanferdous.github.io/
├── index.html              # Homepage (bio, news, featured publications)
├── research.html           # Research vision, contributions, agenda
├── publications.html       # Full publication list, preprints, awards, service
├── teaching.html           # Teaching philosophy, record, course preparation
├── software.html           # CDANs, TimeGraph, ClassyGlass
├── diversity.html          # Diversity statement
├── css/
│   └── style.css           # All styling
├── files/
│   ├── resume.pdf          # Academic CV
│   ├── research-statement.pdf
│   ├── teaching-statement.pdf
│   └── diversity-statement.pdf
└── README.md               # This file
```

## Deployment

The site is hosted on GitHub Pages and serves directly from the `main` branch root.

### One-time setup

1. Go to the repository on GitHub
2. Settings → Pages
3. Source: **Deploy from a branch**
4. Branch: **main**, folder: **/ (root)**
5. Save

The site builds and deploys automatically within one or two minutes of each push to `main`.

### Local preview

No build step is needed. To preview locally, open `index.html` in a browser, or run a simple local server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Making updates

### Adding a news entry

Edit `index.html`, find the `<ul class="news-list">` block, and add a new `<li>` at the top:

```html
<li>
  <span class="news-date">Month Year</span>
  <span class="news-body">Description of the news. Links go in <a href="...">like this</a>.</span>
</li>
```

### Adding a publication

Edit `publications.html`, find the `<ul class="entry-list">` under "Peer-Reviewed Publications," and add a new `<li>` in reverse chronological order:

```html
<li>
  <div class="pub-title">
    <a href="DOI_OR_URL">Paper Title</a>
  </div>
  <div class="pub-authors"><strong>Muhammad Hasan Ferdous</strong>, Co-Author, Co-Author</div>
  <div class="pub-venue">Venue Name, Year.</div>
  <div class="pub-links">
    <a href="DOI_URL">DOI</a>
    <a href="ARXIV_URL">arXiv</a>
    <a href="CODE_URL">Code</a>
  </div>
</li>
```

Also add a corresponding entry to the News block on `index.html`.

### Updating the CV or other PDFs

Replace the file in `files/`. The filename must stay the same so the links continue to work.

- `files/resume.pdf` is the CV
- `files/research-statement.pdf` is the research statement
- `files/teaching-statement.pdf` is the teaching statement
- `files/diversity-statement.pdf` is the diversity statement

### Updating the bio

Edit the three paragraphs in `index.html` inside the `<section class="hero">` block.

### Removing the job market banner

After accepting a position, delete the `<div class="market-banner">...</div>` block from `index.html` and remove the "(defending Summer 2026)" suffix from the role line.

## Commit and push workflow

```bash
git add .
git commit -m "Brief description of the change"
git push origin main
```

GitHub Pages will rebuild within a few minutes.

## Styling

All styles are in `css/style.css`. Color tokens and typography are defined as CSS custom properties at the top of the file. To change the accent color (currently a muted oxblood), edit the `--accent` and `--accent-hover` values in `:root`.
