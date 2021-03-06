---
title: "Camera Intrinsic Parameters Estimation by Visual Inertial Odometry for a Mobile Phone with Application to Assisted Navigation"
authors:
- Lingqiu Jin
- He Zhang
- Cang Ye
author_notes: ""
date: "2020-05-25T00:00:00Z"
doi: "10.1109/TMECH.2020.2997606"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE/ASME Transactions on Mechatronics, pp.1-1*"
publication_short: "*IEEE/ASME Transactions on Mechatronics, pp.1-1*"

abstract: The increasing computing and sensing capabilities of modern mobile phones have spurred research interests in developing new visual-inertial odometry (VIO) techniques to turn a smartphone into a self-contained vision-aided inertial navigation system for various applications. Smartphones nowadays use cameras with optical image stabilization (OIS) technology to reduce image blurs. When in action, the mechanism results in varying camera intrinsic parameters (CIP), which must be taken into account in the VIO computation. In this paper, we first develop a linear model to relate the CIP with the IMU-measured acceleration. Based on the model, we introduce a new VIO method, called CIP-VMobile, which treats CIP as state variables and tightly couples them with other state variables in a graph optimization process to estimate the optimal state. The method uses the linear model to construct a factor graph and uses the linear-model-computed values as initial CIP estimates to speed up the VIO computation and attain a better pose estimation result. Simulation and experimental results with an iPhone7 validate the method's efficacy. Based on CIP-VMobile, we fabricated a robotic navigation aid based on an iPhone 7 for assisted navigation. Experimental results with the RNA demonstrate CIP-VMobile's promise in real-world navigation applications.

# Summary. An optional shortened abstract.
summary:

tags:
# - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9099599&casa_token=Mydcy-UDUB0AAAAA:AcOs2TUSS4DqyYAdUETJMxpICmsbjdf7Cim09lRO-YXvKtAJygsl14KbNo6BoZkW9q704Qw' #http://arxiv.org/pdf/1512.04133v1
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
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
slides: example
---
