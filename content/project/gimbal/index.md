---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "1-DOF Gimbal"
subtitle: ""
summary: " "
authors: []
tags: [Control]
categories: []
date: 2019-11-20T08:11:38+02:00
lastmod: 2019-11-20T08:11:38+02:00
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Smart"
  preview_only: false

url_pdf: 
url_code:
url_dataset: 
url_poster:
url_project:
url_slides:
url_source:
url_video: https://youtu.be/L0cBFk25gZE

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
publication: []
---
Final project of the mechatronic course I took at the American University of Beirut.

DC motor based one axis gimbal, feedback will be from an ADXL335 analog accelerometer sensor. The controller implemented is a basic tuned PID. The microcontroller used is a PIC18F4550 under MPLAB IDE and coded with C.