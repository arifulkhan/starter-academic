---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Mapping Arbitrarily Sparse Two-body Interactions
on One-dimensional Quantum Circuits"
authors: [Arif Khan, Mahantesh Halappanavar, Tobias Hagge, Karol Kowalski, Alex Pothen & Sriram Krishnamoorthy]
date: 2019-01-01
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-03-17T14:35:58-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE International Conference on High Performance Computing, Data, and Analytics"
publication_short: "HiPC"

abstract: "We consider an assignment problem arising in
Fermionic-swap based mapping of the one-body and two-body
interaction terms in simulating time evolution of a sparse
second-quantized electronic structure Hamiltonian on a quantum
computer. Relative efficiency of different assignment algorithms
depends on the relative costs of performing a swap and computing
a Hamiltonian interaction term. Under the assumption
that the interaction term cost dominates the computation, we
develop an iterative algorithm that uses minimum cost linear
assignment (MINLA) and matching for one-body interactions,
and hypergraph optimal linear arrangement (HOLA) and partial
distance-2 coloring for two-body interactions, to exploit arbitrary
sparsity in the Hamiltonian for efficient computation. Using a set
of 122 problems from computational chemistry, we demonstrate
performance improvements up to 100% relative to the state-ofthe-
art approach for one-body terms and up to 86% utilization
for two-body terms relative to a theoretical peak utilization.
To the best of our knowledge, this is the first study to exploit
arbitrary sparsity in orbital interactions for efficient computation
on one-dimensional qubit connectivity layouts. The proposed
algorithms lay a foundation for extension to map general k-body
interactions that arise in many domains onto generalized qubit
connectivity layouts available in current and future quantum
systems."

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
