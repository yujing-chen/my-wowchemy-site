---
title: "FedAT: A communication-efficient federated learning method with asynchronous tiers under non-iid data"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Zheng Chai
- admin
- Liang Zhao
- Yue Cheng
- Huzefa Rangwala. 

  *(Priprint)*


# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2020-10-11T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *submission*
publication_short: In *submission*

abstract: Federated learning (FL) involves training a model over massive distributed devices, while keeping the training data localized. This form of collaborative learning exposes new tradeoffs among model convergence speed, model accuracy, balance across clients, and communication cost, with new challenges including (1) straggler problem, where the clients lag due to data or (computing and network) resource heterogeneity, and (2) communication bottleneck, where a large number of clients communicate their local updates to a central server and bottleneck the server. Many existing FL methods focus on optimizing along only one dimension of the tradeoff space. Existing solutions use asynchronous model updating or tiering-based synchronous mechanisms to tackle the straggler problem. However, the asynchronous methods can easily create a network communication bottleneck, while tiering may introduce biases as tiering favors faster tiers with shorter response latencies. To address these issues, we present FedAT, a novel Federated learning method with Asynchronous Tiers under Non-i.i.d. data. FedAT synergistically combines synchronous intra-tier training and asynchronous cross-tier training. By bridging the synchronous and asynchronous training through tiering, FedAT minimizes the straggler effect with improved convergence speed and test accuracy. FedAT uses a straggler-aware, weighted aggregation heuristic to steer and balance the training for further accuracy improvement. FedAT compresses the uplink and downlink communications using an efficient, polyline-encoding-based compression algorithm, therefore minimizing the communication cost. Results show that FedAT improves the prediction performance by up to 21.09%, and reduces the communication cost by up to 8.5x, compared to state-of-the-art FL methods.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2010.05958.pdf'
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

