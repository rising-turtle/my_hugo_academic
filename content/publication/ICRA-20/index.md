---
title: "A Visual Positioning System for Indoor Blind Navigation"
authors:
- He Zhang
- Cang Ye
date: "2020-09-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of IEEE International Conference on Robotics and Automation (ICRA)*, Paris, May 31 - June 4
publication_short: In *Proceedings of IEEE International Conference on Robotics and Automation (ICRA)*, Paris, May 31 - June 4

abstract: This paper presents a new visual positioning system (VPS) for real-time pose estimation of a robotic navigation aid (RNA) that is used for assistive navigation of a visually impaired person. The backbone of the VPS is a new depth-enhanced visual-inertial odometry (DVIO) that uses an RGB-D camera and an inertial measurement unit (IMU) to estimate the 6-DOF pose of the device. The DVIO method extracts the geometric feature (the floor plane in this work) from the camera's depth data and integrates its measurement residuals with that of the visual features and the inertial data in a graph optimization framework for pose estimation. A new measure based on the Sampson error is introduced to describe the measurement residuals of the near-range visual features whose depths (measured by the depth camera) are accurate and that of the far-range visual features whose depths are unknown. The measure allows for the incorporation of both types of visual features into the graph optimization. The use of the geometric feature and the Sampson error improve pose estimation accuracy and precision. The DVIO method is paired with a particle-filter-based localization (PFL) method to localize the RNA in a 2D floor plan and use the information to guide the visually impaired person to reach the destination. The PFL reduces the RNA's position and heading error on the horizontal plane by aligning the camera's depth data with the floor plan map. Together, the DVIO and the PFL allow the VPS to accurately estimate the pose of the RNA for wayfinding and meanwhile generate a 3D local map for obstacle avoidance. Experimental results demonstrate the usefulness of the RNA in wayfinding and obstacle avoidance for the visually impaired in indoor spaces.

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
url_video: 'https://www.youtube.com/watch?v=fDQENJeFnks'

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
