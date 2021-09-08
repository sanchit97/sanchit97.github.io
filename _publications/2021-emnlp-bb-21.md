---
title: "Perturbing Inputs for Fragile Interpretations in Deep Natural Language Processing"
collection: publications
permalink: /publication/emnlp-bb-21-fragile-interpretations
excerpt: 
date: 2021-09-03
venue: 'EMNLP-BlackboxNLP'
paperurl: 'https://arxiv.org/pdf/2108.04990'
# citation: 'Sanchit Sinha'
---
Interpretability methods like Integrated Gradients and LIME are popular choices for explaining natural language model predictions with relative word importance scores. These interpretations need to be robust for trustworthy NLP applications in high-stake areas like medicine or finance. Our paper demonstrates how interpretations can be manipulated by making simple word perturbations on an input text. Via a small portion of word-level swaps, these adversarial perturbations aim to make the resulting text semantically and spatially similar to its seed input (therefore sharing similar interpretations). Simultaneously,  the generated examples achieve the same prediction label as the seed yet are given a substantially different explanation by the interpretation methods. Our experiments generate fragile interpretations to attack two SOTA interpretation methods, across three popular Transformer models and on two different NLP datasets. We observe that the rank order correlation drops by over 20% when less than 10% of words are perturbed on average. Further, rank-order correlation keeps decreasing as more words get perturbed. Furthermore, we demonstrate that candidates generated from our method have good quality metrics.

[Download paper here](https://arxiv.org/pdf/2108.04990.pdf)

<!-- Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1). -->