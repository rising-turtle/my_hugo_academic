---
title: "Plane-Aided Visual-Inertial Odometry for Pose Estimation of a 3D Camera based Indoor Blind Navigation System"
authors:
- He Zhang
- Cang Ye
date: "2017-09-20T00:00:00Z"
doi: "10.5244/C.31.169"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of British Machine Vision Conference (BMVC)*, London, Sep. 4-7
publication_short: In *Proceedings of British Machine Vision Conference (BMVC)*, London, Sep. 4-7

abstract: The classic visual-inertial odometry (VIO) method estimates a moving camera’s 6-DOF pose relative to its starting point by fusing the camera’s ego-motion measured by a visual odometry (VO) and the motion measured by an inertial measurement unit (IMU). The VIO attempts to updates the estimates of the IMU’s biases at each step by using the VO’s output so as to improve the accuracy of IMU measurement. This approach works only if an accurate VO output can be identified and used. However, there is no reliable method that can be used to evaluate the accuracy of the VO. In this paper, a new VIO method is introduced for pose estimation of a robotic navigation aid (RNA) that uses a 3D time-of-flight camera for perception. The method, called plane-aided visual-inertial odometry (PAVIO), extracts planes from the 3D point cloud of the current camera view and track them onto the next camera view by using the IMU’s measurement. The tracking result is used to accept the VO output only if it is accurate. The accepted VO outputs, the information of the extracted planes, and the IMU’s measurements over time are used to create a factor graph. By optimizing the graph, the method improves the estimation accuracy of the IMU bias and reduces the camera’s pose error. Experimental results with the RNA validate the effectiveness of the proposed method.

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
# url_video: '#'

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
