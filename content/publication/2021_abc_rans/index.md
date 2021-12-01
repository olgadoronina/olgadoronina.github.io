---
title: "Parameter Estimation for Reynolds-Averaged Navier--Stokes Models Using Approximate Bayesian Computation"
date: "2021-08-01"
authors:
  - olga_doronina
  - "Scott M. Murman"
  - "Peter E. Hamlington"

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types: ["2"]

# Publication name and optional abbreviated version.
publication: "AIAA Journal"
publication_short: "AIAA Journal"

# Abstract and optional shortened version.
abstract: "We use approximate Bayesian computation (ABC) to estimate unknown parameter values, 
as well as their uncertainties, in Reynolds-averaged Navier-Stokes (RANS) simulations of turbulent flows. 
The ABC method approximates posterior distributions of model parameters, but does not require the direct computation, 
or estimation, of a likelihood function. This method thus enables relatively simple and flexible parameter 
estimation for complex models and a wide range of reference data. In this paper, we describe the ABC approach, 
including the use of a calibration step, adaptive proposal, 
and Markov chain Monte Carlo (MCMC) technique to accelerate the parameter estimation, resulting in 
an ABC approach with improved MCMC, denoted ABC-IMCMC. As a test of the classic ABC rejection algorithm 
and ABC-IMCMC, we estimate parameters in a nonequilibrium RANS model using reference data from direct 
numerical simulations of periodically sheared homogeneous turbulence. We then demonstrate the use of ABC-IMCMC 
to estimate parameters in the Menter shear-stress-transport (SST) model using experimental reference data for 
an axisymmetric transonic bump. We show that the accuracy of the SST model for this test case can be improved 
using ABC-IMCMC, indicating that ABC-IMCMC is a promising method for the calibration of RANS models using a wide 
range of reference data."
abstract_short: ""

projects:
  - ABC_turbulence_modeling

software: 
    - turbabc

# Links (optional).
#- name: Custom Link
#  url: http://example.org
#url_pdf: "https://arxiv.org/pdf/2005.13993.pdf"
#url_preprint: ""
#url_code: ""
#url_dataset: = ""
#url_project: = ""
#url_slides: = ""
#url_video: ""
#url_poster: ""
#url_source: ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom:[{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
#math: true
# Does the content use source code highlighting?
#highlight: true

#tags:
#- Source Themes
featured: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
# focal_point: ""
# preview_only: false

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""

---
