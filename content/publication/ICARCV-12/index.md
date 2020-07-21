---
title: "Duo-graph: An efficient and robust method for large-scale mapping for visual-guided robots"
authors:
- He Zhang
- Zifeng Hou
- Nanjun Li
- Shuang Song
- Pengzhi Xu
date: "2012-12-20T00:00:00Z"
doi: "10.1109/ICARCV.2012.6485179"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of 12th International Conference on Control, Automation, Robotics and Vision (ICARCV)*, Guangzhou, China, Dec. 5-7, 2012, pp. 323-328
publication_short: In *Proceedings of 12th International Conference on Control, Automation, Robotics and Vision (ICARCV)*, Guangzhou, China, Dec. 5-7, 2012, pp. 323-328

abstract: In this paper, we present a duo-graph Simultaneous Localization and Mapping (SLAM) method that enables visual-guided robot to efficiently and robustly generate consistent 3D map in a large-scale environment. Recently the conditional independent graph (CI-GRAPH) has been proved to be an efficient and robust method for solving the large-scale SLAM problem. However, it stems from extended kalman filter (EKF) SLAM that suffers from high computational load when number of the landmarks becomes large. Moreover, the big noise in the measurement can lead EKF SLAM far from convergence. These disadvantages are the cases in the visual-guided robot. To solve these problems, we propose a duo-graph structure that sustains the feasibility of a hierarchical graph-based SLAM framework. It implements two level graph-based SLAM$:$ local and global SLAM. Utilizing the characteristic of the duo-graph structure, the local SLAM can efficiently localize itself while the global SLAM can accurately close loops in the large scale environment. In addition, our method can filter massive noisy visual features and eliminate mismatches in the global SLAM process. To demonstrate the superiority of our method, both simulation and real experiments are carried out.

# Summary. An optional shortened abstract.
summary:

# tags:
# - Source Themes
featured: true

# links:
#- name: Custom Link
#  url: http://example.org
url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6485179&casa_token=bZnzwOe3DUkAAAAA:RMEh_LL0YgAbN4rBTZ-T2d1tsLyHw0yksrCDEXaSKJvn2AtINu2mpA7eFp7uZ1qsbYo1dnU' #http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
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
