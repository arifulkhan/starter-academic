---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Distributed Louvain Algorithm for Graph
Community Detection."
authors: [Sayan Ghosh, Mahantesh Halappanavar, Antonino Tumeo, Ananth Kalyanaraman, Hao Lu, Daniel
Chavarria-Miranda, Arif Khan & Assefaw Gebremedhin]
date: 2017-01-01
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-03-16T16:55:29-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE International Parallel & Distributed Processing Symposium"
publication_short: "IPDPS"

abstract: "In most real-world networks, the nodes/vertices tend
to be organized into tightly-knit modules known as communities
or clusters, such that nodes within a community are more likely
to be “related” to one another than they are to the rest of
the network. The goodness of partitioning into communities is
typically measured using a well known measure called modularity.
However, modularity optimization is an NP-complete problem. In
2008, Blondel, et al. introduced a multi-phase, iterative heuristic
for modularity optimization, called the Louvain method. Owing
to its speed and ability to yield high quality communities, the
Louvain method continues to be one of the most widely used
tools for serial community detection.
In this paper, we present the design of a distributed memory
implementation of the Louvain algorithm for parallel community
detection. Our approach begins with an arbitrarily partitioned
distributed graph input, and employs several heuristics to
speedup the computation of the different steps of the Louvain
algorithm. We evaluate our implementation and its different
variants using real-world networks from various application
domains (including internet, biology, social networks). Our
MPI+OpenMP implementation yields about 7x speedup (on
4K processes) for soc-friendster network (1.8B edges) over a
state-of-the-art shared memory multicore implementation (on
64 threads), without compromising output quality. Furthermore,
our distributed implementation was able to process a larger
graph (uk-2007; 3.3B edges) in 32 seconds on 1K cores (64
nodes) of NERSC Cori, when the state-of-the-art shared memory
implementation failed to run due to insufficient memory on a
single Cori node containing 128 GB of memory."

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
