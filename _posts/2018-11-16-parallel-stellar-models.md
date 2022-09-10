---
layout: single
title:  "Parallel Computing in Hydrodynamics Paper Published!"
date:   2018-11-16
categories: paper
header:
    overlay_image: /assets/images/news/ParallelModels.png
    overlay_filter: 0.6
    teaser: /assets/images/news/ParallelModels.png
    actions:
      - label: "Download here"
        url: "https://comp-astrophys-cosmol.springeropen.com/articles/10.1186/s40668-018-0025-5"
excerpt: "Our paper investigating methods for speeding up the SHIVA hydrodynamics code has been published in Computational Astrophysics and Astronomy"
---

With the advent of high-precision astronomy, high precision hydrodynamics models of stars and stellar events are more important than ever. These models, however, are computationally expensive so methods must be employed to speed them up. In this paper we investigated a number of methods for speeding up the implicit hydrodynamics code, SHIVA, using parallelization methods. In particular, we found that parallelization of the hydrodynamics part of the calculation is beneficial, speeding up the calculations on the order of the number of CPUs used in the calculation. On the other hand, parallelizing the nucleosynthesis part of the calculations adversely affected the computation because of the communication overhead required.
