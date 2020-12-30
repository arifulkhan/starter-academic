---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Classifying Immunophenotypes
with Templates from Flow Cytometry"
authors: [Ariful Azad, Arif Khan, Bartek Rajwa, Saumyadipta Pyne & Alex Pothen]
date: 2013-01-01
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-03-16T16:55:16-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ACM Conference of Bioinformatics, Computational
Biology and Biomedical Informatics"
publication_short: "ACm BCB"

abstract: "We describe an algorithm to dynamically classify flow cy-
tometry data samples into several classes based on their im-
munophenotypes. Flow cytometry data consists of fluores-
cence measurements of several proteins that characterize dif-
ferent cell types in blood or cultured cell lines. Each sample
is initially clustered to identify the cell populations present
in it. Using a combinatorial dissimilarity measure between
cell populations in samples, we compute meta-clusters that
correspond to the same cell population across samples. The
collection of meta-clusters in a class of samples then de-
scribes a template for that class. We organize the samples
into a template tree, and use it to classify new samples into
existing classes or create a new class if needed. We dynam-
ically update the templates and their statistical parameters
as new samples are classified, so that the new information
is reflected in the classes. We use our dynamic classifica-
tion algorithm to classify T cells that on stimulation with
an antibody show increased abundance of the proteins SLP-
76 and ZAP-70. These proteins are involved in a platform
that assembles signaling proteins in the immune response.
We also use the algorithm to show that variation in an im-
mune subsystem between individuals is a larger effect than
variation in multiple samples from one individual."

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
