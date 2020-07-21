---
title: "The VCU-RVI Benchmark: Evaluating Visual Inertial Odometry for Indoor Navigation Applications with an RGB-D
Camera"
authors:
- He Zhang
- Lingqiu Jin
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

abstract: This paper presents VCU-RVI, a new visual inertial odometry (VIO) benchmark with a set of diverse data sequences in different indoor scenarios. The benchmark is captured using an Structure Core (SC) sensor, consisting of RGB-D camera and an IMU. It provides aligned color and depth images with 640x480 resolution at 30 Hz. The camera's data is synchronized with the IMU's data at 100 Hz. Thirty-nine data sequences covering a total of ~3.7 kilometers trajectory are recorded in various indoor environments by two experimental setups$:$ holding it by a hand or installing it on a wheeled robot. For the handheld SC data sequences in the laboratory, they are recorded under three challenging conditions$:$ fast motion, radical illumination changing, and dynamic objects. Besides, data sequences for long distance indoor navigation are collected covering different indoor scenarios$:$ room, corridor, hall, and stairway. For the data sequences captured using the wheeled robot, half of them are recorded with sufficient IMU excitation in the beginning of the sequence, allowing to test the VIO methods with the requirement of sufficient motion conditions for initialization. We also put three bumpers in the laboratory to simulate bumpy road scenarios where the robot's motion is of 6-DOF. In addition, data sequences for long distance travel are also collected by the wheel robot. For trajectory evaluation, we use a motion capture system (120 Hz) to provide accurate pose ground truth. We conduct experiments to evaluate state-of-the-art VIO algorithms using our benchmark. The VCU-RVI dataset, the evaluated VIO methods, and the evaluation tools to generate the experimental results are made public.

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
