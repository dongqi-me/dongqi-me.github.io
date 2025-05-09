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

<div style="display: flex; align-items: flex-start; margin-bottom: 20px;">
  <div style="flex-grow: 1;">
    <pre id="citation-text-chatgpt" style="background-color: #f8f9fa; padding: 15px; border-radius: 4px; border-left: 4px solid #007bff; margin: 0; white-space: pre-wrap; word-break: keep-all; overflow-x: auto; color: #24292e;">
@inproceedings{pu-demberg-2023-chatgpt,
    title = "{C}hat{GPT} vs Human-authored Text: Insights into Controllable Text Summarization and Sentence Style Transfer",
    author = "Liu, Dongqi  and
      Demberg, Vera",
    editor = "Padmakumar, Vishakh  and
      Vallejo, Gisela  and
      Fu, Yao",
    booktitle = "Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 4: Student Research Workshop)",
    month = jul,
    year = "2023",
    address = "Toronto, Canada",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.acl-srw.1",
    doi = "10.18653/v1/2023.acl-srw.1",
    pages = "1--18",
}</pre>
  </div>
  <button onclick="copyBibTeXChatGPT()" style="margin-left: 10px; height: 36px; padding: 0 10px; background-color: #007bff; color: white; border: none; border-radius: 4px; cursor: pointer; flex-shrink: 0; align-self: flex-start; margin-top: 15px;">
    Copy
  </button>
</div>

<script>
function copyBibTeXChatGPT() {
  // 创建一个临时textarea元素
  var textArea = document.createElement("textarea");
  textArea.value = document.getElementById("citation-text-chatgpt").textContent.trim();
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
    <a href="https://aclanthology.org/2023.acl-srw.1" target="_blank"><img src="https://img.shields.io/badge/ACL-2023-blue" alt="ACL 2023"></a>
    <a href="https://doi.org/10.18653/v1/2023.acl-srw.1" target="_blank"><img src="https://img.shields.io/badge/DOI-10.18653%2Fv1%2F2023.acl--srw.1-orange" alt="DOI"></a>
</div>
