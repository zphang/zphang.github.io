---
title: "Investigating the Effectiveness of HyperTuning via Gisting"
collection: publications
permalink: /publication/2024-02-26-hypergisting
excerpt: '<p>[<a href="https://arxiv.org/abs/2402.16817" style="color:#51ADC8;">Paper</a>] - <a href="/publication/2024-02-26-hypergisting" style="color:#51ADC8;">Abstract</a><br /><span style="font-family:Courier New">Citation</span>: Jason Phang <u>Investigating the Effectiveness of HyperTuning via Gisting</u>. <i>Preprint.</i></p>'
date: 2024-02-26
venue: 'Preprint'
---

Gisting (Mu et al., 2023) is a simple method for training models to compress information into fewer token representations using a modified attention mask, and can serve as an economical approach to training Transformer-based hypernetworks. We introduce HyperLlama, a set of Gisting-based hypernetworks built on Llama-2 models that generates task-specific soft prefixes based on few-shot inputs. In experiments across P3, Super-NaturalInstructions and Symbol Tuning datasets, we show that HyperLlama models can effectively compress information from few-shot examples into soft prefixes. However, they still underperform multi-task fine-tuned language models with full attention over few-shot in-context examples. We also show that HyperLlama-generated soft prefixes can serve as better initializations for further prefix tuning. Overall, Gisting-based hypernetworks are economical and easy to implement, but have mixed empirical performance.
[<a href="https://arxiv.org/abs/2402.16817" style="color:#51ADC8;">Paper</a>]

<span style="font-family:Courier New">Citation</span>: Jason Phang <u>Investigating the Effectiveness of HyperTuning via Gisting</u>. <i>Preprint.</i> 

