---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "New publication at Neurips 2020 : Co-Optimal Transport"
subtitle: "New publication at Neurips 2020 "
summary: ""
authors: []
tags: []
categories: []
date: 2020-10-30T01:40:12+01:00
lastmod: 2020-10-30T01:40:12+01:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "A nice COOT illustration"
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ["oatmil"]
---

Optimal transport (OT) is a powerful geometric and probabilistic tool for finding correspondences and measuring similarity between two distributions. Yet, its original formulation relies on the existence of a cost function between the samples of the two distributions, which makes it impractical for comparing data distributions supported on different topological spaces. To circumvent this limitation, we propose a novel OT problem, named COOT for CO-Optimal Transport, that aims to simultaneously optimize two transport maps between both samples and features. This is different from other approaches that either discard the individual features by focussing on pairwise distances (e.g. Gromov-Wasserstein) or need to model explicitly the relations between the features. COOT leads to interpretable correspondences between both samples and feature representations and holds metric properties. We provide a thorough theoretical analysis of our framework and establish rich connections with the Gromov-Wasserstein distance. We demonstrate its versatility with two machine learning applications in heterogeneous domain adaptation and co-clustering/data summarization, where COOT leads to performance improvements over the competing state-of-the-art methods. 