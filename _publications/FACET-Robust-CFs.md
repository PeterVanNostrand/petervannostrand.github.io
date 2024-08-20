---
title: "FACET: Robust Counterfactual Explanation Analytics"
collection: publications
permalink: /publication/FACET-Robust-CFs
excerpt: "Machine learning systems are deployed in domains such as hiring and healthcare, where undesired classifications can have serious ramifications for the user. Thus, there is a rising demand for explainable AI systems which provide actionable steps for lay users to obtain their desired outcome. To meet this need, we propose FACET, the first explanation analytics system which supports a user in interactively refining counterfactual explanations for decisions made by tree ensembles. As FACET's foundation, we design a novel type of counterfactual explanation called the counterfactual region. Unlike traditional counterfactuals, FACET's regions concisely describe portions of the feature space where the desired outcome is guaranteed, regardless of variations in exact feature values. This property, which we coin explanation robustness, is critical for the practical application of counterfactuals. We develop a rich set of novel explanation analytics queries which empower users to identify personalized counterfactual regions that account for their real-world circumstances. To process these queries, we develop a compact high-dimensional counterfactual region index along with index-aware query processing strategies for near real-time explanation analytics. We evaluate FACET against state-of-the-art explanation techniques on eight public benchmark datasets and demonstrate that FACET generates actionable explanations of similar quality in an order of magnitude less time while providing critical robustness guarantees. Finally, we conduct a preliminary user study which suggests that FACET's regions lead to higher user understanding than traditional counterfactuals."
date: 2024-01-01
venue: "Proceedings of the ACM on Management of Data (SIGMOD)"
slidesurl: "/files/FACET/FACET-SIGMOD24-Slides.pptx"
paperurl: "https://dl.acm.org/doi/10.1145/3626729?cid=99659850355"
citation: "Peter M. VanNostrand, Huayi Zhang, Dennis M. Hofmann, and Elke A. Rundensteiner. 2023. FACET: Robust Counterfactual Explanation Analytics. Proc. ACM Manag. Data 1, 4, Article 242 (December 2023), 27 pages. https://doi.org/10.1145/3626729"
---

<link rel="stylesheet" type="text/css" media="all" href="/assets/css/panelstory.css" />

<a class="panel-story" href="/files/FACET/FACET-SIGMOD24-Panel-Story.pptx"><img src="/files/FACET/FACET-SIGMOD24-Panel-Story.gif" alt="a carousel of slides presenting the paper"  width="100%" /></a>

Machine learning systems are deployed in domains such as hiring and healthcare, where undesired classifications can have serious ramifications for the user. Thus, there is a rising demand for explainable AI systems which provide actionable steps for lay users to obtain their desired outcome. To meet this need, we propose FACET, the first explanation analytics system which supports a user in interactively refining counterfactual explanations for decisions made by tree ensembles. As FACET's foundation, we design a novel type of counterfactual explanation called the counterfactual region. Unlike traditional counterfactuals, FACET's regions concisely describe portions of the feature space where the desired outcome is guaranteed, regardless of variations in exact feature values. This property, which we coin explanation robustness, is critical for the practical application of counterfactuals. We develop a rich set of novel explanation analytics queries which empower users to identify personalized counterfactual regions that account for their real-world circumstances. To process these queries, we develop a compact high-dimensional counterfactual region index along with index-aware query processing strategies for near real-time explanation analytics. We evaluate FACET against state-of-the-art explanation techniques on eight public benchmark datasets and demonstrate that FACET generates actionable explanations of similar quality in an order of magnitude less time while providing critical robustness guarantees. Finally, we conduct a preliminary user study which suggests that FACET's regions lead to higher user understanding than traditional counterfactuals.

Downloads: [Paper](https://dl.acm.org/doi/10.1145/3626729?cid=99659850355) ⏐ [Code](https://github.com/PeterVanNostrand/FACET) ⏐ [Slides](/files/FACET/FACET-SIGMOD24-Slides.pptx) ⏐ [Poster](/files/FACET/FACET-SIGMOD24-Poster.pptx)

**Check out the following resources related to this work!**

- We published a comprehensive user evaluation of FACET's novel concept of Counterfactual Regions in ACM FAccT 2024 (Fairness Accountability Transparency). Check it out [here](https://petervannostrand.github.io/publication/Examining-Actionable-Recourse)!
- We also develop an open source explanation user interface for lay users to interact with FACET's analytics. Check out our [demo paper](/publication/FACET-Demo) at VLDB 2024
- We provide an open source build-ready implementation of FACET and the accompanying dashboard developed in Python and ReactJS at [https://github.com/PeterVanNostrand/FACET](https://github.com/PeterVanNostrand/FACET)

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/mzBQaSaNtMM?si=diOI8tMg7JUJZw5I" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<br>
