---
title: Election pledges, new paper at Findings of ACL2021!
subtitle: > 

  Glad to announce that the paper 
  
  
  "We will Reduce Taxes \- Identifying Election Pledges with Language Models"
  
  
  with [Dirk Hovy](https://twitter.com/dirk_hovy), [Elin Naurin](https://twitter.com/@elinnaurin), [Julia Runeson](https://twitter.com/@juliarune), Robert Thomson and Pankaj Adhikari has been accepted at [Findings of ACL2021](https://2021.naacl.org/)!


# Summary for listings and search engines
summary: > 
  We will Reduce Taxes \- Identifying Election Pledges with Language Models
  

# Link this post with a project
projects: []

# Date published
date: "2016-04-20T00:00:00Z"

# Date updated
lastmod: "2021-05-6T00:00:00Z"

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
#- Elin Naurin
#- Julia Runeson
#- Robert Thomson
#- Pankaj Adhikari

#tags:
#- Election pledges
#- Zero-Shot Learning
#- Language models

# categories:
# - aaa
# - bbb

links:
- icon: file
  icon_pack: fas
  name: Download the accepted version here!
  url: media/2021-aclfindings-mimac.pdf

#url_pdf:

---

## Overview

In an election campaign, political parties pledge to implement various projects--should they be elected. But do they follow through? 

To track election pledges from parties' election manifestos, we need to distinguish between pledges and general statements.

In this paper, we use election manifestos of Swedish and Indian political parties to learn neural models that distinguish actual pledges from generic political positions. 

Since pledges might vary by election year and party, we implement a Multi-Task Learning (MTL) setup, predicting election year and manifesto's party as auxiliary tasks.

Pledges can also span several sentences, so we use hierarchical models that incorporate contextual information.

Lastly, we evaluate the models in a Zero-Shot Learning (ZSL) framework across countries and languages.

Our results indicate that year and party have predictive power even in ZSL, while context introduces some noise. 

We finally discuss the linguistic features of pledges.
