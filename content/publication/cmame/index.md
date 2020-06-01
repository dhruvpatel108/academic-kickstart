+++
title = "Circumventing the Solution of Inverse Problems in Mechanics through Deep Learning: Application to Elasticity Imaging"
date = 2017-07-05
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Dhruv Patel", "Raghav Tibrewala", "Adriana Vega", "Li Dong", "Nicholas Hugenberg", "Assad Oberai"]

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
publication = "Computer Methods in Applied Mechanics and Engineering"
publication_short = "CMAME"

# Abstract and optional shortened version.
abstract = "The ability to make decisions based on quantities of interest that depend on variables inferred from measurement finds application in different fields of mechanics and physics. The evaluation of the inferred variables, and hence the quantities of interest, from the measurement typically requires the solution of an inverse problem. For example, in medical imaging the elastic heterogeneity of a tumor and its nonlinear elastic response can be used to distinguish benign tumors from their malignant counterparts. These images of linear and nonlinear elastic parameters of tissue are typically obtained by using a measured displacement field and solving a complex inverse elasticity problem. In this paper we consider circumventing the solution of the inverse problem by using measured displacements as input to a deep convolutional neural network (CNN) and training it to classify tumors on the basis of their elastic heterogeneity and nonlinearity. For a simple, 5-layer CNN trained with 8,000 samples for heterogeneity, and a 4-layer CNN trained with 4,000 samples for nonlinear elasticity we report classification accuracies in the range of 99.7% - 99.9%. The training and testing data are both obtained from the forward solution of finite element models of samples. We also analyze the weights of the trained model to understand the process through which the network extracts features of elastic moduli from the input displacement images. Finally, we apply the nonlinear elasticity classifier, which is trained entirely using simulated data, to displacement images obtained from ten patients with breast lesions and note that it correctly classifies eight out of ten cases. This application illustrates how data from physics-based models can be used in improving the performance of a data-driven algorithm in data-sparse scenarios."

abstract_short = "Learning-based framework to bypass the solution of inverse problems in mechanics."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://www.sciencedirect.com/science/article/pii/S0045782519302579"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = "wccm_final.pdf"
url_video = ""
url_poster = "poster.pdf"
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = true

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "featured.gif"
caption = ""

+++
