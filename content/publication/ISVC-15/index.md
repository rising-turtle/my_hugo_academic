---
title: "An RGB-D Camera based Walking Pattern Detection Method for Smart Rollators"
authors:
- He Zhang
- Cang Ye
date: "2016-12-20T00:00:00Z"
doi: "10.1007/978-3-319-27857-5_56"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of 11th International Symposium on Visual Computing (ISVC)*, Las Vegas, Dec. 14-16, pp. 624-633
publication_short: In *Proceedings of 11th International Symposium on Visual Computing (ISVC)*, Las Vegas, Dec. 14-16, pp. 624-633

abstract: This paper presents a walking pattern detection method for a smart rollator. The method detects the rollator user's lower extremities from the depth data of an RGB-D camera. It then segments the 3D point data of the lower extremities into the leg and foot data points, from which a skeletal system with 6 skeletal points and 4 rods is extracted and used to represent a walking gait. A gait feature, comprising the parameters of the gait shape and gait motion, is then constructed to describe a walking state. K-means clustering is employed to cluster all gait features obtained from a number of walking videos into 6 key gait features. Using these key gait features, a walking video sequence is modeled as a Markov chain. The stationary distribution of the Markov chain represents the walking pattern. Five Support Vector Machines (SVMs) are trained for walking pattern detection. Each SVM detects one of the five walking patterns. Experimental results demonstrate that the proposed method has a better performance in detecting walking patterns than three existing methods.

# Summary. An optional shortened abstract.
summary:

# tags:
# - Source Themes
featured: true

# links:
#- name: Custom Link
#  url: http://example.org
url_pdf: 'https://d1wqtxts1xzle7.cloudfront.net/42804583/An_RGB-D_Camera_based_Walking_Pattern_Detection_Method_for_Smart_Rollators.pdf?1455808229=&response-content-disposition=inline%3B+filename%3DAn_RGB-D_Camera_based_Walking_Pattern_De.pdf&Expires=1595346379&Signature=fYRMIZpGMJajE1PpbIBqTT-uJpbhpTQF8ANXPAvJUzGVE8xb8uNxvl1YIXZwiJXM0MUBTseiI3Oj-nMkZmz4gqH7pABjrKSu5E8QaoyhtXxzLeviUk5aybIuCgbwETiF5N4~CkfsYXjAc3PP4li5DAvadClCqca9rz~D4j0bPgEMTbEOCjG5ataWO72tElnPJIMt2POvn7Vm5Blt3S1k8xmh-sp6aqtetq8a~IS~epnvrEXEwJXmHTmZ-RhNtL6JV-noSOelgo-~d5xygdVIOog-vZG4E2ZkwheFCNnevSnHJngayw5DL82QiFvwg6Cz~hZU-KtFypn6~n-~af44Dw__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA' #http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: 'https://www.youtube.com/watch?v=bSuH0cJwwnw'

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
