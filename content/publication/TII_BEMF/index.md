---
title: "Back EMF-Based Dynamic Position Estimation in the Whole Speed Range for Precision Sensorless Control of PMLSM"
authors:
  - author_ziyan
  - Chuxiong Hu
  - Ze Wang
  - Shuaihu Wu
  - Zhijin Liu
  - Yu Zhu
author_notes:

date: "2022-09-19"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-09-19"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Industrial Informatics ( Volume: 19, Issue: 5, May 2023)"
publication_short: "IEEE Transactions on Industrial Informatics ( Volume: 19, Issue: 5, May 2023)"

abstract: 

# Summary. An optional shortened abstract.
summary: Published in *IEEE Transactions on Industrial Informatics*. (SCI/EI, **IF=12.3**). [View Full Text.](https://ieeexplore.ieee.org/document/9895363)

tags: []
#- Source Themes
featured: false

links:
 - name: Full text
   url: 'https://ieeexplore.ieee.org/document/9895363'

url_pdf: ''  
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Experimental setup.'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

Back electromotive force (EMF)-based sensorless control strategies for permanent-magnet linear synchronous motor (PMLSM) have the potential to simplify the mechatronic system, reduce the cost and prolong the service life. However, the poor performance in the low-to-zero speed region limits their application range. In this article, a novel back EMF-based mover position estimator is proposed to achieve consistent good accuracy in the whole speed range including high speed, medium speed, low speeds, temporary standstill, and speed reversals. The three-phase flux linkages are obtained by directly calculating the integration of back EMF. To overcome the curve drift caused by the integrator, this article proposes a jumping correction algorithm and a uniform correction algorithm. The mover position is calculated from the corrected flux linkages. This article also realizes a closed-loop sensorless trajectory tracking control system using the proposed position estimator. Experimental results on a PMLSM demonstrate that the proposed position estimator can guarantee the stability and accuracy in the whole speed range. Compared with the existing back EMF-based methods working only well in high-speed region and usually with mm -level accuracy, the proposed method achieves an accuracy of sub-200 μm regardless of the reference trajectory, and has exciting prospect in industrial applications.

{{< video src="sensorless.mp4" controls="yes">}}
