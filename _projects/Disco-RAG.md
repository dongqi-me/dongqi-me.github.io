---
layout: project
title: "Disco-RAG: Discourse-Aware Retrieval-Augmented Generation"
[//]: # (subtitle: "Randomizing Over Randomized Experiments")
---

<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

### 📄 Abstract

Retrieval-Augmented Generation (RAG) has emerged as an important means of enhancing the performance of large language models (LLMs) in knowledge-intensive tasks. However, most existing RAG strategies treat retrieved passages in a flat and unstructured way, which prevents the model from capturing structural cues and constrains its ability to synthesize knowledge from dispersed evidence across documents. To overcome these limitations, we propose Disco-RAG, a discourse-aware framework that explicitly injects discourse signals into the generation process. Our method constructs intra-chunk discourse trees to capture local hierarchies and builds inter-chunk rhetorical graphs to model cross-passage coherence. These structures are jointly integrated into a planning blueprint that conditions the generation. Experiments on question answering and long-document summarization benchmarks show the efficacy of our approach. Disco-RAG achieves state-of-the-art results on the benchmarks without fine-tuning. These findings underscore the important role of discourse structure in advancing RAG systems.

### 🔍 Overview

<div style="display: flex; justify-content: center;">
    <img src="../assets/publications/ACL2026/DiscoRAG.jpg" alt="Disco-RAG" style="max-width:100%; width:800px;">
</div>

### 💻 Code

Our code is publicly available on GitHub: [<img src="https://img.shields.io/badge/GitHub-DiscoRAG-blue?logo=github" alt="Disco-RAG GitHub Repository">](https://github.com/dongqi-me/Disco-RAG)

可以，删掉 `abstract` 字段后的版本如下：

### 📚 Citation

<div style="position: relative; margin-bottom: 20px;">
  <pre id="citation-text-discorag" style="background-color: #f8f9fa; padding: 15px; border-radius: 4px; border-left: 4px solid #007bff; margin: 0; white-space: pre-wrap; overflow-x: auto; font-family: monospace; line-height: 1.5;">
<span style="color: #800000;">@inproceedings</span>{<span style="color: #000080;">liu-etal-2026-disco</span>,
  <span style="color: #008000;">title</span> = {<span style="color: #000080;">Disco-{RAG}: Discourse-Aware Retrieval-Augmented Generation</span>},
  <span style="color: #008000;">author</span> = {<span style="color: #000080;">Liu, Dongqi and Ding, Hang and Feng, Qiming and Xie, Xurong and Xue, Zhucun and Wang, Chengjie and Li, Jian and Zhang, Jiangning and Wang, Yabiao</span>},
  <span style="color: #008000;">editor</span> = {<span style="color: #000080;">Liakata, Maria and Moreira, Viviane P. and Zhang, Jiajun and Jurgens, David</span>},
  <span style="color: #008000;">booktitle</span> = {<span style="color: #000080;">Proceedings of the 64th Annual Meeting of the {A}ssociation for {C}omputational {L}inguistics (Volume 1: Long Papers)</span>},
  <span style="color: #008000;">month</span> = <span style="color: #000080;">jul</span>,
  <span style="color: #008000;">year</span> = {<span style="color: #000080;">2026</span>},
  <span style="color: #008000;">address</span> = {<span style="color: #000080;">San Diego, California, United States</span>},
  <span style="color: #008000;">publisher</span> = {<span style="color: #000080;">Association for Computational Linguistics</span>},
  <span style="color: #008000;">url</span> = {<span style="color: #000080;">https://aclanthology.org/2026.acl-long.189/</span>},
  <span style="color: #008000;">pages</span> = {<span style="color: #000080;">4106--4136</span>},
  <span style="color: #008000;">ISBN</span> = {<span style="color: #000080;">979-8-89176-390-6</span>}
}</pre>

  <button id="copy-button-discorag" onclick="copyBibTeXDiscoRAG()" style="position: absolute; top: 10px; right: 10px; background: #f6f8fa; color: #24292e; border: none; border-radius: 6px; padding: 6px 10px; cursor: pointer; font-size: 12px; display: flex; align-items: center; opacity: 0.6; transition: opacity 0.2s;">
    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" style="margin-right: 3px;">
      <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path>
      <path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
    </svg>
  </button>
</div>

<script>
function copyBibTeXDiscoRAG() {
  var textArea = document.createElement("textarea");
  textArea.value = document.getElementById("citation-text-discorag").textContent.trim();
  document.body.appendChild(textArea);
  textArea.select();

  try {
    var successful = document.execCommand("copy");
    var button = document.getElementById("copy-button-discorag");

    if (successful) {
      var originalContent = button.innerHTML;
      button.innerHTML = '<svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" style="margin-right: 3px;"><path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path></svg>';
      button.style.opacity = "1";

      setTimeout(function() {
        button.innerHTML = originalContent;
        button.style.opacity = "0.6";
      }, 2000);
    }
  } catch (err) {
    console.error("Unable to copy", err);
  }

  document.body.removeChild(textArea);
}
</script>

<div style="text-align: center; margin-top: 30px;">
  <a href="https://aclanthology.org/2026.acl-long.189/" target="_blank">
    <img src="https://img.shields.io/badge/ACL-2026-blue" alt="ACL 2026">
  </a>
  <a href="https://arxiv.org/abs/2601.04377" target="_blank">
    <img src="https://img.shields.io/badge/arXiv-2601.04377-b31b1b" alt="arXiv">
  </a>
  <a href="https://github.com/dongqi-me/Disco-RAG" target="_blank">
    <img src="https://img.shields.io/badge/Code-Available-green?logo=github" alt="Code">
  </a>
</div>
