---
title: "HyperTuning: Toward Adapting Large Language Models without Back-propagation"
collection: publications
permalink: /publication/2022-11-22-hypertuning
excerpt: '<p>[<a href="https://arxiv.org/abs/2211.12485" style="color:#51ADC8;">Paper</a>] - <a href="/publication/2022-11-22-hypertuning" style="color:#51ADC8;">Abstract</a><br /><span style="font-family:Courier New">Citation</span>: Jason Phang, Yi Mao, Pengcheng He, Weizhu Chen <u>HyperTuning: Toward Adapting Large Language Models without Back-propagation</u>. <i>ICML 2023.</i></p>'
date: 2022-11-22
venue: 'ICML 2023'
---

Fine-tuning large language models for different tasks can be costly and inefficient, and even methods that reduce the number of tuned parameters still require full gradient-based optimization. We propose HyperTuning, a novel approach to model adaptation that uses a hypermodel to generate task-specific parameters for a fixed downstream model. We demonstrate a simple setup for hypertuning with HyperT5, a T5-based hypermodel that produces soft prefixes or LoRA parameters for a frozen T5 model from few-shot examples. We train HyperT5 in two stages: first, hyperpretraining with a modified conditional language modeling objective that trains a hypermodel to generate parameters; second, multi-task fine-tuning (MTF) on a large number of diverse language tasks. We evaluate HyperT5 on P3, MetaICL and Super-NaturalInstructions datasets, and show that it can effectively generate parameters for unseen tasks. Moreover, we show that using hypermodel-generated parameters as initializations for further parameter-efficient fine-tuning improves performance. HyperTuning can thus be a flexible and efficient way to leverage large language models for diverse downstream applications.
[<a href="https://arxiv.org/abs/2211.12485" style="color:#51ADC8;">Paper</a>]

<span style="font-family:Courier New">Citation</span>: Jason Phang, Yi Mao, Pengcheng He, Weizhu Chen <u>HyperTuning: Toward Adapting Large Language Models without Back-propagation</u>. <i>ICML 2023</i>. 
