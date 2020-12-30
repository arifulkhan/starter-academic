---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Street-level Travel-time Estimation via Aggregated Uber Data"
authors: [Kelsey Maass, Arun Sathanur, Arif Khan & Robert Rallo]
date: 2020-02-09
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-03-17T14:36:08-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "SIAM Workshop on Combinatorial Scientific Computing"
publication_short: "SIAM CSC"

abstract: "Estimating temporal patterns in travel times along road
segments in urban settings is of central importance to
trac engineers and city planners. In this work, we
propose a methodology to leverage coarse-grained and
aggregated travel time data to estimate the street-level
travel times of a given metropolitan area. Our main fo-
cus is to estimate travel times along the arterial road
segments where relevant data are often unavailable.
The central idea of our approach is to leverage easy-
to-obtain, aggregated data sets with broad spatial cov-
erage, such as the data published by Uber Movement,
as the fabric over which other expensive, fine-grained
datasets, such as loop counter and probe data, can
be overlaid. Our proposed methodology uses a graph
representation of the road network and combines sev-
eral techniques such as graph-based routing, trip sam-
pling, graph sparsification, and least-squares optimiza-
tion to estimate the street-level travel times. Using
sampled trips and weighted shortest-path routing, we
iteratively solve constrained least-squares problems to
obtain the travel time estimates. We demonstrate our
method on the Los Angeles metropolitan-area street
network, where aggregated travel time data is available
for trips between traffic analysis zones. Additionally,
we present techniques to scale our approach via a novel
graph pseudo-sparsification technique."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
