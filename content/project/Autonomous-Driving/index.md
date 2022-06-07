---
title: Electromagnetic propulsion
summary: Leveraging electromagnetic propulsion with the goal of creating a simple projectile launching system.

tags:
- Physics
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
url_pdf: "project/Electromagnetic-propulsion/report.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---
In this experiment, an electromagnetic propulsion system was built, with the aim to make it as reliable as possible at launching a projectile.The system consists of two solenoids and two sensors connected to an Arduino [1], the objective is to successfully accelerate the projectile through both of these solenoids without having the projectile get stuck in the middle of at the equilibrium point, therefore the purpose of the sensors is to control the flow of current, this system was tested and a success rate of 40%, 60% rate and finally 100% were achieved when all the sources of failures were formally addressed. Furthermore the experiment also looked at using a calibrated timing method, where instead of the sensors controlling the flow of current to the solenoids it was all hard coded into the python code, the optimum activation period for this design (length of each part considered) was found using trial and error, these periods were 150 milliseconds (period of the activation of the magnetic fields) from the solenoid nearest to the projectile, and 350millisecond from the other solenoid, allowing the projectile to travel from the stationary point, into the solenoid and then turns off before the projectile gets stuck in the equilibrium point (both periods start when the first signal is triggered), aside from determining the optimum times, the success rate of this method is 100%.

This experiment was carried out with the goal of making a simple electromagnetic propulsion system that’s reliable, and this was successfully achieved.
