---
title: "Modellgetriebene Modernisierung von Altsystemen im großen Maßstab [EN]"
date: 2026-02-04
tags: [ "modellgetriebene Softwareentwicklung", "Modernisierung von Altsystemen",
        "semi-automatische Migration", "Zwischenmodell", "Reverse Engineering",
        "Modelltransformation", "Wartbarkeit", "Nachverfolgbarkeit",
        "industrielle Fallstudie" ]
author: [ "Tobias Böhm", "Jens Guan Su Tien", "Mohini Nonnenmann", "Tom Schoonbaert",
          "Bart Carpels", "Andreas Biesdorf" ]
description: "Industrie-Erfahrungsbericht über einen modellgetriebenen Ansatz zur 
              Modernisierung von Altsystemen, der ein angereichertes Zwischenmodell nutzt, 
              um .NET-MVC-Anwendungen auf moderne Web-Stacks zu migrieren."
summary: "Industrie-Erfahrungsbericht über einen modellgetriebenen Ansatz zur 
          Modernisierung von Altsystemen, der ein angereichertes Zwischenmodell nutzt, 
          um .NET-MVC-Anwendungen auf moderne Web-Stacks zu migrieren."
editPost:
  URL: "https://doi.org/10.48550/arXiv.2602.04341"
  Text: "arXiv.org cs.SE"

---

---

##### Links

- [Artikel](https://arxiv.org/abs/2602.04341)
- [PDF](https://arxiv.org/pdf/2602.04341)

---

##### Abstract

<p style="text-align: justify;">
Dieser Erfahrungsbericht stellt einen modellgetriebenen Ansatz zur Modernisierung von Altsystemen vor, der ein
angereichertes, technologieunabhängiges Zwischenmodell zwischen der Legacy-Codebasis und der modernen Zielplattform
einfügt, und berichtet über dessen Anwendung und Evaluation. Der vierstufige Prozess aus Analyse, Anreicherung,
Synthese und Transition extrahiert, abstrahiert und transformiert systematisch Systemartefakte. Wir wenden unseren
Ansatz auf eine große industrielle Anwendung an, die auf Legacy-Versionen des .NET Frameworks und ASP.NET MVC basiert,
und zeigen, dass zentrale Komponenten der Benutzeroberfläche sowie Seitenstrukturen semi-automatisch auf einen
modernen Web-Stack migriert werden können, während funktionales Verhalten und wesentliche nicht-funktionale
Eigenschaften erhalten bleiben. Durch die Konsolidierung architektonischen Wissens in expliziten Modellrepräsentationen
weist die resultierende Codebasis eine höhere Wartbarkeit und Erweiterbarkeit auf, wodurch die Entwicklererfahrung
verbessert wird. Obwohl die Automatisierung für Standardmuster effektiv ist, bleibt die Migration maßgeschneiderter
Layout-Komposite herausfordernd und erfordert gezielte manuelle Anpassungen. Unsere Beiträge sind: (i) ein
durchgängiger modellgetriebener Prozess, (ii) ein angereichertes Zwischenmodell, das Struktur, Abhängigkeiten und
semantische Metadaten erfasst, (iii) Transformationsregeln, die funktionales Verhalten und wesentliche
nicht-funktionale Qualitäten bewahren, sowie (iv) die Anwendung und Evaluation des Ansatzes in einem industriellen
Kontext. Insgesamt reduzieren modellbasierte Abstraktionen Risiko und Aufwand und unterstützen eine skalierbare,
nachverfolgbare Modernisierung von Altsystemen. Unser Ansatz lässt sich auf vergleichbare Modernisierungskontexte
übertragen und fördert die Wiederverwendung von Migrationsmustern.
</p>
---

##### Zitierempfehlung

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
