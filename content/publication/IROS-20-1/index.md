---
title: "DUI-VIO: Depth Uncertainty Incorporated Visual Inertial Odometry based on an RGB-D Camera"
authors:
- He Zhang
- Cang Ye
date: "2020-10-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of IEEE International Conference on Intelligent Robots and Systems (IROS)*, Las Vegas, Oct 25-29
publication_short: In *Proceedings of IEEE International Conference on Intelligent Robots and Systems (IROS)*, Las Vegas, Oct 25-29

abstract: This paper presents a new RGB-D-camera-based visual-inertial odometry (VIO), termed DUI-VIO, for estimating the motion state of the camera. First, a Gaussian mixture model (GMM) to is employed to model the uncertainty of the depth data for each pixel on the camera’s color image. Second, the uncertainties are incorporated into the VIO’s initialization and optimization processes to make the state estimate more accurate. In order to perform the initialization process, we propose a hybrid-perspective-n-point (PnP) method to compute the pose change between two camera frames and use the result to triangulate the depth for an initial set of visual features whose depth values are unavailable from the camera. Hybrid-PnP first uses a 2D-2D PnP algorithm to compute rotation so that more visual features may be used to obtain a more accurate rotation estimate. It then uses a 3D-2D scheme to compute translation by taking into account the uncertainties of depth data, resulting in a more accurate translation estimate. The more accurate pose change estimated by Hybrid-PnP help to improve the initialization result and thus the VIO performance in state estimation. In addition, Hybrid-PnP make it possible to compute the pose change by using a small number of features with a known depth. This improves the reliability of the initialization process. Finally, DUI-VIO incorporates the uncertainties of the inverse depth measurements into the nonlinear optimization process, leading to a reduced state estimation error. Experimental results validate that the proposed DUI-VIO method outperforms the state-of-the-art VIO methods in terms of accuracy and reliability.

# Summary. An optional shortened abstract.
summary:

# tags:
# - Source Themes
featured: true

# links:
#- name: Custom Link
#  url: http://example.org
url_pdf: '' #http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
url_video: 'https://www.youtube.com/watch?v=kYlQvT2iIow'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
