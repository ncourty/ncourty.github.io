---
# Documentation: https://docs.hugoblox.com/managing-content/

title: "(Neurips 2025) One paper on a differentiable Gromov Hyperbolicity accepted"
subtitle: "Work first authored by Pierre Houédry during his post-doc"
summary: ""
authors: []
tags: []
categories: []
date: 2025-10-08T14:53:07+02:00
lastmod: 2025-10-08T14:53:07+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
Title: *Bridging Arbitrary and Tree Metrics via Differentiable Gromov Hyperbolicity*

Abstract: 'Trees and the associated shortest-path tree metrics provide a powerful framework for representing hierarchical and combinatorial structures in data. Given an arbitrary metric space, its deviation from a tree metric can be quantified by Gromov's \delta-hyperbolicity. Nonetheless, designing algorithms that bridge an arbitrary metric to its closest tree metric is still a vivid subject of interest, as most common approaches are either heuristical and lack guarantees, or perform moderately well. In this work, we introduce a novel differentiable optimization framework, coined DeltaZero, that solves this problem. Our method leverages a smooth surrogate for Gromov's \delta-hyperbolicity which enables a gradient-based optimization, with a tractable complexity. The corresponding optimization procedure is derived from a problem with better worst case guarantees than existing bounds, and is justified statistically. Experiments on synthetic and real-world datasets demonstrate that our method consistently achieves state-of-the-art distortion.'

[Link to paper](https://arxiv.org/abs/2505.21073)