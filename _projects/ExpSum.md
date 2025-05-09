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

<div style="position: relative; margin-bottom: 20px;">
  <pre id="citation-text-expsum" style="background-color: #f8f9fa; padding: 15px; border-radius: 4px; border-left: 4px solid #007bff; margin: 0; white-space: pre-wrap; overflow-x: auto; font-family: monospace; line-height: 1.5;">
<span style="color: #800000;">@article</span>{<span style="color: #000080;">liu2025explanatory</span>,
  <span style="color: #008000;">title</span>={<span style="color: #000080;">Explanatory Summarization with Discourse-Driven Planning</span>},
  <span style="color: #008000;">author</span>={<span style="color: #000080;">Liu, Dongqi and Yu, Xi and Demberg, Vera and Lapata, Mirella</span>},
  <span style="color: #008000;">journal</span>={<span style="color: #000080;">arXiv preprint arXiv:2504.19339</span>},
  <span style="color: #008000;">year</span>={<span style="color: #000080;">2025</span>}
}</pre>
  <button onclick="copyBibTeXExpSum()" style="position: absolute; top: 10px; right: 10px; background: #f6f8fa; color: #24292e; border: none; border-radius: 6px; padding: 6px 10px; cursor: pointer; font-size: 12px; display: flex; align-items: center; opacity: 0.6; transition: opacity 0.2s;">
    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" style="margin-right: 3px;">
      <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path>
      <path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
    </svg>
  </button>
</div>

<script>
function copyBibTeXExpSum() {
  var textArea = document.createElement("textarea");
  textArea.value = document.getElementById("citation-text-expsum").textContent.trim();
  document.body.appendChild(textArea);
  textArea.select();
  
  try {
    var successful = document.execCommand('copy');
    var button = document.querySelector('button');
    if (successful) {
      var originalContent = button.innerHTML;
      button.innerHTML = '<svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" style="margin-right: 3px;"><path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path></svg>';
      button.style.opacity = '1';
      setTimeout(function() {
        button.innerHTML = originalContent;
        button.style.opacity = '0.6';
      }, 2000);
    }
  } catch (err) {
    console.error('Unable to copy', err);
  }
  
  document.body.removeChild(textArea);
}
</script>

<div style="text-align: center; margin-top: 30px;">
    <a href="https://tacl2023.org" target="_blank"><img src="https://img.shields.io/badge/TACL-2025-blue" alt="TACL 2025"></a>
    <a href="https://arxiv.org/abs/2504.19339" target="_blank"><img src="https://img.shields.io/badge/arXiv-2504.19339-b31b1b" alt="arXiv"></a>
    <a href="https://github.com/dongqi-me/ExpSum" target="_blank"><img src="https://img.shields.io/badge/Code-Available%20Soon-yellow" alt="Code"></a>
</div>
