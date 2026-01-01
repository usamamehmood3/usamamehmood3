---
title: "The black-box simplex architecture for runtime assurance of multi-agent CPS"
collection: publications
category: manuscripts
permalink: /publication/2024-isse-bsa
excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2024-03-21
header:
  teaser: publications/2024_isse_bsa.png
venue: 'Innovations in Systems and Software Engineering'
slidesurl: 'https://academicpages.github.io/files/slides3.pdf'
paperurl: "https://link.springer.com/content/pdf/10.1007/s11334-024-00553-6.pdf"
citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

The Simplex Architecture is a runtime assurance framework where control authority may switch from an unverified and potentially unsafe advanced controller to a backup baseline controller in order to maintain the safety of an autonomous cyber-physical system. In this work, we show that runtime checks can replace the requirement to statically verify safety of the baseline controller. This is important as there are many powerful control techniques, such as model-predictive control and neural network controllers, that work well in practice but are difficult to statically verify. Since the method does not use internal information about the advanced or baseline controller, we call the approach the Black-Box Simplex Architecture. We prove the architecture is safe and present two case studies where (i) model-predictive control provides safe multi-robot coordination, and (ii) neural networks provably prevent collisions in groups of F-16 aircraft, despite the controllers occasionally outputting unsafe commands. We further show how to safely blend commands from the advanced and baseline controllers in multi-agent systems, reducing the performance impact when switching is necessary to preserve safety.
