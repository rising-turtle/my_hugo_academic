---
title: "An Iterative Graph Optimization Approach for 2D SLAM"
authors:
- He Zhang
- Guoliang Liu
- Zifeng Hou
date: "2014-09-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *6th IROS Workshop on Planning, Perception and Navigation for Intelligent Vehicles (PPNIV)*, Chicago, Sep. 14-18
publication_short: In *6th IROS Workshop on Planning, Perception and Navigation for Intelligent Vehicles (PPNIV)*, Chicago, Sep. 14-18

abstract: The-state-of-the-art graph optimization method can robustly converge into a solution with least square errors for the graph structure. Nevertheless, when a biased edge (erroneous transformation with over-confident information matrix) exists, the optimal solution can produce the large deviation because of error propagation produced by the biased edge. In order to solve this problem in graph-based 2D SLAM system, this paper proposed an iterative graph optimization approach. To reduce the errors propagated from the biased edges, we iteratively reconstruct the graph structure by referring to the result of the graph optimization process. Meanwhile, to maintain the information of the other well estimated edges, we strictly update the graph structure by considering the scan-correlation score and the marginal covariance. In addition, we apply a novel key-node mechanism to robustly detect the loop-closure by a linear interpolation algorithm. The experiments show that the proposed method is more robust and accurate than the previous methods when the biased edges exist.

# Summary. An optional shortened abstract.
summary:

# tags:
# - Source Themes
featured: true

# links:
#- name: Custom Link
#  url: http://example.org
url_pdf: 'http://ppniv14.irccyn.ec-nantes.fr/final/session1_He.pdf' #http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
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
