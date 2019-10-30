+++

title = "Residential Customer Baseline Load Estimation Using Stacked Autoencoder with Pseudo-load Selection"
date = 2019-10-10T00:00:00
draft = false

# Authors. Comma separated list, e.g. ["Bob Smith", "David Jones"].
authors = ["Xinan Wang", "__**Yishen Wang**__", "Jianhui Wang", "Di Shi"]

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
publication = "*IEEE Journal on Selected Areas in Communications*, early access, 2019."
publication_short = "*IEEE J-SAC*"

# Abstract and optional shortened version.
abstract = "Accurate estimation of customer baseline load (CBL) is a key factor in the successful implementation of demand response (DR). CBL technologies implemented at utilities currently are primarily designed for large industrial and commercial customers. The U.S. Federal Energy Regulatory Commission (FERC) order 745 states that DR owners, including residential customers, can sell their load reduction in the wholesale market. However, since residential load is random and un-schedulable, this tends to inherently degrade the effectiveness of existing CBL technologies. In this paper, a novel SAE based CBL method for residential customers that uses the data reconstruction capability of a stacked autoencoder (SAE) is described. In the model, two SAEs are synchronously trained—one SAE generates a pseudo-load pool and the second one is used to select a pseudo-load to reconstruct a residential CBL. A support vector machine (SVM) classifier is self-trained to conduct the pseudo-load selection. The proposed strategy is validated using a real data set consisting of 328 residential customers’ smart meter readings. Benchmarks from other machine learning techniques and existing CBL methods are compared with the proposed method. Test results show that the accuracy of the residential CBL reconstruction significantly improves when compared with existing methods, such as HighXofY and exponential moving average."
abstract_short = ""

# Is this a selected publication? (true/false)
selected = false

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
url_pdf = ""
url_preprint = ""
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
