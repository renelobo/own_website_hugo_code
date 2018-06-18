+++
title = "Automated Walking Aid Detector Based on Indoor Video Recordings"
date = 2015-08-15T16:39:24+01:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Steven Puttemans","Greet Baldewijns","Tom Croonenborghs","Bart Vanrumste","Toon Goedeme"]

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
publication = "Proceedings of the 37th annual international conference of the IEEE engineering in medicine and biology society"
publication_short = "EMBC"

# Abstract and optional shortened version.
abstract = "Due to the rapidly aging population, developing automated home care systems is a very important step in taking care of elderly people. This will enable us to automatically monitor the health of senior citizens in their own living environment and prevent problems before they happen.  One of the challenging tasks is to actively monitor walking habits of elderlies, who alternate between the use of different walking aids, and to combine this with automated fall risk assessment systems. We propose a camera based system that uses object categorization techniques to robustly  detect walking aids, like a walker, in order to improve the classification of the fall risk. By  automatically integrating the application specific scenery knowledge like camera position and used  walker type, we succeed in detecting walking aids within a single frame with an accuracy of 68% for  trajectory A and 38% for trajectory B. Furthermore, compared to current state of the art detection systems, we use a rather limited set of training data to achieve this accuracy and thus create a system that is easily adaptable for other applications. Moreover, we applied spatial constraints between detections to optimize the object detection output and to limit the amount of false positive detections. Finally, we evaluate the output on a walking sequence base, leading up to a 92.3% correct classification rate of walking sequences. It can be noted that adapting this approach to other  walking aids, like a walking cane, is quite straightforward and opens up the door for many future  applications."
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
url_pdf = "https://lirias.kuleuven.be/bitstream/123456789/499873/1/EMBC2015.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = "/files/EMBC2015poster.pdf"
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
image = "walker.png"
caption = "Example of masking and walking aid detections."

+++
