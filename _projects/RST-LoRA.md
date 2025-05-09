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

<div style="position: relative; margin-bottom: 20px;">
  <pre id="citation-text-rstlora" style="background-color: #f8f9fa; padding: 15px; border-radius: 4px; border-left: 4px solid #007bff; margin: 0; white-space: pre-wrap; overflow-x: auto; font-family: monospace; line-height: 1.5;">
<span style="color: #800000;">@inproceedings</span>{<span style="color: #000080;">pu-demberg-2024-rst</span>,
    <span style="color: #008000;">title</span> = "<span style="color: #000080;">{RST}-{L}o{RA}: A Discourse-Aware Low-Rank Adaptation for Long Document Abstractive Summarization</span>",
    <span style="color: #008000;">author</span> = "<span style="color: #000080;">Liu, Dongqi  and
      Demberg, Vera</span>",
    <span style="color: #008000;">editor</span> = "<span style="color: #000080;">Duh, Kevin  and
      Gomez, Helena  and
      Bethard, Steven</span>",
    <span style="color: #008000;">booktitle</span> = "<span style="color: #000080;">Proceedings of the 2024 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies (Volume 1: Long Papers)</span>",
    <span style="color: #008000;">month</span> = <span style="color: #000080;">jun</span>,
    <span style="color: #008000;">year</span> = "<span style="color: #000080;">2024</span>",
    <span style="color: #008000;">address</span> = "<span style="color: #000080;">Mexico City, Mexico</span>",
    <span style="color: #008000;">publisher</span> = "<span style="color: #000080;">Association for Computational Linguistics</span>",
    <span style="color: #008000;">url</span> = "<span style="color: #000080;">https://aclanthology.org/2024.naacl-long.121</span>",
    <span style="color: #008000;">doi</span> = "<span style="color: #000080;">10.18653/v1/2024.naacl-long.121</span>",
    <span style="color: #008000;">pages</span> = "<span style="color: #000080;">2200--2220</span>",
}</pre>
  <button onclick="copyBibTeXRSTLoRA()" style="position: absolute; top: 10px; right: 10px; background: #f8f9fa; color: #007bff; border: 1px solid #007bff; border-radius: 4px; padding: 5px 10px; cursor: pointer; font-size: 13px; display: flex; align-items: center; transition: all 0.2s ease;">
    <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="margin-right: 5px;">
      <rect x="9" y="9" width="13" height="13" rx="2" ry="2"></rect>
      <path d="M5 15H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v1"></path>
    </svg>
    Copy
  </button>
</div>

<script>
function copyBibTeXRSTLoRA() {
  var textArea = document.createElement("textarea");
  textArea.value = document.getElementById("citation-text-rstlora").textContent.trim();
  document.body.appendChild(textArea);
  textArea.select();
  
  try {
    var successful = document.execCommand('copy');
    var button = document.querySelector('button');
    if (successful) {
      button.innerHTML = '<svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="margin-right: 5px;"><polyline points="20 6 9 17 4 12"></polyline></svg>Copied!';
      button.style.background = '#e8f4ff';
      setTimeout(function() {
        button.innerHTML = '<svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="margin-right: 5px;"><rect x="9" y="9" width="13" height="13" rx="2" ry="2"></rect><path d="M5 15H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v1"></path></svg>Copy';
        button.style.background = '#f8f9fa';
      }, 2000);
    }
  } catch (err) {
    console.error('Unable to copy', err);
  }
  
  document.body.removeChild(textArea);
}
</script>

<div style="text-align: center; margin-top: 30px;">
    <a href="https://aclanthology.org/2024.naacl-long.121" target="_blank"><img src="https://img.shields.io/badge/NAACL-2024-blue" alt="NAACL 2024"></a>
    <a href="https://doi.org/10.18653/v1/2024.naacl-long.121" target="_blank"><img src="https://img.shields.io/badge/DOI-10.18653%2Fv1%2F2024.naacl--long.121-orange" alt="DOI"></a>
    <a href="https://github.com/dongqi-me/RST_LoRA" target="_blank"><img src="https://img.shields.io/badge/Code-Available-green?logo=github" alt="Code"></a>
</div>
