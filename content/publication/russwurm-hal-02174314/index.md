---
title: End-to-end Learning for Early Classification of Time Series

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`),
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Marc Russwurm
- Sébastien Lefevre
- Nicolas Courty
- Rémi Emonet
- Marco Körner
- Romain Tavenard

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2019-07-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-09-10T23:12:57.645328Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types: [article-journal, 'RemoteSensing']
#- manuscript

# Publication name and optional abbreviated publication name.
publication: ''
publication_short: ''

doi: ''

abstract: 'Remote sensing satellites capture the cyclic dynamics of our Planet in regular time intervals recorded in satellite time series data. End-to-end trained deep learning models use this time series data to make predictions at a large scale, for instance, to produce up-to-date crop cover maps. Most time series classification approaches focus on the accuracy of predictions. However, the earliness of the prediction is also of great importance since coming to an early decision can make a crucial difference in time-sensitive applications.

In this work, we present an End-to-End Learned Early Classification of Time Series (ELECTS) model that estimates a classification score and a probability of whether sufficient data has been observed to come to an early and still accurate decision. ELECTS is modular: any deep time series classification model can adopt the ELECTS conceptual idea by adding a second prediction head that outputs a probability of stopping the classification. The ELECTS loss function then optimizes the overall model on a balanced objective of earliness and accuracy. Our experiments on four crop classification datasets from Europe and Africa show that ELECTS allows reaching state-of-the-art accuracy while reducing the quantity of data massively to be downloaded, stored, and processed.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: true

# Links
url_pdf: ''
url_code: 'https://github.com/marccoru/elects'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
links:
- name: URL
  url: https://hal.science/hal-02174314
- name: ISPRS Journal
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
