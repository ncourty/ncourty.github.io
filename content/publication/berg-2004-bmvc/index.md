---
title: Horospherical Learning with Smart Prototypes

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`),
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Paul Berg
- Björn Michele
- Minh-Tan Pham
- Laetitia Chapel
- Nicolas Courty

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-09-10T23:12:57.823097Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types: [paper-conference, "VisionAndGraphics"]
#- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*BMVC*'
publication_short: ''

doi: ''

abstract: 'Hyperbolic spaces have emerged as an effective manifold to learn representations due to their ability to efficiently represent hierarchical data structures, with little distortion, even for low-dimensional embeddings. In the chosen hyperbolic model, such as the Poincaré ball, classification is usually conducted by leveraging a signed distance function to the hyperbolic equivalent of a plane (gyroplanes) or by measuring the alignment to a virtual fixed prototype. We propose, in a deep learning context, to leverage a different characterization of a decision boundary: Horospheres, which are level-sets of the Busemann function. They are geometrically equivalent to spheres tangent to the boundary of the hyperbolic space on a virtual point akin to a prototype. Accordingly, we define a new horospherical layer that can be adapted to any neural network backbone. In previous works, prototypes are usually uniformly distributed without using a potentially available label hierarchy for the task at hand. We also propose a hierarchically informed method for positioning these prototypes, based on the Gromov-Wasserstein distance.
We find that the combination of a good initialization and optimization of the prototypes improves the baseline performance for image classification on hierarchical datasets and in two semantic segmentation tasks, conducted on image and point cloud datasets. Source code will be released upon acceptance.'

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
links:
  - name: BMVC 2024
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
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
