# An introduction to Brightway 2

> [!IMPORTANT]  
> 1. Works really only for [Brigthway 2](https://github.com/brightway-lca/brightway2), not [Brightway 2.5](https://github.com/brightway-lca/brightway25). I might write an update some time, perhaps when Brightway 3 is out 😉
> 2. This repository has not been maintained since Nov 2019, in part because I have moved my focus elsewhere and in part because I had lost access to the previous account where this repo was stored. Apologies to those who have posted issues since then; however, having now access to the repo again on my current account does not mean that I will engage in issue-solving. Sorry again! 🙃

[Brightway](https://docs.brightway.dev) is a Python-based free and open-source software for [lifecycle assessment](https://en.wikipedia.org/wiki/Life-cycle_assessment) (LCA; see [here](https://www.nature.com/articles/s43017-023-00449-2) for a recent good overview, also accessible via [LinkedIn](https://www.linkedin.com/posts/maximilian-koslowski-711365143_lca-to-guide-solutions-for-the-triple-planetary-activity-7083024231541743616-G6Gy?utm_source=share&utm_medium=member_desktop)).

LCA is a tool used for analysing the environmental (and other) pressures associated with products, technologies, and countries. This may sound a little big, but it's all just a matter of which database you use. Commonly, the term LCA is understood in its process-based variant where its application is bound to comparative and hotspot analysis. That is, LCAs are performed for individual products like shopping bags to figure out if a cotton-based one is more environmentally-friendly (and where along its supply chain) than a single-use plastic one (see for example [this study](https://norsus.no/en/publikasjon/life-cycle-assessment-of-plastic-bags-and-othercarrying-solutions-for-groceries-in-norway/)), or similarly with single-use vs reusable food packaging (see for example [this study](https://www.lifecycleinitiative.org/wp-content/uploads/2022/10/UNEP-D010-Food-Packaging-Report_Final-Version-1-1.pdf/UNEP-D010-Food-Packaging-Report-2-1.pdf)). They may also be performed for product fleets such as [this (Brightway-based) one](https://viewer.webservice-energy.org/lca-wind-dk/) on wind turbines in Denmark. The mathematics of LCA are, however, derived from the field of [input-output economics](https://en.wikipedia.org/wiki/Input%E2%80%93output_model) which has a history dating back more than a hundred years. IO-based LCA is used for calculating environmental footprints of regions and their citizens (see for example [here](https://www.nature.com/articles/s41561-018-0113-9) for an overview of its applications and [here](https://www.environmentalfootprints.org/infographics) for an overview of footprints). Popular databases for process-based and IO-based LCA are, respectively, [ecoinvent](https://ecoinvent.org/) and [EXIOBASE](https://zenodo.org/record/5589597). The focus of Brightway has typically been process-based LCA.

This repo contains two files: a Jupyter notebook and a spreadsheet that is used at one point in that notebook. The notebook is long, really long. So be ready for spending some time here! And have fun 😉

---

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
