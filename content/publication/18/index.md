---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Distributed Travel Time Estimation Capability for Metropolitan-sized Road Transportation Networks"
authors: [Arif Khan, Arun Sathanur, Kelsey Maass & Robert Rallo]
date: 2020-07-09
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-17T14:36:08-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "SIGKDD International Workshop on Urban Computing"
publication_short: "SIGKDD Urban Computing"

abstract: "Street-level travel time estimation along with the temporal variations
in patterns of travel times is an important component of
traffic planning and operation in modern urban settings. In this
work, we propose a scalable distributed-computing based methodology
to leverage coarse-grained and aggregated travel time data
to estimate the street-level travel times of a given metropolitan
area. Our approach, termed TranSEC (Transportation State Estimation
Capability), leverages easy-to-obtain, aggregated data sets
with broad spatial coverage, such as the data published by Uber
Movement and can handle road networks of very large size such
as whole metropolitan areas. TranSEC is flexible enough to accommodate
augmentation with fine-grained but potentially more
expensive datasets, such as curated GPS-based data and probe data.
Our proposed methodology uses a graph representation of the
road network and combines several techniques such as weighted
shortest-path routing, a trip sampling and a biased travel time sampling
schemes, graph sparsification through betweenness centrality,
and an iterative optimization flowthat solves successive constrained
least-squares optimization problems. TranSEC further uses graph
partitioning tools to enable distributed solution to the problem. We
demonstrate our method on the full Los Angeles metropolitan-area
where aggregated travel time data is available for trips between traffic
analysis zones using a 1280-core supercomputer and visualize
the temporal traffic trends at the street-level."

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
