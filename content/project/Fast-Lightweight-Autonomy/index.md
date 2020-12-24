---
title: Fast Lightweight Autonomy
summary: Autonomous flight of fast and agile  MAVs.
tags:
#- System
date: "2020-12-19T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Beautiful photo by Dr. Yash Mulgaonkar
  focal_point: Smart

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

The project was funded by [DARPA (2015-2018)](https://www.darpa.mil/program/fast-lightweight-autonomy).
The goal was to understand the capability of MAVs in navigating unknown cluttered environments rapidly and autonomously using only onboard sensors (GPS-denied) and computation devices (cannot contact ground control for instructions).

Maybe the PIs explained the project better than I did.
[![FLA interview](https://img.youtube.com/vi/_UFabSMuz6w/hqdefault.jpg)](https://www.youtube.com/watch?v=_UFabSMuz6w)

UPenn (collaborated with OSRF and UZH) was one of the three teams. Below shows some video highlights of our group effort.

|     |     |
| --- | --- |
| [![Mohta ICRA2018](https://img.youtube.com/vi/6eeetSVHXPk/hqdefault.jpg)](https://www.youtube.com/watch?v=6eeetSVHXPk) | [![Watterson 2018](https://img.youtube.com/vi/nVbZjbm4i84/hqdefault.jpg)](https://www.youtube.com/watch?v=nVbZjbm4i84) |

Related publications:
[[Mohta, JFR2017]](https://arxiv.org/abs/1712.02052)
[[Mohta, ICRA2018]](https://arxiv.org/abs/1806.07053)
[[Quigley, ICRA2019]](https://arxiv.org/abs/1809.07674).

My major contribution in this project was the development of a stereo visual initial odometry, called S-MSCKF.
As the name suggests, S-MSCKF is an extension of MSCKF (originally proposed by Dr. Mourikis) to stereo cameras.
With stereo cameras, robustness of the odometry is improved (no longer need to wait for multiple frames to get the depth of a point feature).
S-MSCKF has been tested and proved to be reliable in various challenging scenarios, such as indoor-outdoor transition, feature-poverty scenes, fast motion (up to 18m/s).

[![Sun ICRA2018](https://img.youtube.com/vi/OXSB8Bze0cY/hqdefault.jpg)](https://www.youtube.com/watch?v=OXSB8Bze0cY)

Related publication:
[[Sun, ICRA2018]](https://arxiv.org/abs/1712.00036)
[[Code]](https://github.com/KumarRobotics/msckf_vio)
