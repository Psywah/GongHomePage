+++
date = 2017-01-01T00:00:00  # Schedule page publish date.

title = "A Robust Multilevel Solver for a New Hybridizable Mixed Discretization of Linear Elasticity"
time_start = 2017-03-26T15:00:00
time_end = 2017-03-30T15:00:00
abstract = "We present a family of new mixed finite element methods for the linear elasticity and then develop a robust overlapping domain decomposition method to solve the linear system. Our mixed discretization, preserving the symmetry and the exact $H(div)$ conformity in the stress approximation, can be efficiently implemented by hybridization, which reduces the indefinite system to a symmetric positive-semidefinite system. The condition number of the reduced system, which is characterized by a non-inherited bilinear form, depends not only on the grid size but also on the material parameters. By constructing uniformly stable interpolation operators between the non-nested spaces, we prove that our overlapping domain decomposition method converges uniformly with respect to both the grid size and Poisson's ratio. Numerical experiments are presented to validate our theoretical results."
abstract_short = ""
event = "18th Copper Mountain Conference On Multigrid Methods"
event_url = "http://grandmaster.colorado.edu/~copper/2017/"
location = "Copper Mountain, Colorado, USA"

# Is this a selected talk? (true/false)
selected = false

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects = ["deep-learning"]

# Links (optional).
url_pdf = ""
url_slides = "/files/slide/201703Copper.pdf"
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

