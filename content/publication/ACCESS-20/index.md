---
title: "Plane-Aided Visual-Inertial Odometry for 6-DOF Pose Estimation of a Robotic Navigation Aid"
authors:
- He Zhang
- Cang Ye
author_notes: ""
date: "2020-05-25T00:00:00Z"
doi: "10.1109/ACCESS.2020.2994299"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Access, vol. 8, pp. 90042 - 90051*"
publication_short: "*IEEE Access, vol. 8, pp. 90042 - 90051*"

abstract: The classic visual-inertial odometry (VIO) method estimates the 6-DOF pose of a moving camera by fusing the camera’s ego-motion estimated by visual odometry (VO) and the motion measured by an inertial measurement unit (IMU). The VIO attempts to updates the estimates of the IMU’s biases at each step by using the VO’s output to improve the accuracy of IMU measurement. This approach works only if an accurate VO output can be identified and used. However, there is no reliable method that can be used to perform an online evaluation of the accuracy of the VO. In this paper, a new VIO method is introduced for pose estimation of a robotic navigation aid (RNA) that uses a 3D time-of-flight camera for assistive navigation. The method, called plane-aided visual-inertial odometry (PAVIO), extracts planes from the 3D point cloud of the current camera view and track them onto the next camera view by using the IMU’s measurement. The covariance matrix of each tracked plane’s parameters is computed and used to perform a plane consistent check based on a chi-square test to evaluate the accuracy of VO’s output. PAVIO accepts a VO output only if it is accurate. The accepted VO outputs, the information of the extracted planes, and the IMU’s measurements over time are used to create a factor graph. By optimizing the graph, the method improves the accuracy in estimating the IMU bias and reduces the camera’s pose error. Experimental results with the RNA validate the effectiveness of the proposed method. PAVIO can be used to estimate the 6-DOF pose for any 3D-camera-based visual-inertial navigation system.

# Summary. An optional shortened abstract.
summary:

tags:
# - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9091872' #http://arxiv.org/pdf/1512.04133v1
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
  caption: '' # 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
