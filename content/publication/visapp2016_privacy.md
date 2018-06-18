+++
title = "Safeguarding Privacy by Reliable Automatic Blurring of Faces in Mobile Mapping Images"
date = 2016-02-27T16:39:24+01:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Steven Puttemans","Stef Van Wolputte","Toon Goedeme"]

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
publication = "Proceedings of the 11th international joint conference on computer vision, imaging and computer graphics theory and applications"
publication_short = "VISAPP"

# Abstract and optional shortened version.
abstract = "When capturing images in the wild containing pedestrians, privacy issues remain a concern for industrial applications. Our application, collecting cycloramic mobile mapping data in crowded environments, is an example of this. If the data is processed and accessed by third parties, privacy of individuals inside the data must be ensured. This is where pedestrian detectors come into play, used to detect individuals and make them privacy safe through blurring. However the problem of undesired false positive detections, typical for pedestrian detectors and unavoidable, still leaves undesired areas of the images being blurred. We tackled this problem by using application specific scene constraints, under the form of a scale-space mapping based on the pedestrian detector’s training data, combined with reducing the field of interest and a specific false positive elimination classifier. Furthermore we applied a technique called soft blurring to avoid the artificial look of simply applying a Gaussian blur to the found detections, which resulted in an effective full-automatic masking pipeline for privacy safeguarding in mobile mapping images. We prove that we can use pre-trained pedestrian detection models, but, based on a limited amount of application-specific annotations, we can boost the detection accuracy enormously by exploiting scene specific constraints."
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
url_pdf = "https://lirias.kuleuven.be/bitstream/123456789/516446/2/VISAPP2016.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = "/files/VISIGRAPP2016.pdf"
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
image = "masking.png"
caption = "Applying data learned rules for rejecting false detections."

+++
