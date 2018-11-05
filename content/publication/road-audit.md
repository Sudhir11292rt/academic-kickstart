+++
title = "Cityscale Road Audit System using Deep Learning"
date = "2018-05-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Sudhir Yarram", "Girish Varma", '''<a href="https://faculty.iiit.ac.in/~jawahar/">C V Jawahar</a>''']

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "<span style='color: orange'>JTPF Novel Technology Paper Award Finalist, Oral Presentation</span><br/><a href='https://www.iros2018.org//'>International Conference on Intelligent Robots (<strong>IROS</strong>)</a>"
#publication_short = "In *ACPR*"

# Abstract and optional shortened version.
abstract = ""

# Featured image thumbnail (optional)
image_preview = "img/audit_6.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["semantic-segmentation"]

# Links (optional).
url_pdf = "https://drive.google.com/file/d/1Z0uKgCJ_1GTGAQcE4FS_faXEqpShWAs1/view?usp=sharing" 
#url_preprint = "https://arxiv.org/abs/1711.08757"
#url_code = "#"
url_dataset = "https://cvit.iiit.ac.in/images/Projects/city-scale-roadaudit/release_version_v1.zip"
url_project = "https://cvit.iiit.ac.in/research/projects/cvit-projects/city-scale-road-audit"
url_slides = "https://drive.google.com/file/d/1VNFPglT0HWi5n9A2WSPUI_SGm7bXmN5W/view?usp=sharing"
url_video = "https://drive.google.com/file/d/1dbPlhSsyIBjd7SaFuhcjy1EoQX1Y1mhP/view?usp=sharing"
#url_poster = "#"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
#math = true

# Does the content use source code highlighting?
#highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "img/audit.png"
#caption = "My caption :smile:"

+++
Deep CNNs for semantic segmentation have high memory and run time requirements. Various approaches have been proposed to make CNNs efficient like grouped, shuffled, depth-wise separable convolutions. We study the effectiveness of these techniques on a real-time semantic segmentation architecture like ERFNet for improving runtime by over 5X. We apply these techniques to CNN layers partially or fully and evaluate the testing accuracies on Cityscapes dataset.  We obtain accuracy vs parameters/FLOPs trade offs, giving accuracy scores for models that can run under specified runtime budgets. We further propose a novel training procedure which starts out with a dense convolution but gradually evolves towards a grouped convolution. We show that our proposed training method and efficient architecture design can improve accuracies by over 8% with depthwise separable convolutions applied on the encoder of ERFNet and attaching a light weight decoder. This results in a model which has a 5X improvement in FLOPs while only suffering a 4% degradation in accuracy with respect to ERFNet.
