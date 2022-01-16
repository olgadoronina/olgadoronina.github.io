+++
title = "Turbulence Model Development Using Markov Chain Monte Carlo Approximate Bayesian Computation"

# Date first published.
date = "2019-01-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["olga_doronina"," Colin Towery",  "Jason Christopher", "Ian Grooms", "Peter Hamlington"]

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
publication = "AIAA Scitech 2019 Forum"
publication_short = "AIAA SciTech 2019"

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
projects = ["ABC_turbulence_modeling"]

# Links (optional).
url_pdf = "pdfs/2019_ABC_rans.pdf"
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

Approximate Bayesian computation (ABC) is used in this study to estimate unknown model parameter values, as well as uncertainties, in a nonequilibrium anisotropy closure for Reynolds averaged Navier-Stokes (RANS) simulations. The ABC approach does not require the direct computation of a likelihood function, thereby enabling substantially faster estimation of un-known parameters as compared to full Bayesian analyses. The approach also naturally provides uncertainties in parameter estimates, avoiding the artificial certainty implied by optimization methods for determining unknown parameters. Details of the ABC approach are described, including the use of a Markov chain Monte Carlo technique to accelerate the parameter estimation, and unknown model parameters are estimated based on turbulence kinetic energy reference data for four impulsively sheared homogeneous turbulence test cases, as well as periodically sheared homogeneous turbulence for five different shearing frequencies. The ABC method is shown to yield parameter values for the nonequilibrium anisotropy closure that  provide good agreement between model results and the reference data.
