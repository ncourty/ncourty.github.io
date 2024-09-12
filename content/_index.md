---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: posts
    content:
      title: News
      subtitle: '(More or less) recent actuality'
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 7
      # Filter on criteria
      filters:
        folders:
          - news
        author: ""
        category: ""
        tag: ""
        # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: list
      columns: '2'
  - block: collection
    id: featured-publications-1
    content:
      title: Featured publications
      subtitle: 'Machine learning track'
      filters:
        publication_type: "ML"
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: compact
  - block: collection
    id: featured-publications-2
    content:
      title: Featured publications
      subtitle: 'Remote Sensing'
      filters:
        publication_type: "RemoteSensing"
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: compact
  - block: collection
    id: featured-publications-3
    content:
      title: Featured publications
      subtitle: 'Computer Vision and Graphics'
      filters:
        publication_type: "VisionAndGraphics"
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: compact
  - block: collection
    id: featured-publications-4
    content:
      title: Featured publications
      subtitle: 'AI for Science'
      filters:
        publication_type: "AI4science"
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: compact

  - block: collection
    id: other-publications
    content:
      title: Other publications
      # text: |-
      #   {{% callout note %}}
      #   Quickly discover relevant content by [filtering publications](./publication/).
      #   {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="events" >}}
  #   design:
  #     columns: '2'
---
