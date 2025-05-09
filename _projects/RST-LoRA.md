---
layout: project
title: "RST-LoRA: A Discourse-Aware Low-Rank Adaptation for Long Document Abstractive Summarization"

[//]: # (subtitle: "Randomizing Over Randomized Experiments")
---

<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

### 📄 Abstract

For long document summarization, discourse structure is important to discern the key content of the text and the differences in importance level between sentences. Unfortunately, the integration of rhetorical structure theory (RST) into parameter-efficient fine-tuning strategies for long document summarization remains unexplored. Therefore, this paper introduces RST-LoRA and proposes four RST-aware variants to explicitly incorporate RST into the LoRA model. Our empirical evaluation demonstrates that incorporating the type and uncertainty of rhetorical relations can complementarily enhance the performance of LoRA in summarization tasks. Furthermore, the best-performing variant we introduced outperforms the vanilla LoRA and full-parameter fine-tuning models, as confirmed by multiple automatic and human evaluations, and even surpasses previous state-of-the-art methods.

### 🔍 Method Overview

<div style="display: flex; justify-content: center;">
    <img src="../assets/publications/NAACL2024/RST-LoRA.png" alt="RST-LoRA" style="max-width:100%; width:800px;">
</div>

### 💻 Code

Our code is publicly available on GitHub: [<img src="https://img.shields.io/badge/GitHub-RST--LoRA-blue?logo=github" alt="RST-LoRA GitHub Repository">](https://github.com/dongqi-me/RST_LoRA)

### 📚 Citation

<div class="citation-container" style="background-color: #f8f9fa; border-left: 4px solid #007bff; padding: 15px; border-radius: 4px; margin: 20px 0;">
<strong>Please cite our work if you find it useful:</strong>

{% highlight bibtex %}
@inproceedings{pu-demberg-2024-rst,
    title = "{RST}-{L}o{RA}: A Discourse-Aware Low-Rank Adaptation for Long Document Abstractive Summarization",
    author = "Liu, Dongqi  and
      Demberg, Vera",
    editor = "Duh, Kevin  and
      Gomez, Helena  and
      Bethard, Steven",
    booktitle = "Proceedings of the 2024 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies (Volume 1: Long Papers)",
    month = jun,
    year = "2024",
    address = "Mexico City, Mexico",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.naacl-long.121",
    doi = "10.18653/v1/2024.naacl-long.121",
    pages = "2200--2220",
}
{% endhighlight %}
</div>

<div style="text-align: center; margin-top: 30px;">
    <a href="https://aclanthology.org/2024.naacl-long.121" target="_blank"><img src="https://img.shields.io/badge/NAACL-2024-blue" alt="NAACL 2024"></a>
    <a href="https://doi.org/10.18653/v1/2024.naacl-long.121" target="_blank"><img src="https://img.shields.io/badge/DOI-10.18653%2Fv1%2F2024.naacl--long.121-orange" alt="DOI"></a>
    <a href="https://github.com/dongqi-me/RST_LoRA" target="_blank"><img src="https://img.shields.io/badge/Code-Available-green?logo=github" alt="Code"></a>
</div>

