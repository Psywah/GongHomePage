+++
date = 2019-06-26T00:00:00  # Schedule page publish date.

title = "An Analysis of a Schwarz preconditioner for heterogeneous Helmholtz problems"
time_start = 2019-06-26T15:00:00
time_end = 2019-06-26T15:30:00
abstract = "We consider one-level additive Schwarz preconditioners for a family of Helmholtz problems of increasing diculty characterized by wave number k. As k increases, the solution becomes more oscillatory and thus meshes need to be increasingly refined, leading to huge linear systems. Moreover, these linear systems become more indenite and the minors of the linear systems may be even singular, which prevents the usage of many standard preconditioning techniques. We discuss additive Schwarz preconditioners, of which the action requires solution of independent subproblems with absorbing boundary conditions and (possibly) absorption added in the domain. Then the local solutions are glued together using prolongation operators dened by a partition of unity and nodal interpolation. Supporting theory for this preconditioner in the case of homogeneous Helmholtz problems is given by I. G. Graham, E. A. Spence and J. Zou in [Preprint arXiv:1806.03731.]. In this talk, we will present preliminary theoretical results and numerical experiments for this method applied to heterogeneous Helmholtz problems. We also show that the method is independent of the underlying finite element discretizations."
abstract_short = ""
event = "the 28th edition of the Biennial Numerical Analysis Conference"
event_url = "https://numericalanalysisconference.org.uk"
location = "University of Strathclyde, Glasgow, UK"

# Is this a selected talk? (true/false)
selected = false

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects = ["deep-learning"]

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

#Embed your slides or video here using [shortcodes](https://sourcethemes.com/academic/post/writing-markdown-latex/). Further details can easily be added using *Markdown* and $\rm \LaTeX$ math code.
+++

