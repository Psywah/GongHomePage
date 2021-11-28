+++
title = "Convergence of parallel overlapping domain decomposition methods for the Helmholtz equation"
date = "2021-04-08"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Shihua Gong", "Martin J. Gander", "Ivan G. Graham", "David Lafontaine", "Euan A. Spence"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["0"]

# Publication name and optional abbreviated version.
publication = "submitted to Numer. Math."
publication_short = ""

# Abstract and optional shortened version.
abstract = "We analyse  parallel  overlapping Schwarz  domain decomposition  methods for the Helmholtz equation, where the subdomain problems satisfy   first-order absorbing (impedance) transmission conditions,  and   exchange of information between subdomains is achieved using a partition of unity.  We  provide a novel analysis of  this method at the PDE level (without   discretization).  First,  we formulate the method as a fixed point iteration, and show (in dimensions 1,2,3) that it is well-defined in a tensor product of appropriate local function spaces, each  with $L^2$ impedance boundary data. We then  obtain a  bound on the norm of the fixed point  operator in terms of the local norms of  certain impedance-to-impedance maps arising from local interactions between subdomains. These bounds  provide  conditions under which (some power of)  the fixed point operator is a  contraction. In 2-d, for rectangular domains and strip-wise  domain decompositions (with each subdomain only overlapping its immediate neighbours),   we present  two techniques for  verifying the assumptions on the impedance-to-impedance maps that ensure power contractivity of the fixed point operator.  The first is  through semiclassical analysis, which gives rigorous estimates valid as the frequency tends to infinity. At least for a model case with two subdomains, these results verify the required assumptions for sufficiently large overlap. For more realistic domain decompositions, we  directly  compute the norms of the  impedance-to-impedance maps by solving  certain canonical (local)  eigenvalue problems. We give  numerical experiments that illustrate the theory.  These also show  that the iterative method remains convergent and/or provides a good preconditioner in cases not covered by the theory, including for general domain decompositions, such as those obtained via automatic graph-partitioning software."
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
url_pdf = ""
url_preprint = "https://arxiv.org/abs/2106.05218" 
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

