---
title: TensorNetworks
summary: Applying TensorNetowrks to the problem of MultiAgent Reinforcement Learning

tags:
- ML
date: "2020-06-27T00:00:00Z"

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
url_pdf: "project/TensorNetowrks/report.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---
In this document all that is present are notes taken as the research progressed, the notes are
structures in order of progression and are unfiltered raw thoughts and steps. with no respect to
grammar.

We Begin by attempting to create a baseline, this is a simply CNN actor critic policy from stablebaselines 3 trained using the PPO algorithm. Once trained we transfer the parameters from pytorch to jax and buid a model, we change the policy network from a multilayerpreceptron to a TensorNetwork. (Currently progressing thus only the notes are available!)
