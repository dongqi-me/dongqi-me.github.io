---
layout: project
title: Incorporating Distributions of Discourse Structure for Long Document Abstractive Summarization

[//]: # (subtitle: "Randomizing Over Randomized Experiments")
---

<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

####  Abstract: 
For text summarization, the role of discourse structure is pivotal in discerning the core content of a text. Regrettably, prior studies on incorporating Rhetorical Structure Theory (RST) into transformer-based summarization models only consider the nuclearity annotation, thereby overlooking the variety of discourse relation types. This paper introduces the `RSTformer', a novel summarization model that comprehensively incorporates both the types and uncertainty of rhetorical relations.  Our RST-attention mechanism, rooted in document-level rhetorical structure, is an extension of the recently devised Longformer framework. Through rigorous evaluation, the model proposed herein exhibits significant superiority over state-of-the-art models, as evidenced by its notable performance on several automatic metrics and human evaluation.

<div style="display: flex; justify-content: center;">
    <img src="../assets/publications/ACL2023/RSTformer.png" alt="RSTformer" style="max-width:100%;">
</div>


#### Code:

Code is available at: https://github.com/dongqi-me/RSTformer

#### Citation:

**BibTeX:**

```bibtex
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
```
