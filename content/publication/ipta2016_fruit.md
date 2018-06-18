+++
title = "Automated visual fruit detection for harvest estimation and robotic harvesting"
date = 2016-12-12T16:39:24+01:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Steven Puttemans","Yasmin Vanbrabant","Laurent Tits","Toon Goedeme"]

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
publication = "Proceedings of the 6th international conference on image processing theory, tools and applications"
publication_short = "IPTA"

# Abstract and optional shortened version.
abstract = "Fully automated detection and localisation of fruit in orchards is a key component in creating automated robotic harvesting systems, a dream of many farmers around the world to cope with large production and personnel costs. In recent years a lot of research on this topic has been performed, using basic computer vision techniques, like colour based segmentation, as a suggested solution. When not using standard RGB cameras, research tends to resort to other sensors, like hyper spectral or 3D. Recent advances in computer vision present a broad range of advanced object detection techniques that could improve the quality of fruit detection from RGB images drastically. We suggest to use a object categorisation technique based on a boosted cascade of weak classifiers to implement a fully automated semi-supervised fruit detector and demonstrate it on both strawberries and apples. Compared to existing techniques we improve fruit detection, mainly in the case of fruit clusters, using a supervised machine learning instead of hand crafting image filters specific to the application. Moreover we integrate application specific colour information to ensure a more stable output of our fully automated detection algorithm. The developed technique is validated on strawberries and apples and is proven to have large benefits in the field of automated harvest and crop estimation."
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
url_pdf = "https://lirias.kuleuven.be/bitstream/123456789/546316/3/IPTA2016_submission_camera_ready.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = "/files/IPTA2016SPU.pdf"
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
image = "fruit_detection.png"
caption = "Example of trained strawberry (left) and apple (right) detectors."

+++
