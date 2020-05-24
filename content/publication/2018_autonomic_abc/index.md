+++
title = "Autonomic Closure for Turbulent Flows Using Approximate Bayesian Computation"

# Date first published.
date = "2018-01-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Olga Doronina", "Jason Christopher", " Colin Towery", "Peter Hamlington", "Werner Dahm"]

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
publication = "2018 AIAA Aerospace Sciences Meeting"
publication_short = "AIAA SciTech 2018"

# Abstract and optional shortened version.
abstract = ""
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []
tags = ["ABC"]
# Links (optional).
url_pdf = "https://www.researchgate.net/profile/Olga_Doronina/publication/322312942_Autonomic_Closure_for_Turbulent_Flows_Using_Approximate_Bayesian_Computation/links/5b0d7f660f7e9b1ed70089a6/Autonomic-Closure-for-Turbulent-Flows-Using-Approximate-Bayesian-Computation.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

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
image = ""
caption = ""

+++
Autonomic closure is a new technique for achieving physically accurate adaptive closure
of coarse-grained turbulent flow governing equations, such as those solved in large eddy simulations (LES). Although autonomic closure has been shown in recent a priori tests to more
accurately represent unclosed terms than do dynamic versions of traditional LES models, the
optimization step used in the approach introduces large matrices that must be inverted, resulting in high memory usage. In order to reduce memory requirements, here we propose the use
of approximate Bayesian computation (ABC) in place of the optimization step, thereby yielding
an autonomic closure implementation that trades memory-intensive for processor-intensive
computations. These computations can be handled by co-processors such as general purpose
graphical processing units that are becoming increasingly available on petascale supercomputers. In this paper, we outline the formulation of ABC-enabled autonomic closure and present
initial results demonstrating the accuracy of the approach.
