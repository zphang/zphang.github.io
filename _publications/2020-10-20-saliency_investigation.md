---
title: "Investigating and Simplifying Masking-based Saliency Methods for Model Interpretability"
collection: publications
permalink: /publication/2020-10-20-saliency_investigation
excerpt: '<p>[<a href="https://arxiv.org/abs/2010.09750" style="color:#51ADC8;">Paper</a>] [<a href="https://github.com/zphang/saliency_investigation" style="color:#51ADC8;">Code</a>]- <a href="/publication/2020-10-20-saliency_investigation" style="color:#51ADC8;">Abstract</a><br /><span style="font-family:Courier New">Citation</span>: Jason Phang, Jungkyu Park, Krzysztof J. Geras. <u>Investigating and Simplifying Masking-based Saliency Methods for Model Interpretability</u>. <i>Preprint, 2020.</i></p>'
date: 2020-10-20
venue: 'Preprint'
---

Saliency maps that identify the most informative regions of an image for a classifier are valuable for model interpretability. A common approach to creating saliency maps involves generating input masks that mask out portions of an image to maximally deteriorate classification performance, or mask in an image to preserve classification performance. Many variants of this approach have been proposed in the literature, such as counterfactual generation and optimizing over a Gumbel-Softmax distribution. Using a general formulation of masking-based saliency methods, we conduct an extensive evaluation study of a number of recently proposed variants to understand which elements of these methods meaningfully improve performance. Surprisingly, we find that a well-tuned, relatively simple formulation of a masking-based saliency model outperforms many more complex approaches. We find that the most important ingredients for high quality saliency map generation are (1) using both masked-in and masked-out objectives and (2) training the classifier alongside the masking model. Strikingly, we show that a masking model can be trained with as few as 10 examples per class and still generate saliency maps with only a 0.7-point increase in localization error. 

[<a href="https://arxiv.org/abs/2010.09750">Paper</a>]

<span style="font-family:Courier New">Citation</span>: Jason Phang, Jungkyu Park, Krzysztof J. Geras. <u>Investigating and Simplifying Masking-based Saliency Methods for Model Interpretability</u>. <i>Preprint, 2020</i> 