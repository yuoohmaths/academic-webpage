---
title: "Extracting complements and substitutes from sales data: a network perspective"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Sebastian Lautz
- Alisdair Wallis
- Renaud Lambiotte


# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2021-08-25T00:00:00Z"
doi: "10.1140/epjds/s13688-021-00297-4"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-08-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *EPJ Data Science*
publication_short: In *EPJ Data Sci*

abstract: The complementarity and substitutability between products are essential concepts in retail and marketing. Qualitatively, two products are said to be substitutable if a customer can replace one product by the other, while they are complementary if they tend to be bought together. In this article, we take a network perspective to help automatically identify complements and substitutes from sales transaction data. Starting from a bipartite product-purchase network representation, with both transaction nodes and product nodes, we develop appropriate null models to infer significant relations, either complements or substitutes, between products, and design measures based on random walks to quantify their importance. The resulting unipartite networks between products are then analysed with community detection methods, in order to find groups of similar products for the different types of relationships. The results are validated by combining observations from a real-world basket dataset with the existing product hierarchy, as well as a large-scale flavour compound and recipe dataset.

# Summary. An optional shortened abstract.
summary: The complementarity and substitutability between products are essential concepts in retail and marketing. 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Preprint
  url: https://arxiv.org/abs/2103.02042

url_pdf: 'https://arxiv.org/pdf/2103.02042.pdf'
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
  caption: ''# Image credit: [**DLPNG**](https://dlpng.com/png/7070875)
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
