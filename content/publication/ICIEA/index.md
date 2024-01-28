---
title: 'A Novel Fundamental PWM Excitation-Based Rotor Position Estimation Method for Precision Sensorless Control of IPMSMs'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - author_ziyan
  - Chuxiong Hu
  - Shuaihu Wu
  - Yunan Wang
  - Ze Wang
  - Yu Zhu

# Author notes (optional)
author_notes:

date: '2023-09-11'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-09-11'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 2023 IEEE 18th Conference on Industrial Electronics and Applications (ICIEA)
publication_short: 2023 IEEE 18th Conference on Industrial Electronics and Applications (ICIEA)

abstract: 

# Summary. An optional shortened abstract.
summary: '{{< icon name="trophy" pack="fas" >}} * **This work has won the Best Paper Award in _2023 IEEE 18th Conference on Industrial Electronics and Applications (ICIEA)_. [View Certificate.](publication/iciea/best.png)**'


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)

links:
 - name: Full text
   url: 'https://ieeexplore.ieee.org/document/10241791'

url_pdf: ''  
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'publication/iciea/slides.pdf'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Ziyan Zhao presenting his paper at the conference'
  focal_point: 
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: publication/iciea/slides.pdf
---

{{< icon name="trophy" pack="fas" >}} * **This work has won the Best Paper Award in _2023 IEEE 18th Conference on Industrial Electronics and Applications (ICIEA)_. [View Certificate.](best.png) [View Presentation Slides.](slides.pdf)**

With the advantage of high power density, high efficiency, and high accuracy, interior permanent magnet synchronous motors (IPMSMs) are widely applied in transportation, manufacturing equipment as well as laboratory devices such as mechanical arms and quadruped walking robots. To achieve precision motion control of IPMSMs, the rotor position feedback is essential. However, position sensing hardware such as encoders can cause increased space and cost, and are therefore not welcomed in some application scenarios. Meanwhile, **sensorless control techniques** can indirectly estimate the rotor position by making sufficient use of the stator voltage and current information. Therefore, sensorless control is now becoming more attractive due to saved cost and space, enhanced reliability, and the potential to prolong service life.

{{< figure src="img_1.png" title="Concepts of sensorless control." >}}

In sensorless control of IPMSMs, the fundamental PWM excitation (FPE)-based methods use PWM signals excitation and measure the derivative of the stator current as responses to estimate the rotor position. As the signal injection is no more required, the FPE-based methods have the potential to simplify the controller and achieve precision sensorless servo control. However, the current derivative is hard to measure accurately. Therefore, existing FPE-based methods usually suffer from significant position estimation errors. In this paper, a novel FPE-based rotor position estimation method is proposed with high stability and accuracy. Different from existing methods which usually sample current derivative only 2 times per PWM cycle, the proposed method takes 2 to 6 samples, depending on the amplitude and direction of the voltage vector. To make full use of all recent sample points, a first-in-first-out (FIFO)-based least squares algorithm is proposed. The optimal rotor position estimation can be obtained with only a small amount of computation since the analytical solution is given.

{{< figure src="block_diagram.png" title="Block diagram of the proposed sensorless control system." >}}

 Simulation and experimental results demonstrate that the rotor position can be estimated with an accuracy of 1 electrical degree under various speed and load. Sensorless closed-loop trajectory tracking control based on the proposed method is realized, which shows an exciting prospect of sensorless control in high-performance servo systems.

{{< video src="1.mp4" controls="yes">}}
{{< video src="2.mp4" controls="yes">}}
{{< video src="3.mp4" controls="yes">}}
