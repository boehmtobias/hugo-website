---
title: "Model-Driven Legacy System Modernization at Scale"
date: 2026-02-04
tags: [ "model-driven engineering", "legacy modernization", "semi-automatic migration",
        "intermediate model", "reverse engineering", "model transformation", "maintainability",
        "traceability", "industrial case study" ]
author: [ "Tobias Böhm", "Jens Guan Su Tien", "Mohini Nonnenmann", "Tom Schoonbaert",
          "Bart Carpels", "Andreas Biesdorf" ]
description: "Industrial experience report on a model-driven approach to legacy system 
              modernization, using an enriched intermediate model to migrate .NET MVC 
              applications to modern web stacks."
summary: "Industrial experience report on a model-driven approach to legacy system
          modernization, using an enriched intermediate model to migrate .NET MVC
          applications to modern web stacks."
editPost:
  URL: "https://doi.org/10.48550/arXiv.2602.04341"
  Text: "arXiv.org cs.SE"

---

---

##### Links

- [Article](https://arxiv.org/abs/2602.04341)
- [PDF](https://arxiv.org/pdf/2602.04341)

---

##### Abstract

<p style="text-align: justify;">
This experience report presents a model-driven approach to legacy system modernization that inserts an enriched,
technology-agnostic intermediate model between the legacy codebase and the modern target platform, and reports on its
application and evaluation. The four-stage process of analysis, enrichment, synthesis, and transition systematically
extracts, abstracts, and transforms system artifacts. We apply our approach to a large industrial application built on
legacy versions of the .NET Framework and this http URL MVC and show that core user interface components and page
structures can be migrated semi-automatically to a modern web stack while preserving functional behavior and essential
non-functional qualities. By consolidating architectural knowledge into explicit model representations, the resulting
codebase exhibits higher maintainability and extensibility, thereby improving developer experience. Although automation
is effective for standard patterns, migration of bespoke layout composites remains challenging and requires targeted
manual adaptation. Our contributions are: (i) an end-to-end model-driven process, (ii) an enriched intermediate model
that captures structure, dependencies, and semantic metadata, (iii) transformation rules that preserve functional
behavior and essential non-functional qualities, and (iv) application and evaluation of the approach in an industrial
setting. Overall, model-based abstractions reduce risk and effort while supporting scalable, traceable modernization of
legacy applications. Our approach generalizes to comparable modernization contexts and promotes reuse of migration
patterns.
</p>
---

##### Citation

Böhm, T., Tien, J. G. S., Nonnenmann, M., Schoonbaert, T., Carpels, B., & Biesdorf, A. (2026). Model-Driven Legacy
System Modernization at Scale. In Proceedings of the 1st Workshop on Code Translation, Transformation, and
Modernization (ReCode ’26) (to appear). ACM. https://doi.org/10.48550/arXiv.2602.04341

```BibTeX
@inproceedings{Bohm2026ModelDrivenLS,
author = {Tobias Böhm and Jens Guan Su Tien and Mohini Nonnenmann and Tom Schoonbaert and Bart Carpels and Andreas Biesdorf},
doi = {10.48550/arXiv.2602.04341},
publisher = {ACM},
title = {Model-Driven Legacy System Modernization at Scale},
booktitle = {Proceedings of the 1st Workshop on Code Translation, Transformation, and Modernization (ReCode '26)},
note = {Accepted for publication at the 1st Workshop on Code Translation, Transformation, and Modernization (ReCode '26), co-located with ICSE 2026},
year = {2026}}
```
