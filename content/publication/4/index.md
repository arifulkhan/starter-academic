---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Multithreaded Algorithms for Maximum Matching in Bipartite Graphs."
authors: [Ariful Azad, Mahantesh Halappanavar, Sivasankaran Rajamanickam, Erik G. Boman, Arif Khan
& Alex Pothen]
date: 2012-07-07
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-03-16T16:55:12-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE
International Parallel & Distributed Processing Symposium"
publication_short: "IPDPS"

abstract: "We design, implement, and evaluate algorithms for
computing a matching of maximum cardinality in a bipartite
graph on multi-core and massively multithreaded computers. As
computers with larger number of slower cores dominate the commodity
processor market, the design of multithreaded algorithms
to solve large matching problems becomes a necessity. Recent
work on serial algorithms based on searching for augmenting
paths for this problem have shown that their performance is
sensitive to the order in which the vertices are processed for
matching. In a multithreaded environment, imposing a serial
order in which vertices are considered for matching would lead to
loss of concurrency and performance. But this raises the question:
Would parallel matching algorithms on multithreaded machines
improve performance over a serial algorithm?
We answer this question in the affirmative. We report efficient
multithreaded implementations of two key algorithms (Hopcroft-
Karp based on breadth-first-search, and Pothen-Fan based on
depth-first-search) and their variants, combined with the Karp-
Sipser initialization algorithm. We report extensive results and
insights using three shared-memory platforms (a 48-core AMD
Opteron, a 32-core Intel Nehalem, and a 128-processor Cray
XMT) on a representative set of real-world and synthetic graphs.
To the best of our knowledge, this is the first extensive study of
augmentation-based parallel algorithms for bipartite cardinality
matching."

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
