---
layout: project
title: ChatGPT vs Human-authored Text&#58; Insights into Controllable Text Summarization and Sentence Style Transfer

[//]: # (subtitle: "Randomizing Over Randomized Experiments")
---

<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

### 📄 Abstract

Large-scale language models, like ChatGPT, have garnered significant media attention and stunned the public with their remarkable capacity for generating coherent text from short natural language prompts. In this paper, we aim to conduct a systematic inspection of ChatGPT's performance in two controllable generation tasks, with respect to ChatGPT's ability to adapt its output to different target audiences (expert vs. layman) and writing style (formal vs. informal). Additionally, we evaluate the faithfulness of the generated text, and compare the model's performance with human-authored texts. Our findings indicate that the stylistic variations produced by humans are considerably larger than those demonstrated by ChatGPT, and the generated texts diverge from human samples in several characteristics, such as the distribution of word types. Moreover, we observe that ChatGPT sometimes incorporates factual errors or hallucinations when adapting the text to suit a specific style.

### 🔍 Overview

<div style="display: flex; justify-content: center;">
    <img src="../assets/publications/ACL2023/ChatGPT_vs_Human.png" alt="ChatGPT_vs_Human" style="max-width:100%; width:800px;">
</div>

### 📚 Citation

<div style="position: relative; margin-bottom: 20px;">
  <pre id="citation-text-chatgpt" style="background-color: #f8f9fa; padding: 15px; border-radius: 4px; border-left: 4px solid #007bff; margin: 0; white-space: pre-wrap; overflow-x: auto; font-family: monospace; line-height: 1.5;">
<span style="color: #800000;">@inproceedings</span>{<span style="color: #000080;">pu-demberg-2023-chatgpt</span>,
    <span style="color: #008000;">title</span> = "<span style="color: #000080;">{C}hat{GPT} vs Human-authored Text: Insights into Controllable Text Summarization and Sentence Style Transfer</span>",
    <span style="color: #008000;">author</span> = "<span style="color: #000080;">Liu, Dongqi  and
      Demberg, Vera</span>",
    <span style="color: #008000;">editor</span> = "<span style="color: #000080;">Padmakumar, Vishakh  and
      Vallejo, Gisela  and
      Fu, Yao</span>",
    <span style="color: #008000;">booktitle</span> = "<span style="color: #000080;">Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 4: Student Research Workshop)</span>",
    <span style="color: #008000;">month</span> = <span style="color: #000080;">jul</span>,
    <span style="color: #008000;">year</span> = "<span style="color: #000080;">2023</span>",
    <span style="color: #008000;">address</span> = "<span style="color: #000080;">Toronto, Canada</span>",
    <span style="color: #008000;">publisher</span> = "<span style="color: #000080;">Association for Computational Linguistics</span>",
    <span style="color: #008000;">url</span> = "<span style="color: #000080;">https://aclanthology.org/2023.acl-srw.1</span>",
    <span style="color: #008000;">doi</span> = "<span style="color: #000080;">10.18653/v1/2023.acl-srw.1</span>",
    <span style="color: #008000;">pages</span> = "<span style="color: #000080;">1--18</span>",
}</pre>
  <button onclick="copyBibTeXChatGPT()" style="position: absolute; top: 10px; right: 10px; background: #f6f8fa; color: #24292e; border: none; border-radius: 6px; padding: 6px 10px; cursor: pointer; font-size: 12px; display: flex; align-items: center; opacity: 0.6; transition: opacity 0.2s;">
    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" style="margin-right: 3px;">
      <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path>
      <path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
    </svg>
  </button>
</div>

<script>
function copyBibTeXChatGPT() {
  var textArea = document.createElement("textarea");
  textArea.value = document.getElementById("citation-text-chatgpt").textContent.trim();
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
    <a href="https://aclanthology.org/2023.acl-srw.1" target="_blank"><img src="https://img.shields.io/badge/ACL-2023-blue" alt="ACL 2023"></a>
    <a href="https://doi.org/10.18653/v1/2023.acl-srw.1" target="_blank"><img src="https://img.shields.io/badge/DOI-10.18653%2Fv1%2F2023.acl--srw.1-orange" alt="DOI"></a>
</div>
