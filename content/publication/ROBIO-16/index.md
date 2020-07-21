---
title: "An indoor navigation aid for the visually impaired"
authors:
- He Zhang
- Cang Ye
date: "2016-12-20T00:00:00Z"
doi: "10.1109/ROBIO.2016.7866366"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of IEEE International Conference on Robotics and Biomimetics (ROBIO)*, Qingdao, China, Dec. 3-7, pp. 467-472 (***Finalist of Best Conference Paper Award***)
publication_short: In *Proceedings of IEEE International Conference on Robotics and Biomimetics (ROBIO)*, Qingdao, China, Dec. 3-7, pp. 467-472 (***Finalist of Best Conference Paper Award***)

abstract: This paper presents a 6-DOF pose estimation (PE) method and an indoor wayfinding system based on the method for the visually impaired (VI). The PE method involves two graph SLAM processes to reduce the accumulative pose error of device. In the first step, the floor plane is extracted from the 3D camera’s point cloud and added as a landmark node into the graph for 6-DOF SLAM to reduce roll, pitch and Z errors. In the second step, the wall lines are extracted and incorporated into the graph for 3-DOF SLAM to reduce X, Y and yaw errors. The method reduces the 6-DOF pose error and results in more accurate pose with less computational time than the existing state-of-the-art planar SLAM methods. Based on the PE method, a wayfinding system is developed for navigating a VI person in an indoor environment. The system uses the estimated pose and floorplan to locate the device user in a building and guide the user by announcing the points of interest and navigational commands through a speech interface. Experimental results validate the effectiveness of the PE method and demonstrate that the system may substantially ease an indoor navigation task.

# Summary. An optional shortened abstract.
summary:

# tags:
# - Source Themes
featured: true

# links:
#- name: Custom Link
#  url: http://example.org
url_pdf: 'https://d1wqtxts1xzle7.cloudfront.net/53064623/ROBIO_CameraReady_update.pdf?1494392301=&response-content-disposition=inline%3B+filename%3DAn_Indoor_Navigation_Aid_for_the_Visuall.pdf&Expires=1595346416&Signature=eRD5jz04Fq19V~Bpy-haPdv9W9bHNWyDwA5mb8kIF0AfG3QZZrg1I0Szc96rg5J1KmCjtpF2-yA3KNz9IWpXVI1e7HMlDKzcclQ669vytd5ImOaVHtyHxQr7TPAdHBIThTlnvGIiLwlsLCw-ny7dIhObwGMKRfHd17FfvXpXg1ITO-TPJbOE-FqF5~gjDQNdFpi-zrQwbq1XHLQ9xQG~ztQlqaIqQZW-Lw6eq1gnh-TCCAtbtQmUcRyttT8zkUq0y3o8jipDe-lsuP31rgAoBYGgqsdsRSlqhf7yRO-~Mp6CkBS0cnJghGd7Y~3hQELapFaJ3Y2br1u8R4IX327yYQ__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA' #http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
url_video: 'https://www.youtube.com/watch?v=mTAa8xx3fMo&t=6s'

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
