---
title: "A Graph-Based Hierarchical SLAM Framework for Large-Scale Mapping"
authors:
- He Zhang
- Zifeng Hou
- Nanjun Li
- Shuang Song
date: "2012-10-20T00:00:00Z"
doi: "10.1007/978-3-642-33515-0_44"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings 5th International Conference on Intelligent Robotics and Applications (ICIRA)*, Montreal, Quebec, Oct. 3-5, 2012, vol. 7507, pp 439-448
publication_short: In *Proceedings 5th International Conference on Intelligent Robotics and Applications (ICIRA)*, Montreal, Quebec, Oct. 3-5, 2012, vol. 7507, pp 439-448

abstract: In this paper, a graph-based hierarchical SLAM framework is proposed which ensures not only the high-speed operation of graph-based SLAM, but also feasibility of large-scale 3D map building. Both local and global level graph-based SLAM will be operated. They can be concurrently implemented in different computing units but must maintained communication which is called as a session. During each session, local level SLAM will create a pose-graph containing trajectory for mobile robot and information for local maps. To avoid communication congestion, raw density point cloud of each pose-node will be reduced into a sparser one by voxel grid filtering. When a session is closed, duo-graph strategy is executed to guarantee the consistency between successive local map. To associate massive local map information and closing loops in large-scale environment, graph-based algorithm will also be implemented in global level SLAM. Two experiments are carried out in the real indoor environment. In the first experiment, SLAM process is greatly accelerated in this framework by distributing the whole SLAM task into different level SLAM entities$:$ local level SLAM operated on robot and global on laptop. It shows that this framework is scalable and it can be implemented in CS(Client-Server) model. Second experiment is conducted in our biggest work office around which we control the robot traverse for three times. It demonstrates that this framework can simultaneously keep fast graph-based SLAM in local-end and generate consistent and convergent 3D map in global-end SLAM process.

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
