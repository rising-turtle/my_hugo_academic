---
title: "A Depth-Enhanced Visual Inertial Odometry for a Robotic Navigation Aid for Blind People"
authors:
- He Zhang
- Lingqiu Jin
- Cang Ye
date: "2019-11-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of Visual-Inertial Navigation$:$ Challenges and Applications Workshop at IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)*, Macau, China, Nov. 4-8, 2019. (***LORD Best Paper Award***)
publication_short: In *Proceedings of Visual-Inertial Navigation$:$ Challenges and Applications Workshop at IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)*, Macau, China, Nov. 4-8, 2019. (***LORD Best Paper Award***)

abstract: This paper presents a new method, called depth-enhanced visual-inertial odometry (DVIO), for real-time pose estimation of a robotic navigation aid (RNA) for assistive wayfinding. The method estimates the device pose by using an RGB-D camera and an inertial measurement unit (IMU). It extracts the floor plane from the camera's depth data and tightly couple the floor plane, the visual features (with depth data from the RGB-D camera or unknown depth), and the IMU's inertial data in a graph optimization framework for 6-DOF pose estimation. Due to use of the floor plane and the depth data from the RGB-D camera, the DVIO method has a better pose estimation accuracy than its VIO counterpart. To enable real-time computing on the RNA, the size of the sliding window for the graph optimization is reduced to trade some accuracy for computational efficiency. Experimental results demonstrate that the method achieved a pose estimation accuracy similar to that of the state of the art VIO but ran at a much faster speed (with a pose update rate of 18 Hz).

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
