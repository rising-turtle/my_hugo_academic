---
title: "An Indoor Wayfinding System Based on Geometric Features Aided Graph SLAM for the Visually Impaired"
authors:
- He Zhang
- Cang Ye
author_notes: ""
date: "2017-03-25T00:00:00Z"
doi: "10.1109/TNSRE.2017.2682265"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Neural Systems and Rehabilitation Engineering, vol.25, pp. 1592-1604*"
publication_short: "*IEEE Transactions on Neural Systems and Rehabilitation Engineering, vol.25, pp. 1592-1604*"

abstract: This paper presents a 6-DOF pose estimation (PE) method and an indoor wayfinding system based on the method for the visually impaired. The PE method involves two graph SLAM processes to reduce the accumulative pose error of the device. In the first step, the floor plane is extracted from the 3D camera’s point cloud and added as a landmark node into the graph for 6-DOF SLAM to reduce roll, pitch and Z errors. In the second step, the wall lines are extracted and incorporated into the graph for 3-DOF SLAM to reduce X, Y and yaw errors. The method reduces the 6-DOF pose error and results in more accurate pose with less computational time than the state-of-the-art planar SLAM methods. Based on the PE method, a wayfinding system is developed for navigating a visually impaired person in an indoor environment. The system uses the estimated pose and floorplan to locate the device user in a building and guides the user by announcing the points of interest and navigational commands through a speech interface. Experimental results validate the effectiveness of the PE method and demonstrate that the system may substantially ease an indoor navigation task.

# Summary. An optional shortened abstract.
summary:

tags:
# - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7879309&casa_token=xX6lQK06JPcAAAAA:_xTyc1gFXzkHdao1YpfEDqyW3hd9pYZJuxanHvgkoSwxf_CS-X2Jo4QRJI6m0d_0VkWNGE0&tag=1' #http://arxiv.org/pdf/1512.04133v1
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=mTAa8xx3fMo&t=6s'

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
