---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Trajectory optimization on manifolds with applications to quadrotor systems
subtitle: ''
summary: ''
authors:
- Michael Watterson
- Sikang Liu
- Ke Sun
- Trey Smith
- Vijay Kumar
tags: []
categories: []
date: '2020-01-01'
lastmod: 2020-12-24T11:42:29-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2020-12-24T16:42:29.170566Z'
publication_types:
- '2'
abstract: ' Manifolds are used in almost all robotics applications even if they are
  not modeled explicitly. We propose a differential geometric approach for optimizing
  trajectories on a Riemannian manifold with obstacles. The optimization problem depends
  on a metric and collision function specific to a manifold. We then propose our safe
  corridor on manifolds (SCM) method of computationally optimizing trajectories for
  robotics applications via a constrained optimization problem. Our method does not
  need equality constraints, which eliminates the need to project back to a feasible
  manifold during optimization. We then demonstrate how this algorithm works on an
  example problem on SO(3) and a perception-aware planning example for visual–inertially
  guided robots navigating in three dimensions. Formulating field of view constraints
  naturally results in modeling with the manifold R3×S2, which cannot be modeled as
  a Lie group. We also demonstrate the example of planning trajectories on SE(3) for
  a formation of quadrotors within an obstacle filled environment. '
publication: '*The International Journal of Robotics Research*'
url_pdf: https://doi.org/10.1177/0278364919891775
doi: 10.1177/0278364919891775

url_pdf: https://journals.sagepub.com/doi/abs/10.1177/0278364919891775
---
