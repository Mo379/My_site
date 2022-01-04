---
title: Structural analysis of proteins
summary: An initial investigation into current and potential geometrical representations of proteins
tags:
- StructBio
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: ""/Users/M/Downloads/Rutherford-scattering/index.md
  focal_point: Smart

links:
#- icon: twitter
#  icon_pack: fab/Users/M/Downloads/Rutherford-scattering/index.md
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: "project/Structural-analysis-or-proteins/report.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---
With the goal to create a database of representations of proteins, and a further aim to help solve the protein function problem, this investigation focuses on obtaining primary protein representations derived from the protein’s 3D dimensional structure. Those representations are the 3D structure (as a base), Distogram and the Convexhull of the protein. The python classes and functions created can then be extended to include more complex protein representations, that may be used in machine learning systems, which aim at predicting a protein’s function. Currently only the Distogram can be used as input for a successful machine learning model (convolutional neural networks), other representations such as the convex hull may need more transformative steps before they can be used as inputs. Plots produced by the code are displayed inside of figures, this is to showcase the output of the code accompanying this article. Finally, no significant data generating processes have been carried out in this investigation,this is due to lack of relevance at this step and storage reasons, it is however possible to start but it wont be of any immediate significance.
