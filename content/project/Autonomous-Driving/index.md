---
title: Autonomous Driving
summary: Using DeepLearning methods in Jax and Tensorflow to teach a model to drive a car.

tags:
- ML
date: "2020-04-27T00:00:00Z"

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
url_code: "https://github.com/Mo379/Auto_driving"
url_pdf: "project/Autonomous-Driving/report.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---
In this work we investigate the performance of different deep learning methods in the task of
self driving, aided by regularising methods and synthetic data augmentation. We obtain results
for models/methods including vanilla Multi layer preceptors, vanilla Convolutional neural networks
as well as results using Transfer Learning with MobileNetV3Small and EfficentNetV2 B0 and B1,
with performances ranking in the respective order from worse to best. We obtain a best performing
theoretical model using the EfficentNetV2B0 model, obtaining a Kaggle MSE score of 0.01161. Fur-
thermore on the practical testing, we used the MobvileNetV3Small and obtained a poorly performing
model, only scoring 9/35 points in the live testing.
