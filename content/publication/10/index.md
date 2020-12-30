---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Designing Scalable b-MATCHING Algorithms on
Distributed Memory Multiprocessors by
Approximation"
authors: [Arif Khan, Alex Pothen, Mostofa Patwary, Nadathur Satish, Narayanan Sunderam, Mahantesh
Halappanavar & Pradeep Dubey]
date: 2016-01-01
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-03-16T16:55:27-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The International Conference for High Performance computing, Network,
Storage and Analysis"
publication_short: "Supercomputing"

abstract: "b-MATCHING is a subset of edges M such that at
most b(v) edges in M are incident on each vertex v, where b(v) is
specified. We present a distributed-memory parallel algorithm,
b-SUITOR, that computes a b-MATCHING with more than half
the maximum weight in a graph with weights on the edges. The
approximation algorithm is designed to have high concurrency
and low time complexity. We organize the implementation of
the algorithm in terms of asynchronous supersteps that combine
computation and communication, and balance the computational
work and frequency of communication to obtain high
performance. Since the performance of the b-SUITOR algorithm
is strongly influenced by communication, we present several
strategies to reduce the communication volume. We implement
the algorithm using a hybrid strategy where inter-node communication
uses MPI and intra-node computation is done with
OpenMP threads. We demonstrate strong and weak scaling of
b-SUITOR up to 16K processors on two supercomputers at
NERSC. We compute a b-MATCHING in a graph with 2 billion
edges in under 4 seconds using 16K processors."

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
