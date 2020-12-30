---
title: "Asynchronous Online Federated Learning for Edge Devices with Non-IID Data"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Yue Ning
- Martin Slawski
- Huzefa Rangwala. 

  In 2020 IEEE International Conference on Big Data (Big Data)


# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2020-12-11T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2020 IEEE International Conference on Big Data (Big Data)*
publication_short: In *BigData*

abstract: (Preprint) Federated learning (FL) is a machine learning paradigm where a shared central model is learned across distributed edge devices while the training data remains on these devices. Federated Averaging (FedAvg) is the leading optimization method for training non-convex models in this setting with a synchronized protocol. However, the assumptions made by FedAvg are not realistic given the heterogeneity of devices. In particular, the volume and distribution of collected data vary in the training process due to different sampling rates of edge devices. The edge devices themselves also vary in their available communication bandwidth and system configurations, such as memory, processor speed, and power requirements. This leads to vastly different training times as well as model/data transfer times. Furthermore, availability issues at edge devices can lead to a lack of contribution from specific edge devices to the federated model. In this paper, we present an Asynchronous Online Federated Learning (ASO-Fed) framework, where the edge devices perform online learning with continuous streaming local data and a central server aggregates model parameters from clients. Our framework updates the central model in an asynchronous manner to tackle the challenges associated with both varying computational loads at heterogeneous edge devices and edge devices that lag behind or dropout. We perform extensive experiments on a simulated benchmark image dataset and three real-world non-IID streaming datasets. The results demonstrate the effectiveness of ASO-Fed on converging fast and maintaining good prediction performance.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/1911.02134.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

