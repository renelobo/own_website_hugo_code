+++
title = "Improving Open Source Face Detection by Combining an Adapted Cascade Classification Pipeline and Active Learning"
date = 2017-08-28T16:39:24+01:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Steven Puttemans","Can Ergun","Toon Goedeme"]

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
publication = "Proceedings of the 12th international joint conference on computer vision, imaging and computer graphics theory and applications"
publication_short = "VISAPP"

# Abstract and optional shortened version.
abstract = "Recent advances in computer vision have almost solved the problem of in the wild face detection, using complex techniques like convolutional neural networks. On the contrary many open source computer vision frameworks like OpenCV have not yet made the switch to these complex techniques and tend to depend on well established algorithms for face detection, like the cascade classification pipeline suggested by Viola and Jones. However the accuracy of these open source face detection models on public datasets like FDDB stays rather low, mainly due to the relatively high number of false positive detections produced. We propose several adaptations to the current existing LBP/AdaBoost cascade classification pipeline of OpenCV. This is done by improving the training sample generation and annotation procedure, and by applying an active learning strategy. This boosts the accuracy of in the wild face detection on the FDDB dataset quite drastically, closing the gap towards the accuracy levels gained by state-of-the-art CNN-based face detectors. The proposed changes allow us to provide a new face detection model to the OpenCV framework, achieving a remarkably high precision at an acceptable recall rate, offering a model that ensures detected faces are actually faces, a critical requirement for further processing pipelines like person identification, etc."
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
url_pdf = "https://lirias.kuleuven.be/bitstream/123456789/560283/2/VISAPP2017.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = "/files/VISIGRAPP2017poster.pdf"
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
image = "face_detection.png"
caption = "Improving the Viola&Jones based face detector integrated in OpenCV."

+++
