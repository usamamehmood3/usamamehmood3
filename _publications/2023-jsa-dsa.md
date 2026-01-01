---
title: "A distributed simplex architecture for multi-agent systems"
collection: publications
category: manuscripts
permalink: /publication/2023-jsa-dsa
excerpt: 'Extend simplex architecture for runtime assurance of multi-agent systems.'
date: 2023-01-01
header:
  teaser: publications/2023_jsa_dsa.png
venue: 'Journal of Systems Architecture'
slidesurl: 'https://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://academicpages.github.io/files/slides2.pdf'
bibtexurl: 'https://academicpages.github.io/files/slides2.pdf'
---

We present the Distributed Simplex Architecture (DSA), a new runtime assurance technique that provides safety guarantees for multi-agent systems (MASs). DSA is inspired by the Simplex control architecture of Sha et al., but with some significant differences. The traditional Simplex approach is limited to single-agent systems or a MAS with a centralized control scheme. DSA addresses this limitation by extending the scope of Simplex to include MASs under distributed control. In DSA, each agent runs a local instance of traditional Simplex such that the preservation of safety in the local instances implies safety for the entire MAS. Control Barrier Functions (CBFs) play a critical role. They are used to define DSA’s core components – the baseline controller and the decision module’s logic for switching between advanced and baseline control – and they provide the basis for the proof of safety. We present a general proof of safety for DSA, provided the CBF-related optimization problem solved by the baseline controller is feasible (has a solution) at each time step for which the baseline controller is in control. We also propose a novel extension to the switching logic designed to avoid states in which this optimization problem is infeasible. Finally, we present experimental results for several case studies, including flocking with collision avoidance, safe navigation of ground rovers through way-points, and safe operation of a microgrid.

