+++

title = "Two-stage WECC Composite Load Modeling: A Double Deep Q-Learning Networks Approach"
date = 2020-04-15T00:00:00
draft = false

# Authors. Comma separated list, e.g. ["Bob Smith", "David Jones"].
authors = ["Xinan Wang", "__**Yishen Wang**__", "Di Shi", "Jianhui Wang", "Zhiwei Wang"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "*IEEE Transactions on Smart Grid*, 2020."
publication_short = "*IEEE Transactions on Smart Grid*"

# Abstract and optional shortened version.
abstract = "With the increasing complexity of modern power systems, conventional dynamic load modeling with ZIP and induction motors (ZIP + IM) is no longer adequate to address the current load characteristic transitions. In recent years, the WECC composite load model (WECC CLM) has shown to effectively capture the dynamic load responses over traditional load models in various stability studies and contingency analyses. However, a detailed WECC CLM model typically has a high degree of complexity, with over one hundred parameters, and no systematic approach to identifying and calibrating these parameters. Enabled by the wide deployment of PMUs and advanced deep learning algorithms, proposed here is a double deep Q-learning network (DDQN)-based, two-stage load modeling framework for the WECC CLM. This two-stage method decomposes the complicated WECC CLM for more efficient identification and does not require explicit model details. In the first stage, the DDQN agent determines an accurate load composition. In the second stage, the parameters of the WECC CLM are selected from a group of Monte-Carlo simulations. The set of selected load parameters is expected to best approximate the true transient responses. The proposed framework is verified using an IEEE 39-bus test system on commercial simulation platforms."
abstract_short = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
# Associate this publication with one or more of your projects.
# Simply enter your project's folder or file name without extension.
# E.g. projects = ["deep-learning"] references
# content/project/deep-learning/index.md.
# Otherwise, set projects = [].
projects = ["2017_load_modeling"]

# Slides (optional).
# Associate this publication with Markdown slides.
# Simply enter your slide deck's filename without extension.
# E.g. slides = "example-slides" references
# content/slides/example-slides.md.
# Otherwise, set slides = "".
slides = ""

# Tags (optional).
# Set tags = [] for no tags, or use the form tags = ["A Tag", "Another Tag"] for one or more tags.
tags = ["Load Modeling"]

# Links (optional).
url_pdf = "https://ieeexplore.ieee.org/document/9068279"
url_preprint = "https://arxiv.org/abs/1911.04894"
#url_code = ""
#url_dataset = ""
#url_project = ""
#url_slides = ""
#url_video = ""
#url_poster = ""
#url_source = ""

# Custom links (optional).
# Uncomment line below to enable. For multiple links, use the form [{...}, {...}, {...}].
# url_custom = [{name = "Custom Link", url = "http://example.org"}]
# Digital Object Identifier (DOI)
doi = ""

# Does this page contain LaTeX math? (true/false)
math = false

# Featured image
# To use, add an image named featured.jpg/png to your page's folder.

#[image]  
  # Caption (optional)
  #caption = ""
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  #focal_point = "

+++
