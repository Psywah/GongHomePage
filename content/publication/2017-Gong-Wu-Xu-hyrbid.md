+++
title = "New Hybridized Mixed Methods for Linear Elasticity and Optimal Multilevel Solvers"
date = "2019-01-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Shihua Gong", "Shuonan Wu", "Jinchao Xu"]

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
publication = "Numerische Mathematik"
publication_short = "Numer. Math."

# Abstract and optional shortened version.
abstract = "In this paper, we present a family of new mixed finite element methods for linear elasticity for both spatial dimensions $n=2,3$, which yields a conforming and strongly symmetric approximation for stress. Applying $\\mathcal{P}_{k+1}-\\mathcal{P}_k$ as the local approximation for the stress and displacement, the mixed methods achieve the optimal order of convergence for both the stress and displacement when $k \\ge n$.  For the lower order case $(n-2\\le k<n)$, the stability and convergence still hold on some special grids. The proposed mixed methods are efficiently implemented by hybridization, which imposes the inter-element normal continuity of the stress by a Lagrange multiplier. Then, we develop and analyze multilevel solvers for the Schur complement of the hybridized system in the two dimensional case. Provided that no nearly singular vertex on the grids, the proposed solvers are proved to be uniformly convergent with respect to both the grid size and Poisson's ratio. Numerical experiments are provided to validate our theoretical results."

abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = [] #["example-external-project"]

# Links (optional).
url_pdf = "https://doi.org/10.1007/s00211-018-1001-3"
url_preprint = "" 
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = "/files/poster/2017hybrid.pdf"
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
image = "" #"headers/bubbles-wide.jpg"
caption = "" #"My caption :smile:"

+++

