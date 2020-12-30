---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Efficient approximation algorithms for weighted
b-Matching. SIAM Journal on Scientific Computing"
authors: [Arif Khan, Alex Pothen, Mostofa Patwary, Nadathur Satish, Narayanan Sunderam, Fredrik Manne, Mahantesh Halappanavar & Pradeep Dubey]
date: 2015-01-01
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-03-16T16:55:20-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "SIAM Journal on Scientific Computing"
publication_short: "SIAM SISC"

abstract: "weight in a graph with weights on the edges. b-Matching is a generalization of the
well-known Matching problem in graphs, where the objective is to choose a subset of M edges in
the graph such that at most a specified number b(v) of edges in M are incident on each vertex v.
Subject to this restriction we maximize the sum of the weights of the edges in M. We prove that the
b-Suitor algorithm computes the same b-Matching as the one obtained by the greedy algorithm
for the problem. We implement the algorithm on serial and shared-memory parallel processors, and
compare its performance against a collection of approximation algorithms that have been proposed
for the Matching problem. Our results show that the b-Suitor algorithm outpeforms the Greedy
and Locally Dominant edge algorithms by one to two orders of magnitude on a serial processor. The
b-Suitor algorithm has a high degree of concurrency, and it scales well up to 240 threads on a shared
memory multiprocessor. The b-Suitor algorithm outperforms the Locally Dominant edge algorithm
by a factor of fourteen on 16 cores of an Intel Xeon multiprocessor."

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
