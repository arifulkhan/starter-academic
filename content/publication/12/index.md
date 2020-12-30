---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Parallel Algorithms through Approximation: b-Edge Cover."
authors: [Arif Khan, Alex Pothen & S M Ferdous]
date: 2017-01-01
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-03-16T16:55:31-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE International Parallel & Distributed Processing Symposium"
publication_short: "IPDPS"

abstract: "Abstract—We describe a paradigm for designing parallel
algorithms via approximation, and illustrate it on the
b-EDGE COVER problem. A b-EDGE COVER of minimum weight
in a graph is a subset C of its edges such that at least a
specified number b(v) of edges in C is incident on each vertex
v, and the sum of the edge weights in C is minimum. The
GREEDY algorithm and a variant, the LSE algorithm, provide
3=2-approximation guarantees in the worst-case for this
problem, but these algorithms have limited parallelism. Hence
we design two new 2-approximation algorithms with greater
concurrency. The MCE algorithm reduces the computation of a
b-EDGE COVER to that of finding a b0-MATCHING, by exploiting
the relationship between these subgraphs in an approximation
context. The S-LSE is derived from the LSE algorithm using
static edge weights rather than dynamically computing effective
edge weights. This relaxation gives S-LSE a worse approximation
guarantee but makes it more amenable to parallelization.
We prove that both the MCE and S-LSE algorithms compute
the same b-EDGE COVER with at most twice the weight of the
minimum weight edge cover. In practice, the 2-approximation
and 3=2-approximation algorithms compute edge covers of
weight within 10% the optimal. We implement three of the
approximation algorithms, MCE, LSE, and S-LSE, on shared
memory multi-core machines, including an Intel Xeon and an
IBM Power8 machine with 8 TB memory. The MCE algorithm
is the fastest of these by an order of magnitude or more. It
computes an edge cover in a graph with billions of edges in 20
seconds using two hundred threads on the IBM Power8. We
also show that the parallel depth and work can be bounded
for the SUITOR and b-SUITOR algorithms when edge weights
are random."

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
