+++
title = "A Novel Technique Based on Deep Learning and a Synthetic Target Database for Classification of Urban Areas in PolSAR Data"

# Date first published.
date = "2013-07-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Shaunak De", "Lorenzo Bruzzone", "Avik Bhattacharya", "Francesca Bovolo", "Subhasis Chaudhuri"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing"

# Abstract and optional shortened version.
abstract = "The classification of urban areas in polarimetric synthetic aperture radar (PolSAR) data is a challenging task. Moreover, urban structures oriented away from the radar line of sight pose an additional complexity in the classification process. The characterization of such areas is important for disaster relief and urban sprawl monitoring applications. In this paper, a novel technique based on deep learning is proposed, which leverages a synthetic target database for data augmentation. The PolSAR dataset is rotated by uniform steps and collated to form a reference database. A stacked autoencoder network is used to transform the information in the augmented dataset into a compact representation. This significantly improves the generalization capabilities of the network. Finally, the classification is performed by a multilayer perceptron network. The modular architecture allows for easy optimization of the hyperparameters. The synthetic target database is created and the classification performance is evaluated on an Lband airborne UAVSAR dataset and L-band space-borne ALOS-2 dataset acquired over San Francisco, USA. The proposed technique shows an overall accuracy of 91.3%. An improvement over state-of-the-art techniques is achieved, especially in urban areas rotated away from the radar line of sight."
abstract_short = "A novel physics-based deep learning technique was proposed which overcomes the traditional limitations of training such networks by augmenting the input information from target simulations."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Links (optional).
url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = "http://ieeexplore.ieee.org/abstract/document/8068203/"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "headers/bubbles-wide.jpg"
caption = "Classification of Urban Areas in PolSAR Data"

+++

Further details on your publication can be written here using *Markdown* for formatting. This text will be displayed on the Publication Detail page.
