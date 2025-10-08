---
# Documentation: https://docs.hugoblox.com/managing-content/

title: "(IJCV 2025) One paper on Horospherical Learning published in the International Journal of Computer Vision"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2025-10-08T14:52:59+02:00
lastmod: 2025-10-08T16:25:53+02:00
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
title: Multi-Prototype Hyperbolic Learning Guided by Class Hierarchy

Abstract: In many computer vision applications, datasets often exhibit an underlying taxonomy within the label space. To adhere to this hierarchical structure, hyperbolic spaces have emerged as an effective manifold for representation learning, thanks to their ability to encode hierarchical relationships, with little distortion, even for low-dimensional embeddings. Hyperbolic prototypical learning, where class labels are represented by prototypes, has recently demonstrated strong potential in this setting. However, existing methods generally assume a uniform distribution of prototypes, overlooking the hierarchical organization of labels that may be available for a given task. To better exploit this prior knowledge, we propose a hierarchically informed method for prototype positioning. Our approach leverages the Gromov-Wasserstein distance to align the hierarchical relationships between labels with the initial uniform spherical distribution of prototypes, leading to more structured and semantically meaningful representations. Additionally, within a deep learning framework, we propose an alternative characterization of decision boundaries using horospheres, which are level sets of the Busemann function. Geometrically, horospheres correspond to spheres tangent to the boundary of hyperbolic space at a virtual point analogous to a prototype, which makes them a compliant tool in the prototypical learning context. Accordingly, we define a new horospherical layer that can be adapted to any neural network backbone. This layer is particularly advantageous when the number of prototypes exceeds the number of classes, offering enhanced flexibility to the classifier. Through our experiments, we demonstrate that the combination of proper initialization and optimized prototype positioning significantly enhances baseline performance for image classification on hierarchical datasets. Additionally, we validate our approach in two semantic segmentation tasks, using both image and point cloud datasets, confirming its effectiveness in leveraging hierarchical label structures for improved classification performance.

[link to the paper](https://link.springer.com/article/10.1007/s11263-025-02571-8)