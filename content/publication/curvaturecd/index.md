---
title: "Curvature-based Clustering on Graphs"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Zachary Lubberts
- Melanie Weber


# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

#date: "2025-06-01T00:00:00Z"
#doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-06-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *Journal of Machine Learning Research*
publication_short: In *JMLR*

abstract: Unsupervised node clustering (or community detection) is a classical graph learning task. In this paper, we study algorithms, which exploit the geometry of the graph to identify densely connected substructures, which form clusters or communities. Our method implements discrete Ricci curvatures and their associated geometric flows, under which the edge weights of the graph evolve to reveal its community structure. We consider several discrete curvature notions and analyze the utility of the resulting algorithms. In contrast to prior literature, we study not only single-membership community detection, where each node belongs to exactly one community, but also mixed-membership community detection, where communities may overlap. For the latter, we argue that it is beneficial to perform community detection on the line graph, i.e., the graph’s dual. We provide both theoretical and empirical evidence for the utility of our curvature-based clustering algorithms. In addition, we give several results on the relationship between the curvature of a graph and that of its dual, which enable the efficient implementation of our proposed mixed-membership community detection approach and which may be of independent interest for curvature-based network analysis.
# Summary. An optional shortened abstract.
summary: Unsupervised node clustering (or community detection) is a classical graph learning task. In this paper, we study algorithms, which exploit the geometry of the graph to identify densely connected substructures, which form clusters or communities. Our method implements discrete Ricci curvatures and their associated geometric flows, under which the edge weights of the graph evolve to reveal its community structure. We consider several discrete curvature notions and analyze the utility of the resulting algorithms. In contrast to prior literature, we study not only single-membership community detection, where each node belongs to exactly one community, but also mixed-membership community detection, where communities may overlap. For the latter, we argue that it is beneficial to perform community detection on the line graph, i.e., the graph’s dual. We provide both theoretical and empirical evidence for the utility of our curvature-based clustering algorithms. In addition, we give several results on the relationship between the curvature of a graph and that of its dual, which enable the efficient implementation of our proposed mixed-membership community detection approach and which may be of independent interest for curvature-based network analysis.
tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: URL
  url: http://jmlr.org/papers/v26/24-0781.html
- name: Preprint
  url: https://arxiv.org/abs/2307.10155

url_pdf: 'https://arxiv.org/pdf/2307.10155.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Figure 1'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
#- example
# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
