---
title: "Struc-Bench: Are Large Language Models Good at Generating Complex Structured Tabular Data?"
collection: publications
permalink: /publication/2023-09-16-struc-bench
excerpt: '<p>[<a href="https://aclanthology.org/2024.naacl-short.2/" style="color:#51ADC8;">Paper</a>] - <a href="/publication/2023-09-16-struc-bench" style="color:#51ADC8;">Abstract</a><br /><span style="font-family:Courier New">Citation</span>: Xiangru Tang, Yiming Zong, Jason Phang, Yilun Zhao, Wangchunshu Zhou, Arman Cohan, Mark Gerstein <u>Struc-Bench: Are Large Language Models Good at Generating Complex Structured Tabular Data?</u>. <i>NAACL 2024.</i></p>'
date: 2023-09-16
venue: 'NAACL 2024'
---

Despite the remarkable capabilities of Large Language Models (LLMs) like GPT-4, producing complex, structured tabular data remains challenging. Our study assesses LLMs’ proficiency in structuring tables and introduces a novel fine-tuning method, cognizant of data structures, to bolster their performance. We unveil Struc-Bench, a comprehensive benchmark featuring prominent LLMs (GPT-NeoX-20B, GPT-3.5, GPT-4, and Vicuna), which spans text tables, HTML, and LaTeX formats. Our proposed FormatCoT aids in crafting format-specific instructions from the intended outputs to populate this benchmark. Addressing the gap in task-centered evaluation, we propose two innovative metrics, P-Score (Prompting Score) and H-Score (Heuristical Score), to more accurately gauge LLM performance. Our experiments show that applying our structure-aware fine-tuning to LLaMA-7B leads to substantial performance gains, outshining its LLM counterparts across most measures. In-depth error analysis and creating an ability map across six dimensions, coverage, formatting, reasoning, comprehension, pragmatics, and hallucination, highlight areas for future enhancements and suggest forthcoming research trajectories. Our code and models can be found at https://github.com/gersteinlab/Struc-Bench.
[<a href="https://aclanthology.org/2024.naacl-short.2/" style="color:#51ADC8;">Paper</a>]

<span style="font-family:Courier New">Citation</span>: Xiangru Tang, Yiming Zong, Jason Phang, Yilun Zhao, Wangchunshu Zhou, Arman Cohan, Mark Gerstein <u>Struc-Bench: Are Large Language Models Good at Generating Complex Structured Tabular Data?</u>. <i>NAACL 2024.</i> 