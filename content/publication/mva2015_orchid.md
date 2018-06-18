+++
title = "Visual Detection and Species Classification of Orchid Flowers"
date = 2015-05-12T16:39:24+01:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Steven Puttemans","Toon Goedeme"]

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
publication = "Proceedings of the international conference on machine, vision and applications"
publication_short = "MVA"

# Abstract and optional shortened version.
abstract = "The goal of this research is to investigate the possibility of using object categorization and object classification techniques in an industrial context with a very limited set of training data. As an industrial application of the proposed techniques we investigate the case of orchid flower detection and orchid species classification in an orchid packaging plant. Due to their large variety of colors and patterns, these orchid flowers are very hard to detect with classic segmentation based techniques but form an ideal test case for object categorization techniques. Due to the limited amount of training data available, we aim at building a system with close to no false positive detections but guaranteeing that each orchid plant still returns a single flower detection. Subsequently the detected flowers are passed towards a classification system of linear binary SVM classifiers trained on visual characteristics of the flowers. To increase the classification success rate, we combined results of single flowers, using majority voting, to reach an orchid plant based classification. The complete pipeline is optimized by effectively using the industrial application specific knowledge of the setup. By implementing this approach we prove that industrial object categorization and classification with high accuracy is possible, even if only a small training dataset is available."
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
url_pdf = "https://lirias.kuleuven.be/bitstream/123456789/499870/1/14-22.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = "/files/MVA2015poster.pdf"
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
image = "orchid.png"
caption = "Example of orchid flower detections."

+++
