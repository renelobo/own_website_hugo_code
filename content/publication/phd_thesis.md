+++
title = "Exploiting scene constraints to improve object detection algorithms for industrial applications"
date = 2017-12-13T16:39:24+01:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Steven Puttemans"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["3"]

# Publication name and optional abbreviated version.
publication = "Doctoral Manuscript"
publication_short = ""

# Abstract and optional shortened version.
abstract = "State-of-the-art object detection algorithms are designed to be heavily robust against scene and object variations like illumination changes, occlusions, scale changes, orientation differences, background clutter and object intra-class variability. However, in industrial machine vision applications, where objects with variable appearance have to be detected, many of these variations are in fact constant and can be seen as scene specific constraints on the detection problem. These scene constraints can be used to reduce the enormous search space for object candidates, and thus speed up the actual detection process and improve it’s accuracy. In this PhD we will explore the possibility to use scene specific constraints of industrial object detection tasks to influence three main aspects of object detection algorithms: 1. Reduce the amount of training data needed. We will try to reduce the required amount of manually annotated training data as much as possible. | 2. Increase the speed of the detection process. Since we are working in an industrial application related context, maintaining real-time performance is a hard constraint. | 3. Reduce the amount of false positive and false negative detections. We aim at building object detection algorithms that are able to detect all objects in a given image or video stream with a high certainty. Moreover, we will propose steps to simplify the training process under such scene constraints, used for creating object specific models. For this we look into techniques like active learning and data augmentation, in order to heavily reduce the amount of manual input required by the algorithm."
abstract_short = "In this PhD dissertation we explore the possibility to use scene-specific constraints of industrial object detection tasks to influence three main aspects of object detection algorithms: the amount of training data, the speed of the detection process and the amount of FP/FN detections. Moreover, we propose steps to simplify the training process using techniques like active learning and data augmentation."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://lirias.kuleuven.be/bitstream/123456789/597085/2/compressed_dissertation_steven_puttemans.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = "files/public_defense.pdf"
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
