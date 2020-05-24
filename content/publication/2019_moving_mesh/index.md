+++
title = "Simulation of aerodynamics of a moving body prescribed by immersed boundaries on dynamically adaptative unstructured mesh"

# Date first published.
date = "2019-01-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["I. V. Abalakin", "P. A. Bakhvalov", "O. A. Doronina", "N. S. Zhdanova", "T. K. Kozubskaya"]

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
publication = "Mathematical Models and Computer Simulations"
publication_short = "Matem. Mod."

# Abstract and optional shortened version.
abstract = ""
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

# Links (optional).
url_pdf = "pdfs/2018_Moving_mesh.pdf"
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

The paper is devoted to the development of integrated technology for numerical simulation of aerodynamics of moving bodies prescribed by the immersed boundaries method on unstructured meshes. The dynamic mesh adaptation is used to improve the accuracy. The mesh adaptation method in use is built on the base of nodes-redistribution techniques. Its implementation implies the solution of additional differential equation governing the mesh movement. The method allows to keep a topology of the initial mesh and does not increase significantly the computational costs. The technology is developed for 2D formulations and verified on model problems.
