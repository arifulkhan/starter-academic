---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Multithreaded Algorithm for
Network Alignment via Approximate Matching."
authors: [Arif Khan, David Gleich, Mahantesh Halappanavar & Alex Pothen]
date: 2012-09-09
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-03-16T16:55:14-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The International Conference for High Performance
computing, Network, Storage and Analysis"
publication_short: "Supercomputing"

abstract: "Network alignment is an optimization problem to
find the best one-to-one map between the vertices of a pair
of graphs that overlaps as many edges as possible. It is a
relaxation of the graph isomorphism problem and is closely
related to the subgraph isomorphism problem. The best current
approaches are entirely heuristic and iterative in nature. They
generate real-valued heuristic weights that must be rounded to
find integer solutions. This rounding requires solving a bipartite
maximum weight matching problem at each iteration in order to
avoid missing high quality solutions. We investigate substituting
a parallel, half-approximation for maximum weight matching
instead of an exact computation. Our experiments show that
the resulting difference in solution quality is negligible. We
demonstrate almost a 20-fold speedup using 40 threads on an
8 processor Intel Xeon E7-8870 system and now solve real-world
problems in 36 seconds instead of 10 minutes."

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
