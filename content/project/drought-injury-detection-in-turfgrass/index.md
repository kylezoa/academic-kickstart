---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Drought Injury Detection in Turfgrass"
summary: "Improve detection of drought injured turfgrass with aerial multispectral images."
authors: []
tags: []
categories: []
date: 2019-10-04T15:51:51-07:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Classification map of turfgrass plot. Red indicates false negative for the actual ET replacement level. Green indicates true positive."
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

links:
- name: Lab Website
  url: https://digitalag.ucdavis.edu/research/drought-injury-turfgrass-rs

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

# Research goal
Improve drought injury detection in turfgrass using aerial multispectral imagery
* Can multispectral cameras detect drought injury that can not be seen in the visible spectrum?
* Can we detect drought injured turfgrass earlier before the effects are seen in the visible spectrum?

# Personal involvement
*	Develop pre-processing and machine learning pipeline for drought injury classification in turfgrass with multispectral images using Python and XGBoost
* Compare multispectral classification performance with RGB images to understand detection performance gain using all spectral bands

For a percent green calculator, I have written a [script](https://github.com/kylezoa/turf-percent-green) to process directories of lightbox images in Python for those who may not use ImageJ/Fiji regularly.