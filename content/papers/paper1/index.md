---
title: "Weakly-Supervised Semantic Segmentation via Transformer Explainability" 
date: 2022-05-23
tags: ["machine learning","deep learning","semantic segmentation", "computer vision"]
author: "Ioannis Athanasiadis, Georgios Moschovis, Alexander Tuoma"
description: "We combine classic back-propagation recipe through the chain rule with relevance
propagation, another technique that is based on Deep Taylor Decomposition, to perform weakly supervised semantic segmentation. Published in ReScience Journal, 2021." 
summary: "This paper shows things using various techniques and data." 
cover:
    image: "TransformerInterpretability.png"
    alt: "Indicative selection of qualitative results."
    relative: false
editPost:
    URL: "https://doi.org/10.5281/zenodo.6574631"
    Text: "ReScience Journal"

---

---

##### Download

+ [Paper](paper1.pdf)
+ [Online appendix](appendix1.pdf)
+ [Code and data](https://github.com/pmichaillat/job-rationing)

---

##### Abstract

Transformers have been an object of extensive research among deep generative
models during the last few years. Precisely, they became a state-of-the-art model
for Natural Language Processing (NLP) tasks in 2017 and adopted the mechanism
of attention, weighing the influence of different parts of the input data. In this
project, we address the use of transformers in a different domain, computer vision,
to perform weakly supervised semantic segmentation. Towards this goal, we
combine classic back-propagation recipe through the chain rule with relevance
propagation, another technique that is based on Deep Taylor Decomposition, to
achieve significant performance, comparable to state-of-the-art CNN architectures,
using transformers. Last but not least, we incorporate the concept of pixel affinities,
which further improves performance in terms of Intersection over Union (IoU). All
code used for our experiments is available on GitHub.

---

##### Figure: Indicative selection of qualitative results.

![](TransformerInterpretability.png)

---

##### Citation

I. Athanasiadis, G. Moschovis, A. Tuoma, Weakly-Supervised Semantic Segmentation via
Transformer Explainability, in: ML Reproducibility Challenge 2021 (Fall Edition), 2022. https://doi.org/10.5281/zenodo.6574631.

```BibTeX
@inproceedings{Athanasiadis:interpretability,
title={{Weakly-Supervised Semantic Segmentation via Transformer Explainability}},
author={Ioannis Athanasiadis and Georgios Moschovis and Alexander Tuoma},
booktitle={ML Reproducibility Challenge 2021 (Fall Edition)},
year={2022},
}
```
