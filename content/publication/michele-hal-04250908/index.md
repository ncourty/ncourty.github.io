---
title: 'SALUDA: Surface-based Automotive Lidar Unsupervised Domain Adaptation'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`),
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Bjoern Michele
- Alexandre Boulch
- Gilles Puy
- Tuan-Hung Vu
- Renaud Marlet
- Nicolas Courty

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-03-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-09-10T23:12:57.218726Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types: [paper-conference,"VisionAndGraphics"]
#- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*3DV*'
publication_short: ''

doi: ''

abstract: 'Learning models on one labeled dataset that generalize well on another domain is a difficult task, as several shifts might happen between the data domains. This is notably the case for lidar data, for which models can exhibit large performance discrepancies due for instance to different lidar patterns or changes in acquisition conditions. This paper addresses the corresponding Unsupervised Domain Adaptation (UDA) task for semantic segmentation. To mitigate this problem, we introduce an unsupervised auxiliary task of learning an implicit underlying surface representation simultaneously on source and target data. As both domains share the same latent representation, the model is forced to accommodate discrepancies between the two sources of data. This novel strategy differs from classical minimization of statistical divergences or lidar-specific domain adaptation techniques. Our experiments demonstrate that our method achieves a better performance than the current state of the art, both in real-to-real and synthetic-to-real scenarios. '

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: true

# Links
url_pdf: ''
url_code: ''
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
  url: https://cnrs.hal.science/hal-04250908
- name: 3DV 2024
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
