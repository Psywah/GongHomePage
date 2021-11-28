+++
title = "Domain decomposition preconditioners for high-order discretisations of the heterogeneous Helmholtz equation"
date = "2021-01-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Shihua Gong", "Ivan G. Graham", "Euan A. Spence"]

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
publication = "IMA Journal  Numerical. Analysis"
publication_short = "IMA J.  Numer. Anal."

# Abstract and optional shortened version.
abstract = " We consider  one-level additive Schwarz domain decomposition preconditioners for the   Helmholtz equation with  variable coefficients (modelling wave propagation in heterogeneous media), subject to  boundary conditions that include wave scattering problems. Absorption is included as a parameter in the problem.  This  problem is  discretised using $H^1$-conforming nodal  finite elements of fixed  local degree $p$ on meshes with diameter $h = h(k)$,  chosen so that the error remains bounded with increasing  $k$. The action of the one-level preconditioner  consists of the parallel solution of problems on subdomains (which can be of   general geometry), each equipped with an  impedance  boundary condition. We prove rigorous estimates  on the norm and field of values of the left- or right-preconditioned matrix that  show explicitly how the absorption, the heterogeneity in the coefficients and the dependence on the degree enter the estimates. These estimates  prove rigorously that,   with enough absorption and for $k$ large enough, GMRES is guaranteed to converge in a number of iterations that is independent of  $k,p,$ and the coefficients.    The theoretical threshold for $k$  to be large enough depends on $p$  and on the local variation of coefficients in subdomains  (and not globally).  Extensive numerical experiments are given for both the absorptive and the propagative cases;  in the latter case we investigate examples both when the coefficients are nontrapping and when they are trapping.  These experiments (i) support our  theory  in terms of dependence on polynomial degree and  the coefficients;   (ii) support the sharpness of our  field of values estimates in terms of the level of absorption required."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]

# Links (optional).
url_pdf = "https://doi.org/10.1093/imanum/draa080"
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
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++

