---
share: false
title: 'Online Data Drift Detection for Anomaly Detection Services based on Deep Learning towards Multivariate Time Series'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Gou Tan
  - Pengfei Chen*
  - Min Li

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: ''
doi: '10.1109/QRS60937.2023.00011'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-10-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 2023 IEEE 23rd International Conference on Software Quality, Reliability, and Security (QRS)
publication_short: (QRS 2023)

abstract: Deep learning models have been successfully adopted in anomaly detection for multivariate time series data in various fields. These models are good at capturing complex time dependencies and extracting meaningful patterns from time series data. However, the trained models may become outdated due to unforeseen changes in real-world data, which can lead to a decrease in the quality of model service. Therefore, it is crucial to continuously monitor the performance of the model and analyze its behavior to ensure its reliability and availability. We propose an online data drift detection method that uses an unsupervised deep learning network, Variational Autoencoder (VAE), to monitor deep learning models in the field of multivariate time series anomaly detection. This method consists of three main steps namely data collection and statistical analysis, real-time drift detection, and drift interpretation. We collect raw time series data and model prediction data non-invasively from the model server. Then they are separated into windows for drift detection. Furthermore, the method can provide analysis and interpretation when drift is detected. Our evaluation experiments involve three real-world datasets from various industrial domains and four different structured anomaly detection models. We validate the effectiveness of drift detection in multivariate time series, and then test how the anomaly detection models perform during data drift detection. The highest improvement in F1 score is approximately 0.16. In addition, we provide an analysis of the interpretability of the model performance.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10366704'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
