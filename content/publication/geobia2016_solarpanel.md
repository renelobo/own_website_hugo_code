+++
title = "Detection of photovoltaic installations in RGB aerial imaging: a comparative study"
date = 2016-09-14T16:39:24+01:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Steven Puttemans","Wiebe Van Ranst","Toon Goedeme"]

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
publication = "Proceedings of the GEOBIA conference"
publication_short = "GEOBIA"

# Abstract and optional shortened version.
abstract = "In this work, we compare four different approaches for detecting photovoltaic installations from RGB aerial images. Our client, an electricity grid administrator, wants to hunt down fraud with unregistered illegal solar panel installations by detecting installations in aerial imagery and checking these against their database of registered installations. The detection of solar panels in these RGB images is a difficult task. Reasons are the relatively low resolution (at 25 cm/pixel an individual solar panel only measures about 9 × 7 pixels), the undiscriminating colour properties of the object (due to in-class variance and specular effects) and the apparent shape variability (rotation and skew due to the different roofs slant angles). Therefore, straightforward object segmentation techniques do not yield a satisfying solution, as proven in this paper. We compared four state-of-the-art object detection approaches for this task. First we experimented with a machine learning object detection technique based on pixel-based support vector machine classification. Secondly we developed an approach using MSER based colour segmentation and shape analysis. Finally a dual approach based on object categorization using the boosted cascade classifier technique of Viola & Jones and the aggregate channel features technique of Doll ́ar et al., is introduced, learning a combination of colour and gradient feature based classifiers from a given training set. We successfully evaluate these four different approaches on a fully labelled test set of a 8000 × 8000 pixel, 4 square km zone containing 315 solar panel installations with in total more than 10.000 individual panels."
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
url_pdf = "https://lirias.kuleuven.be/bitstream/123456789/546313/1/submission_final2.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = "/files/GEOBIA2016.pdf"
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
image = "solar_panels.png"
caption = "Example detections using Viola&Jones (left) and Dollar (right) framework."

+++
