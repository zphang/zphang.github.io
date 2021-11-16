---
title: "Adversarially Constructed Evaluation Sets Are More Challenging, but May Not Be Fair"
collection: publications
permalink: /publication/2021-11-15-adversarial
excerpt: '<p>[<a href="https://jasonphang.com/files/advpaper.pdf" style="color:#51ADC8;">Paper</a>] - <a href="/publication/2021-11-15-adversarial" style="color:#51ADC8;">Abstract</a><br /><span style="font-family:Courier New">Citation</span>: Jason Phang, Angelica Chen, William Huang, Samuel R. Bowman <u>Adversarially Constructed Evaluation Sets Are More Challenging, but May Not Be Fair</u>. <i>Preprint, 2021.</i></p>'
date: 2021-11-15
venue: 'Preprint'
---

More capable language models increasingly saturate existing task benchmarks, in some cases outperforming humans. This has left little headroom with which to measure further progress. Adversarial dataset creation has been proposed as a strategy to construct more challenging datasets, and two common approaches are: (1) filtering out easy examples and (2) model-in-the-loop data collection. In this work, we study the impact of applying each approach to create more challenging evaluation datasets. We adapt the AFLite algorithm to filter evaluation data, and run experiments against 18 different adversary models. We find that AFLite indeed selects more challenging examples, lowering the performance of evaluated models more as stronger adversary models are used. However, the resulting ranking of models can also be unstable and highly sensitive to the choice of adversary model used. Moreover, AFLite oversamples examples with low annotator agreement, meaning that model comparisons hinge on the most contentiously labeled examples. Smaller-scale experiments on the adversarially collected datasets ANLI and AdversarialQA show similar findings, broadly lowering performance with stronger adversaries while disproportionately affecting the adversary model.

[<a href="https://jasonphang.com/files/advpaper.pdf" style="color:#51ADC8;">Paper</a>]

<span style="font-family:Courier New">Citation</span>: Jason Phang, Angelica Chen, William Huang, Samuel R. Bowman <u>Adversarially Constructed Evaluation Sets Are More Challenging, but May Not Be Fair</u>. <i>Preprint, 2021.</i> 