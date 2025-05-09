---
layout: project
title: Incorporating Distributions of Discourse Structure for Long Document Abstractive Summarization

[//]: # (subtitle: "Randomizing Over Randomized Experiments")
---

<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

### 📄 Abstract

For text summarization, the role of discourse structure is pivotal in discerning the core content of a text. Regrettably, prior studies on incorporating Rhetorical Structure Theory (RST) into transformer-based summarization models only consider the nuclearity annotation, thereby overlooking the variety of discourse relation types. This paper introduces the `RSTformer', a novel summarization model that comprehensively incorporates both the types and uncertainty of rhetorical relations. Our RST-attention mechanism, rooted in document-level rhetorical structure, is an extension of the recently devised Longformer framework. Through rigorous evaluation, the model proposed herein exhibits significant superiority over state-of-the-art models, as evidenced by its notable performance on several automatic metrics and human evaluation.

### 🔍 Method Overview

<div style="display: flex; justify-content: center;">
    <img src="../assets/publications/ACL2023/RSTformer.png" alt="RSTformer" style="max-width:100%; width:800px;">
</div>

### 💻 Code

Our code is publicly available on GitHub: [<img src="https://img.shields.io/badge/GitHub-RSTformer-blue?logo=github" alt="RSTformer GitHub Repository">](https://github.com/dongqi-me/RSTformer)

### 📚 Citation

<div class="citation-container" style="background-color: #f8f9fa; border-left: 4px solid #007bff; padding: 15px; border-radius: 4px; margin: 20px 0; position: relative;">
<strong>Please cite our work if you find it useful:</strong>
<button onclick="copyToClipboard('rstformer-citation')" style="position: absolute; top: 10px; right: 10px; background: #007bff; color: white; border: none; border-radius: 4px; padding: 5px 10px; cursor: pointer;">Copy</button>

<pre id="rstformer-citation" style="background-color: #f5f5f5; padding: 10px; overflow-x: auto; margin-top: 10px;">
@inproceedings{pu-etal-2023-incorporating,
    title = "Incorporating Distributions of Discourse Structure for Long Document Abstractive Summarization",
    author = "Liu, Dongqi  and
      Wang, Yifan  and
      Demberg, Vera",
    editor = "Rogers, Anna  and
      Boyd-Graber, Jordan  and
      Okazaki, Naoaki",
    booktitle = "Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)",
    month = jul,
    year = "2023",
    address = "Toronto, Canada",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.acl-long.306",
    doi = "10.18653/v1/2023.acl-long.306",
    pages = "5574--5590",
}
</pre>
</div>

<script>
function copyToClipboard(elementId) {
  var text = document.getElementById(elementId).textContent;
  navigator.clipboard.writeText(text).then(function() {
    var button = event.target;
    var originalText = button.textContent;
    button.textContent = 'Copied!';
    setTimeout(function() {
      button.textContent = originalText;
    }, 2000);
  });
}
</script>

<div style="text-align: center; margin-top: 30px;">
    <a href="https://aclanthology.org/2023.acl-long.306" target="_blank"><img src="https://img.shields.io/badge/ACL-2023-blue" alt="ACL 2023"></a>
    <a href="https://doi.org/10.18653/v1/2023.acl-long.306" target="_blank"><img src="https://img.shields.io/badge/DOI-10.18653%2Fv1%2F2023.acl--long.306-orange" alt="DOI"></a>
    <a href="https://github.com/dongqi-me/RSTformer" target="_blank"><img src="https://img.shields.io/badge/Code-Available-green?logo=github" alt="Code"></a>
</div>
