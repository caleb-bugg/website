+++
title = "Sparse Reduced Computation: Enabling Mining of Massively-Large Data Sets"
date = 2016-12-15T12:00:22-07:00
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
publication = "International Conference on Pattern Recognition Applications and Methods"
publication_short = ""

# Abstract and optional shortened version.
abstract = "Machine learning techniques that rely on pairwise similarities have proven to be leading algorithms for classification. Despite their good and robust performance, similarity-based techniques are rarely chosen for largescale data mining because the time required to compute all pairwise similarities grows quadratically with the size of the data set. To address this issue of scalability, we introduced a method called sparse computation, which efficiently generates a sparse similarity matrix that contains only significant similarities. Sparse computation achieves significant reductions in running time with minimal and often no loss in accuracy. However, for massively-large data sets even such a sparse similarity matrix may lead to considerable running times. In this paper, we propose an extension of sparse computation called sparse-reduced computation that not only avoids computing very low similarities but also avoids computing similarities between highly-similar or identical objects by compressing them to a single object. Our computational results show that sparse-reduced computation allows highly-accurate classification of data sets with millions of objects in seconds."
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
url_pdf = "files/sparse-reduced-computation.pdf"
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
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

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
