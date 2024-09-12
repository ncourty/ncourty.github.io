---
title: Neural network time-series classifiers for gravitational-wave searches in single-detector
  periods

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`),
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Agata Trovato
- E Chassande-Mottin
- M Bejger
- Remi Flamary
- Nicolas Courty

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-09-10T23:12:57.777305Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types: [article-journal, "AI4science"]

# Publication name and optional abbreviated publication name.
publication: '*Classical and Quantum Gravity*'
publication_short: ''

doi: ''

abstract: 'The search for gravitational-wave signals is limited by non-Gaussian transient noises that mimic astrophysical signals. Temporal coincidence between two or more detectors is used to mitigate contamination by these instrumental glitches. However, when a single detector is in operation, coincidence is impossible, and other strategies have to be used. We explore the possibility of using neural network classifiers and present the results obtained with three types of architectures: convolutional neural network, temporal convolutional network, and inception time. The last two architectures are specifically designed to process time-series data. The classifiers are trained on a month of data from the LIGO Livingston detector during the first observing run (O1) to identify data segments that include the signature of a binary black hole merger. Their performances are assessed and compared. We then apply trained classifiers to the remaining three months of O1 data, focusing specifically on single-detector times. The most promising candidate from our search is 2016-01-04 12:24:17 UTC. Although we are not able to constrain the significance of this event to the level conventionally followed in gravitational-wave searches, we show that the signal is compatible with the merger of two black holes with masses m1=50.7+10.4−8.9M⊙ and m2=24.4+20.2−9.3M⊙ at the luminosity distance of dL=564+812−338Mpc. '

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
links:
 - name: 'Classical and Quantum Gravity'

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
