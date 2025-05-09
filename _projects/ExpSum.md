---
layout: project
title: Explanatory Summarization with Discourse-Driven Planning

[//]: # (subtitle: "Randomizing Over Randomized Experiments")
---

<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

### 📄 Abstract

Lay summaries for scientific documents typically include explanations to help readers grasp sophisticated concepts or arguments. However, current automatic summarization methods do not explicitly model explanations, which makes it difficult to align the proportion of explanatory content with human-written summaries. In this paper, we present a plan-based approach that leverages discourse frameworks to organize summary generation and guide explanatory sentences by prompting responses to the plan. Specifically, we propose two discourse-driven planning strategies, where the plan is conditioned as part of the input or part of the output prefix, respectively. Empirical experiments on three lay summarization datasets show that our approach outperforms existing state-of-the-art methods in terms of summary quality, and it enhances model robustness, controllability, and mitigates hallucination.

### 🔍 Method Overview

<div style="display: flex; justify-content: center;">
    <img src="../assets/publications/TACL2025/expsum_framework.png" alt="ExpSum Framework.png" style="max-width:100%; width:800px;">
</div>

### 💻 Code

Our code is publicly available on GitHub: [<img src="https://img.shields.io/badge/GitHub-ExpSum-blue?logo=github" alt="ExpSum GitHub Repository">](https://github.com/dongqi-me/ExpSum)

### 📚 Citation

<div class="citation-container" style="background-color: #f8f9fa; border-left: 4px solid #007bff; padding: 15px; border-radius: 4px; margin: 20px 0;">
<strong>Please cite our work if you find it useful:</strong>

{% highlight bibtex %}
@article{liu2025explanatory,
  title={Explanatory Summarization with Discourse-Driven Planning},
  author={Liu, Dongqi and Yu, Xi and Demberg, Vera and Lapata, Mirella},
  journal={arXiv preprint arXiv:2504.19339},
  year={2025}
}
{% endhighlight %}
</div>

<div style="text-align: center; margin-top: 30px;">
    <a href="https://tacl2023.org" target="_blank"><img src="https://img.shields.io/badge/TACL-2025-blue" alt="TACL 2025"></a>
    <a href="https://arxiv.org/abs/2504.19339" target="_blank"><img src="https://img.shields.io/badge/arXiv-2504.19339-b31b1b" alt="arXiv"></a>
    <a href="https://github.com/dongqi-me/ExpSum" target="_blank"><img src="https://img.shields.io/badge/Code-Available%20Soon-yellow" alt="Code"></a>
</div>
