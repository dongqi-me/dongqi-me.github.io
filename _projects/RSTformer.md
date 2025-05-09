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

<div style="position: relative; margin-bottom: 20px;">
  <pre id="citation-text-rstformer" style="background-color: #f8f9fa; padding: 15px; border-radius: 4px; border-left: 4px solid #007bff; margin: 0; white-space: pre-wrap; overflow-x: auto; font-family: monospace; line-height: 1.5;">
<span style="color: #800000;">@inproceedings</span>{<span style="color: #000080;">pu-etal-2023-incorporating</span>,
    <span style="color: #008000;">title</span> = "<span style="color: #000080;">Incorporating Distributions of Discourse Structure for Long Document Abstractive Summarization</span>",
    <span style="color: #008000;">author</span> = "<span style="color: #000080;">Liu, Dongqi  and
      Wang, Yifan  and
      Demberg, Vera</span>",
    <span style="color: #008000;">editor</span> = "<span style="color: #000080;">Rogers, Anna  and
      Boyd-Graber, Jordan  and
      Okazaki, Naoaki</span>",
    <span style="color: #008000;">booktitle</span> = "<span style="color: #000080;">Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)</span>",
    <span style="color: #008000;">month</span> = <span style="color: #000080;">jul</span>,
    <span style="color: #008000;">year</span> = "<span style="color: #000080;">2023</span>",
    <span style="color: #008000;">address</span> = "<span style="color: #000080;">Toronto, Canada</span>",
    <span style="color: #008000;">publisher</span> = "<span style="color: #000080;">Association for Computational Linguistics</span>",
    <span style="color: #008000;">url</span> = "<span style="color: #000080;">https://aclanthology.org/2023.acl-long.306</span>",
    <span style="color: #008000;">doi</span> = "<span style="color: #000080;">10.18653/v1/2023.acl-long.306</span>",
    <span style="color: #008000;">pages</span> = "<span style="color: #000080;">5574--5590</span>",
}</pre>
  <button onclick="copyBibTeXRSTformer()" style="position: absolute; top: 10px; right: 10px; background: #007bff; color: white; border: none; border-radius: 4px; padding: 5px 10px; cursor: pointer; font-size: 14px;">
    Copy
  </button>
</div>

<script>
function copyBibTeXRSTformer() {
  var textArea = document.createElement("textarea");
  textArea.value = document.getElementById("citation-text-rstformer").textContent.trim();
  document.body.appendChild(textArea);
  textArea.select();
  
  try {
    var successful = document.execCommand('copy');
    var button = document.querySelector('button');
    if (successful) {
      button.textContent = 'Copied!';
      setTimeout(function() {
        button.textContent = 'Copy';
      }, 2000);
    }
  } catch (err) {
    console.error('Unable to copy', err);
  }
  
  document.body.removeChild(textArea);
}
</script>

<div style="text-align: center; margin-top: 30px;">
    <a href="https://aclanthology.org/2023.acl-long.306" target="_blank"><img src="https://img.shields.io/badge/ACL-2023-blue" alt="ACL 2023"></a>
    <a href="https://doi.org/10.18653/v1/2023.acl-long.306" target="_blank"><img src="https://img.shields.io/badge/DOI-10.18653%2Fv1%2F2023.acl--long.306-orange" alt="DOI"></a>
    <a href="https://github.com/dongqi-me/RSTformer" target="_blank"><img src="https://img.shields.io/badge/Code-Available-green?logo=github" alt="Code"></a>
</div>
