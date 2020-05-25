---
title: Approximate Bayesian Computation for Parameter Estimation in RANS Turbulence Models
event: 72nd Annual Meeting of the APS Division of Fluid Dynamics
event_url: https://www.apsdfd2019.org/

location: Seattle, WA
address:

summary: RANS model parameters estimation in inhomogeneous turbulent flow (axisymmetric transonic bump) using Approximate Bayesian Computation (ABC).
abstract: "Traditionally, turbulence model parameters have
           been determined through either direct inversion of model equations given some reference data or using optimization techniques. However, the former approach becomes
           complicated for models with many different parameters or when the model consists
           of partial differential equations. Here, we use an Approximate Bayesian computation (ABC) approach to estimate unknown model parameter values, as well as
           their uncertainties, in a nonequilibrium anisotropy closure for Reynolds averaged
           Navier-Stokes (RANS) simulations. ABC does not require direct computation of
           a likelihood function, thereby enabling substantially faster estimation of unknown
           parameters as compared to full Bayesian analyses. Details of the ABC approach are
           described, including the use of a Markov chain Monte Carlo technique as well as
           the choice of summary statistics and distance function. Unknown model parameters
           are estimated based on reference data for different homogeneous nonequilibrium test
           cases. We also discuss the calibration of turbulence models in inhomogeneous flows
           using forward simulations of an axisymmetric bump."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2019-11-26T08:24:00Z"
date_end: "2019-11-26T08:37:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 

authors: ["olga_doronina", "Scott Murman", "Peter Hamlington"]
tags: ["ABC", "RANS"]

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 
  focal_point: Right

links:
url_code: ""
url_pdf: "http://absimage.aps.org/image/DFD19/MWS_DFD19-2019-003688.pdf"
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: 

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
- ABC_turbulence_modeling

# Enable math on this page?
math: true

---

