**English** | [简体中文](README.zh-CN.md)

# World Models: Definition, Clarification, Distinction, and Boundaries

Sixth paper of the [human-referential fitting theory](https://github.com/yuyuguilab/practice-fitting-theory) program. The paper extends the program's conceptual toolkit to the term "world model":

- **Definition** — a functional, not an entity, concept: two conditions (action-conditioning C1, component callability C2); three implementation families (written-in, learned, learn-then-formalize).
- **Clarification** — positional polymorphism: one functional concept located at four positions (component / evaluation benchmark / state representation / simulated environment), four forms of invocation (rollout / scoring / query / training ground & generation); the naming-competition genealogy and a survival clause.
- **Analysis** — three propositions (position, probability, task) and one limit (recursive self-improvement needs real-data anchoring; calibration cannot self-certify).
- **Distinctions** — from intelligence (policy vs. model) and from AGI (criterial mismatch, non-transferable progress); a structural analysis of the terminal "intelligent world model" (four routes, four requirements, three boundaries).
- Eight falsifiability clauses and an admission protocol for new cases.

## Build

```bash
tectonic paper.tex      # English edition
tectonic paper_zh.tex   # Chinese edition
```

Requires [tectonic](https://tectonic-typesetting.dev/). The first run downloads the CTAN bundle (including the Fandol CJK fonts used by both editions) over the network; later builds work offline.

## Editions

- `paper.tex` / `paper.pdf` — English
- `paper_zh.tex` / `paper_zh.pdf` — Chinese

## Cite

Yugui Yu. *World Models: Definition, Clarification, Distinction, and Boundaries*. Zenodo, v1.0.1. doi:[10.5281/zenodo.24384106](https://doi.org/10.5281/zenodo.24384106) (concept DOI; resolves to the latest version)

```bibtex
@article{yu2026worldmodels,
  author  = {Yugui Yu},
  title   = {World Models: Definition, Clarification, Distinction, and Boundaries},
  journal = {Zenodo},
  year    = {2026},
  version = {v1.0.1},
  doi     = {10.5281/zenodo.24384106},
  url     = {https://doi.org/10.5281/zenodo.24384106}
}
```

## License

CC BY 4.0. Author: Yugui Yu (YYG Strategy Lab).
