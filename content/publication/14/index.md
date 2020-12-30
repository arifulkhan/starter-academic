---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Adaptive Anonymization of Data using b-Edge Cover"
authors: [Arif Khan, Krzysztof Choromanski, Alex Pothen, S M Ferdous, Mahantesh Halappanavar & Antonino Tumeo]
date: 2018-01-01
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-03-16T16:55:36-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The International Conference
for High Performance computing, Network, Storage and Analysis"
publication_short: "Supercomputing"

abstract: "We explore the problem of sharing data that pertains
to individuals with anonymity guarantees, where each user
requires a desired level of privacy. We propose the first sharedmemory
as well as distributed memory parallel algorithms for the
adaptive anonymity problem that achieves this goal, and produces
high quality anonymized datasets.
The new algorithm is based on an optimization procedure
that iteratively computes weights on the edges of a dissimilarity
matrix, and at each iteration computes a minimum weighted
b-Edge Cover in the graph. We describe how a 2-approximation
algorithm for computing the b-Edge Cover can be used to solve
the adaptive anonymity problem in parallel.
We are able to solve adaptive anonymity problems with
hundreds of thousands of instances and hundreds of features
on a supercomputer in under five minutes. Our algorithm scales
up to 8K cores on a distributed memory supercomputer, while
also providing good speedups on shared memory multiprocessors.
On smaller problems where an a Belief Propagation algorithm
is feasible, our algorithm is two orders of magnitude faster."

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
