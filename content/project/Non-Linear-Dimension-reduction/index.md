---
title: Non-linear dimension reduction
summary: A group investigation into the effectiveness of Non-linear dimension reduction methods for manifold based datasets.
tags:
- ML
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: ""
  focal_point: Smart

links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: "project/Non-Linear-Dimension-reduction/report.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---
With the increasing size and dimensionality of data, the interpretation and insight into said data becomes hard to extract. In this investigation, we look at two non-linear di- mensionality reduction methods; Laplacian Eigenmaps and Locally Linear Embeddings (LLE). We look at the intuition, mathematical formulation and effectiveness of these methods. We then apply those methods to data sampled from non-linear manifolds, and observe their resultant embedding to gain insight into how the methods behave and their effectiveness at reducing the dimensionality of the data.

We find that for some datasets LLE performs better while for others not so well, and similarly for Laplacian Eigenmaps. The datasets that we used showed that LLE was better at mapping the points to distinct values whereas, for many different choices of t, Laplacian Eigenmaps gave plots where many points overlapped. This potentially speaks to the sensitivity of the first method to the choice and proximity of neighbouring points and how it is better at preserving variation in the data. However, Laplacian Eigenmaps was able to capture an added feature of the data in that some completely distinct sections of the data were close in the 3D space.
