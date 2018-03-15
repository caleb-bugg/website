+++
title = "High-performance geometric algorithms for sparse computation in big data analytics"
date = 2017-12-10T12:00:09-07:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Philipp Baumann", "Dorit S. Hochbaum", "Quico Spaen"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "IEEE International Conference on Big Data"
publication_short = ""

# Abstract and optional shortened version.
abstract = 'Several leading supervised and unsupervised machine learning algorithms require as input similarities between objects in a data set. Since the number of pairwise similarities grows quadratically with the size of the data set, it is computationally prohibitive to compute all pairwise similarities for large-scale data sets. The recently introduced methodology of “sparse computation” resolves this issue by computing only the relevant similarities instead of all pairwise similarities. To identify the relevant similarities, sparse computation efficiently projects the data onto a low-dimensional space where a similarity is considered relevant if the corresponding objects are close in this space. The relevant similarities are then computed in the original space. Sparse computation identifies close pairs by partitioning the low-dimensional space into grid blocks, and considering objects close if they fall in the same or adjacent grid blocks. This guarantees that all pairs of objects that are within a specified L∞ distance are identified as well as some pairs that are within twice this distance. For very large data sets, sparse computation can have high runtime due to the enumeration of pairs of adjacent blocks. We propose here new geometric algorithms that eliminate the need to enumerate adjacent blocks. Our empirical results on data sets with up to 10 million objects show that the new algorithms achieve a significant reduction in runtime. The algorithms have applications in large-scale computational geometry and (approximate) nearest neighbor search. Python implementations of the proposed algorithms are publicly available.'
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "files/geometric-algs-sparse-computation.pdf"
url_preprint = ""
url_code = "https://github.com/hochbaumGroup/sparsecomputation"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "Experiment code", url = "https://github.com/quic0/sparse-experiments"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
