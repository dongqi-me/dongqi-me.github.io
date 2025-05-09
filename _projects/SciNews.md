---
layout: project
title: "SciNews: From Scholarly Complexities to Public Narratives -- A Dataset for Scientific News Report Generation"

[//]: # (subtitle: "Randomizing Over Randomized Experiments")
---

<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

## 📄 Project Overview

The SciNews dataset is designed to facilitate the development and evaluation of models that generate scientific news reports from scholarly articles. This dataset aims to bridge the gap between complex scientific research and the general public by simplifying and summarizing academic content into accessible narratives. It supports tasks like text summarization, simplification, and the automated generation of scientific news, providing a valuable resource for enhancing public engagement with science and technology.

<div style="display: flex; justify-content: center;">
    <img src="../assets/publications/COLING2024/SciNews.png" alt="SciNews" style="max-width:100%; width:800px;">
</div>

## 📊 Dataset Details

### 📋 Dataset Description

- **Curated by:** Dongqi Liu, Yifan Wang, Jia Loy, Vera Demberg from the (1). Department of Computer Science and (2). Department of Language Science and Technology at Saarland Informatics Campus, Saarland University, Germany.
- **Funded by:** This project has received funding from the European Research Council (ERC) under the European Union's Horizon 2020 Research and Innovation Programme (Grant Agreement No. 948878).
- **Language(s) (NLP):** English

### 🔗 Dataset Sources

- **Repository:** Dataset is available at: [<img src="https://img.shields.io/badge/HuggingFace-SciNews-yellow?logo=huggingface" alt="SciNews HuggingFace Dataset">](https://huggingface.co/datasets/dongqi-me/SciNews)
- **Paper:** The details about the dataset can be found in the paper "[SciNews: From Scholarly Complexities to Liublic Narratives – A Dataset for Scientific News Report Generation](https://aclanthology.org/2024.lrec-main.1258/)" by Dongqi Liu, Yifan Wang, Jia Loy, Vera Demberg.

## 🔍 Dataset Creation

### 📥 Data Collection and Processing

Data was collected from the Science X platform, an open-access hub for science, technology, and medical research news. Data extraction was performed using web scraping tools like Selenium and BeautifulSoup.

### 🏷️ Annotations

The dataset does not include additional annotations as it is a compilation of existing scientific papers and their corresponding news reports. The quality control included automated and human assessments to ensure the relevance and quality of the news narratives in relation to the original scientific papers.

### 💡 Recommendations

Users of the SciNews dataset should be aware of its limitations and biases, particularly when developing models for scientific news generation. Efforts should be made to address potential biases and ensure that generated narratives accurately and fairly represent the original scientific content.

## 📚 Citation

<div style="position: relative; margin-bottom: 20px;">
  <pre id="citation-text-scinews" style="background-color: #f8f9fa; padding: 15px; border-radius: 4px; border-left: 4px solid #007bff; margin: 0; white-space: pre-wrap; overflow-x: auto; font-family: monospace; line-height: 1.5;">
<span style="color: #800000;">@inproceedings</span>{<span style="color: #000080;">pu-etal-2024-scinews-scholarly</span>,
    <span style="color: #008000;">title</span> = "<span style="color: #000080;">{S}ci{N}ews: From Scholarly Complexities to Public Narratives {--} a Dataset for Scientific News Report Generation</span>",
    <span style="color: #008000;">author</span> = "<span style="color: #000080;">Liu, Dongqi  and
      Wang, Yifan  and
      Loy, Jia E.  and
      Demberg, Vera</span>",
    <span style="color: #008000;">editor</span> = "<span style="color: #000080;">Calzolari, Nicoletta  and
      Kan, Min-Yen  and
      Hoste, Veronique  and
      Lenci, Alessandro  and
      Sakti, Sakriani  and
      Xue, Nianwen</span>",
    <span style="color: #008000;">booktitle</span> = "<span style="color: #000080;">Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024)</span>",
    <span style="color: #008000;">month</span> = <span style="color: #000080;">may</span>,
    <span style="color: #008000;">year</span> = "<span style="color: #000080;">2024</span>",
    <span style="color: #008000;">address</span> = "<span style="color: #000080;">Torino, Italy</span>",
    <span style="color: #008000;">publisher</span> = "<span style="color: #000080;">ELRA and ICCL</span>",
    <span style="color: #008000;">url</span> = "<span style="color: #000080;">https://aclanthology.org/2024.lrec-main.1258</span>",
    <span style="color: #008000;">pages</span> = "<span style="color: #000080;">14429--14444</span>",
}</pre>
  <button onclick="copyBibTeXSciNews()" style="position: absolute; top: 10px; right: 10px; background: #007bff; color: white; border: none; border-radius: 4px; padding: 5px 10px; cursor: pointer; font-size: 14px;">
    Copy
  </button>
</div>

<script>
function copyBibTeXSciNews() {
  var textArea = document.createElement("textarea");
  textArea.value = document.getElementById("citation-text-scinews").textContent.trim();
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
    <a href="https://aclanthology.org/2024.lrec-main.1258" target="_blank"><img src="https://img.shields.io/badge/LREC--COLING-2024-blue" alt="LREC-COLING 2024"></a>
    <a href="https://huggingface.co/datasets/dongqi-me/SciNews" target="_blank"><img src="https://img.shields.io/badge/Dataset-HuggingFace-yellow?logo=huggingface" alt="Dataset"></a>
</div>

## 📬 Contact

For further inquiries or questions regarding the SciNews dataset, please contact: <a href="mailto:dongqi.me@gmail.com"><img src="https://img.shields.io/badge/Email-dongqi.me%40gmail.com-red?logo=gmail" alt="Email Contact"></a>

