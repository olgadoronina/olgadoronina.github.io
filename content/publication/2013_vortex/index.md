+++
title = "Numerical simulation of acoustic waves scattering by isolated vortex structures"

# Date first published.
date = "2013-03-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["olga_doronina", "N. S. Zdanova"]

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
publication = "Matematicheskoe Modelirovanie"
publication_short = "Matem. Mod. (Russian)"

# Abstract and optional shortened version.
abstract = "We consider a problem of linear sound scattering by an isolated vortex to investigate the interaction of the vortex flow and acoustic waves. We present numerical simulation results for a planar wave scattered by a Gaussian-core vortex and a cylindrical point source acoustic wave scattered by a Rankine vortex. For numerical simulation, we use the EBR scheme on grids of different types. We compare the simulation results of different numerical approaches and the benchmark solution."
abstract_short = "We consider problems of linear sound scattering by an isolated vortex, namely, a planar wave scattered by a Gaussian-core vortex and a cylindrical point source acoustic wave scattered by a Rankine vortex. We compare the results of different numerical approaches and the benchmark solution."

# Featured image thumbnail (optional)
image_preview = ""

# Links (optional).
url_pdf = ""
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
links = [ {name = "Webpage", url= "http://mi.mathnet.ru/eng/mm3403"}]

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
The problem of sound scattering by an isolated vortex is not only interesting by itself but also is fundamental for understanding the interaction between acoustic waves and vortex flow, including the process of sound generation by turbulence.

When turbulence is represented by a distribution of localized vortices with certain static properties, the acoustic field scattered by such flow is a superposition of scattered acoustic fields from each vortex. Therefore, the description of an elementary event, scattering of sound by an isolated vortex, can be used to predict the impact on the acoustic field of the turbulent flow.

For the numerical simulation of this problem, we use a linear approximation of the mathematical model. This approximation is quite realistic because it reveals the main properties of the studied phenomena. Thus we model the problem using a system of linearized Euler equations, in which a vortex is defined as a background field.

We use EBR (Edge-Based Reconstruction) numerical scheme, the 5th order scheme based on the quasi-one-dimensional reconstruction, implemented in highly parallel research code NOISEtte (KIAM RAS). One of the goals of this study is to test the EBR scheme's ability to model such problems on unstructured grids and to assess its accuracy and efficiency compared to other approaches.