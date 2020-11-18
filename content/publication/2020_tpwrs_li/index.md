+++

title = "Real-time Energy Disaggregation at Substations with Behind-the-Meter Solar Generation"
date = 2020-11-03T00:00:00
draft = false

# Authors. Comma separated list, e.g. ["Bob Smith", "David Jones"].
authors = ["Wenting Li", "Ming Yi", "Meng Wang", "__**Yishen Wang**__", "Di Shi", "Zhiwei Wang"]

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
publication = "*IEEE Transactions on Power Systems*, 2020."
publication_short = "*IEEE Transactions on Power Systems*"

# Abstract and optional shortened version.
abstract = "Energy Disaggregation at substations (EDS) is challenging because measurements are mostly aggregated over multiple types of loads, and the existence of some loads such as behind-the-meter solar is unknown to the operator. This paper for the first time addresses this so-called partial labels issue in energy disaggregation and develops a model-free EDS method to separate individual loads, including BTM solar, from the total energy consumption in real-time. Our approach learns the patterns of all loads offline from recorded historical datasets with partial labels. Compared with conventional model-free methods that require either pure measurements of each load for training or full labels of each training sample, our method can extract load patterns from partially labeled aggregated data and thus, is more applicable to practical scenarios and alleviates the annotation burden for the operator. Specifically, we propose to solve a new dictionary learning problem, where column-sparsity and incoherence regularization terms are added to identify unlabeled loads and learn distinctive patterns of each load. In real-time disaggregation, our approach solves an improved sparse decomposition problem where one decomposes the aggregated measurements as a linear combination of some representative recorded measurements with known disaggregation learned in the offline stage. Numerical experiments are reported to validate our method."
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
url_pdf = "https://ieeexplore.ieee.org/document/9247468"
#url_preprint = "https://arxiv.org/abs/1911.04894"
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
