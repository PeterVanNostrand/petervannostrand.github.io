---
title: "KRONE: Scalable LLM-Augmented Log Anomaly Detection via Hierarchical Abstraction"
authors: "Lei Ma, Jinyang Liu, Tieying Zhang, Peter M. VanNostrand, Dennis M. Hofmann, Lei Cao, Elke A. Rundensteiner, and Jianjun Chen"
collection: publications
permalink: /publication/KRONE
excerpt: "Log anomaly detection is crucial for uncovering system failures and security risks. Although logs originate from nested component executions with clear boundaries, this structure is lost when stored as flat sequences. As a result, state-of-the-art methods often miss true dependencies within executions while learning spurious correlations across unrelated events. We propose KRONE, the first hierarchical anomaly detection framework that automatically derives execution hierarchies from flat logs to enable modular, multi-level anomaly detection. At its core, the KRONE Log Abstraction Model extracts application-specific semantic hierarchies, which are used to recursively decompose log sequences into coherent execution units, referred to as KRONE Seqs. This transforms sequence-level detection into a set of modular KRONE Seq-level detection tasks. For each test KRONE Seq, KRONE adopts a hybrid modular detection strategy that routes between an efficient level-independent Local-Context detector for rapid filtering and a Nested-Aware detector that captures cross-level semantic dependencies, augmented with LLM-based anomaly detection and explanation. KRONE further optimizes detection through cached result reuse and early-exit strategies along the hierarchy. Experiments on three public benchmarks and one industrial dataset from ByteDance Cloud demonstrate that KRONE achieves substantial improvements in accuracy (42.49% to 87.98%), F1 score, data efficiency (117.3x reduction), resource efficiency (43.7x reduction), and interpretability. KRONE improves F1-score by 10.07% (82.76% to 92.83%) over prior methods while reducing LLM usage to only 1.1% to 3.3% of the test data."
paperurl: "http://arxiv.org/abs/2602.07303"
date: 2026-05-4
venue: "Proceedings of the 33rd IEEE International Conference on Data Engineering (ICDE)"
citation: "Lei Ma, Jinyang Liu, Tieying Zhang, Peter M. VanNostrand, Dennis M. Hofmann, Lei Cao, Elke A. Rundensteiner, and Jianjun Chen. 2026. KRONE: Scalable LLM-Augmented Log Anomaly Detection via Hierarchical Abstraction. Proceedings of the 2026 IEEE 33rd International Conference on Data Engineering (ICDE)."
codeurl: "https://github.com/LeiMa0324/KRONE"
ytvideourl: "https://www.youtube.com/embed/L_QpMUqXJuY?si=OjBumFWhDiRTiySP"
slidesurl: "/files/KRONE/KRONE-ICDE26-Slides.pdf"
---

**Check out the following resources related to this work!**

- See our project page at [https://leima0324.github.io/krone/](https://leima0324.github.io/krone/) for more details
- Check out an [interactive demo](https://leima0324.github.io/KRONE_Demo_official/) of KRONE

This paper has been accepted for publication at ICDE 2026, this page will be updated when the ICDE 2026 proceedings are available online.