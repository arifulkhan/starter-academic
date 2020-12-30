---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A new 3/2-approximation algorithm for b-Edge Cover Problem"
authors: [Arif Khan & Alex Pothen]
date: 2016-01-01
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-03-16T16:55:23-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "SIAM
Workshop on Combinatorial Scientific Computing"
publication_short: "SIAM CSC"

abstract: "We describe a 3/2-approximation algorithm, LSE, for
computing a b-Edge Cover of minimum weight in a
graph with weights on the edges. The b-Edge Cover
problem is a generalization of the better-known Edge
Cover problem in graphs, where the objective is to
choose a subset C of edges in the graph such that at
least a specified number b(v) of edges in C are incident
on each vertex v. In the weighted b-Edge Cover
problem, we minimize the sum of the weights of the
edges in C. We prove that the LSE algorithm computes
the same b-Edge Cover as the one obtained
by the Greedy algorithm for the problem. However,
the Greedy algorithm requires edges to be sorted by
their effective weights, and these weights need to be updated
after each iteration. These requirements make
the Greedy algorithm sequential and impractical for
massive graphs. The LSE algorithm avoids the sorting
step, and is amenable for parallelization. We implement
the algorithm on a serial machine and compare its
performance against a collection of approximation algorithms
for the b-Edge Cover problem. Our results
show that the LSE algorithm is 3× to 5× faster than
the Greedy algorithm on a serial processor. The approximate
edge covers obtained by the LSE algorithm
have weights greater by at most 17% of the optimal
weight for problems where we could compute the latter.
We also investigate the relationship between the
b-Edge Cover and the b-Matching problems, show
that the latter has a faster implementation since edge
weights are static in this algorithm, and obtain a heuristic
solution for the former from the latter."

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
