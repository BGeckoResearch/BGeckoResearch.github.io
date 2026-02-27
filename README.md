# BGeckoLab (BGecko Research)

**BGeckoLab** is the public research front for **BGecko**: mathematics, physics, and AI/ML work with an emphasis on *rigor, reproducibility, and open artifacts* (code, notes, and writeups).

- Website: https://bgecko.org 
- Repository: https://github.com/BGeckoResearch/BGeckoResearch.github.io

---

## Research Pillars

This repository aggregates and organizes work in:

1. **Mathematics**
   - Functional analysis, operator theory, spectral methods  
   - C\*-algebras / von Neumann algebras (when relevant)
   - Topological / measure-theoretic foundations for learning systems

2. **Physics**
   - Energy-based modeling viewpoints (Hamiltonians, potentials)
   - Statistical mechanics / variational principles as modeling primitives

3. **AI / ML**
   - Energy-based models (EBMs), probabilistic modeling, universality questions
   - Approximation theory + inference regimes (Laplace, asymptotics, mixtures)
   - Robust evaluation + reproducible pipelines

> **Guiding constraint:** every claim that matters should map to (a) a formal statement, (b) a measurable test, or (c) a reproducible experiment.

---

## What’s in this repo?

This is primarily the **site + hub** repository.

Typical contents (your repo may vary):
- `index.html` / `style.css` / `js/` — the site frontend
- `img/` — figures, diagrams, assets
- `space-dashboard.html` — dashboards / experiments / pages

If you’re looking for **core research code**, it may live in separate repositories (recommended).  
If so, add a list here:

### Related Repositories (recommended pattern)
- `bgecko-<project-name>` — code + experiments
- `bgecko-notes` — technical notes / proofs / derivations
- `bgecko-papers` — paper sources (LaTeX) and release PDFs

---

## Active Projects

A living list of current threads. Keep it short and high signal.

- **[Project 1: Title]** — 1–2 lines: goal + what’s new.
- **[Project 2: Title]** — 1–2 lines.
- **[Project 3: Title]** — 1–2 lines.

**Status legend:** `idea → draft → experiments → preprint → submitted → published`

---

## Reproducibility Policy

If a project includes experiments, the target standard is:

- pinned dependencies (e.g., `requirements.txt` / `poetry.lock` / `environment.yml`)
- deterministic seeds when feasible
- runnable scripts and/or notebooks
- a minimal reproduction path in the project README

When a result is not reproducible yet, it should be labeled **WIP**.

---

## How to Cite

If you use or reference this work, cite the corresponding preprint/release page.

**Preferred:** DOI-based citations (Zenodo/OSF) when available.

Example (generic; replace when you have DOI):
```bibtex
@misc{bgecko2026_project,
  author       = {BGecko Research},
  title        = {<Project Title>},
  year         = {2026},
  howpublished = {\url{https://bgecko.org}},
  note         = {Accessed: YYYY-MM-DD}
}
