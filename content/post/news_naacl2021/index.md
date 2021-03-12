---
title: Soft-labels, new paper at NAACL2021!
subtitle: > 

  Glad to announce that the paper 
  
  
  "Beyond Black & White: Leveraging Annotator Disagreement via Soft-Label Multi-Task Learning"
  
  
  with Alexandra Uma, [Silviu Paun](https://twitter.com/SilviuPaun), [Barbara Plank](https://twitter.com/barbara_plank), [Dirk Hovy](https://twitter.com/dirk_hovy) and [Massimo Poesio](https://twitter.com/poesio) has been accepted at [NAACL2021](https://2021.naacl.org/)!


# Summary for listings and search engines
summary: > 
  Beyond Black & White: Leveraging Annotator Disagreement via Soft-Label Multi-Task Learning
  

# Link this post with a project
projects: []

# Date published
date: "2016-04-20T00:00:00Z"

# Date updated
lastmod: "2021-03-12T00:00:00Z"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  # caption: Linguistic cues of deception with Sampling and Occlusion (SOC) algorithm (Jin et al., 2019)
  focal_point: Top
  placement: 2
  preview_only: false

#authors:
#- Tommaso Fornaciari
#- Dirk Hovy
#- Federico Bianchi
#- Massimo Poesio

#tags:
#- Deception detection
#- Deep contextual models
#- Language models

# categories:
# - aaa
# - bbb

links:
- icon: file
  icon_pack: fas
  name: Download the accepted version here!
  url: media/naacl2021softlabels.pdf

#url_pdf:

---

## Overview

Supervised learning assumes that a ground truth label exists. 

However, the reliability of this ground truth depends on human annotators, who often disagree. 

Prior work has shown that this disagreement can be helpful in training models.

We propose a novel method to incorporate this disagreement as information: in addition to the standard error computation, we use soft-labels (i.e., probability distributions over the annotator labels) as an auxiliary task in a multi-task neural network.

We measure the divergence between the predictions and the target soft-labels with several loss-functions and evaluate the models on various NLP tasks.

We find that the soft-label prediction auxiliary task reduces the penalty for errors on ambiguous entities, and thereby mitigates overfitting. It significantly improves performance across tasks, beyond the standard approach and prior work.
