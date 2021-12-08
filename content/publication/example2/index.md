---
title: "Unifying Diffusion Models on Networks and Their Influence Maximisation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Renaud Lambiotte


# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2021-12-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-12-02T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *arXiv*
publication_short: In *arXiv*

abstract: Information diffusion in social networks is a central theme in computational social sciences, with important theoretical and practical implications, such as the influence maximisation problem for viral marketing. Two widely adopted diffusion models are the independent cascade model where nodes adopt their behaviour from each neighbour independently, and the linear threshold model where collective effort from the whole neighbourhood is needed to influence a node. However, both models suffer from certain drawbacks, including a binary state space, where nodes are either active or not, and the absence of feedback, as nodes can not be influenced after having been activated. To address these issues, we consider a model with continuous variables that has the additional advantage of unifying the two classic models, as the extended independent cascade model and the extended linear threshold model are recovered by setting appropriate parameters. For the associated influence maximisation problem, the objective function is no longer submodular, a feature that most approximation algorithms are based on but is arguably strict in practice. Hence, we develop a framework, where we formulate the influence maximisation problem as a mixed integer nonlinear programming and adopt derivative-free methods. Furthermore, we propose a customised direct search method specifically for the proposed diffusion model, with local convergence. We also show that the problem can be exactly solved in the case of linear dynamics by selecting nodes according to their Katz centrality. We demonstrate the rich behaviour of the newly proposed diffusion model and the close-to-optimal performance of the customised direct search numerically on both synthetic and real networks. 

# Summary. An optional shortened abstract.
summary: We unify the features from the classic models into a novel class of information diffusion model, and propose a general framework for the influence maximisation problem that is applicable to a broad range of functions describing the overall influence.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Preprint
  url: https://arxiv.org/abs/2112.01465

url_pdf: 'https://arxiv.org/pdf/2112.01465.pdf'
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
  caption: 'Image credit: [**Information Technology and Innovation Foundation**](https://www.linkedin.com/company/information-technology-and-innovation-foundation/)'
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
