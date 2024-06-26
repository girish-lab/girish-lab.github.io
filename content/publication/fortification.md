+++
title = "On Fortification of Projection Games"
date = "2015-08-10"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Amey Bhangale", "Ramprasad Saptharishi", "Girish Varma", "Rakesh Venkat"]


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
publication = "Randomization and Computation (<strong>RANDOM'15</strong>)"
publication_short = "RANDOM'15"

# Abstract and optional shortened version.
abstract = ""

bibtex='''
@InProceedings{BSVV15,
  author =	{Amey Bhangale and Ramprasad Saptharishi and Girish Varma and Rakesh Venkat},
  title =	{{On Fortification of Projection Games}},
  booktitle =	{Approximation, Randomization, and Combinatorial Optimization. Algorithms and Techniques (APPROX/RANDOM 2015)},
  pages =	{497--511},
  series =	{Leibniz International Proceedings in Informatics (LIPIcs)},
  ISBN =	{978-3-939897-89-7},
  ISSN =	{1868-8969},
  year =	{2015},
  volume =	{40},
  editor =	{Naveen Garg and Klaus Jansen and Anup Rao and Jos{\'e} D. P. Rolim},
  publisher =	{Schloss Dagstuhl--Leibniz-Zentrum fuer Informatik},
  address =	{Dagstuhl, Germany},
  URL =		{http://drops.dagstuhl.de/opus/volltexte/2015/5320},
  URN =		{urn:nbn:de:0030-drops-53204},
  doi =		{10.4230/LIPIcs.APPROX-RANDOM.2015.497},
  annote =	{Keywords: Parallel Repetition, Fortification}
}
'''
# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = ["probabilistically-checkable-proofs", "game-theory", "complexity-theory"]

# Links (optional).
#url_pdf =  "https://doi.org/10.1016/j.jtbi.2012.06.017"
url_preprint = "https://arxiv.org/abs/1504.05556"
#url_code = "#"
#url_dataset = "#"
#url_project = "#"
#url_slides = "https://www.dropbox.com/s/mv391tfzysae7ee/slides.pdf?dl=0"
#url_video = "#"
#url_poster = "#"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
#math = true

# Does the content use source code highlighting?
#highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++

A recent result of Moshkovitz cite{Moshkovitz14} presented an ingenious method to provide a completely elementary proof of the Parallel Repetition Theorem for certain projection games via a construction called fortification. However, the construction used in cite{Moshkovitz14} to fortify arbitrary label cover instances using an arbitrary extractor is insufficient to prove parallel repetition. In this paper, we provide a fix by using a stronger graph that we call fortifiers. Fortifiers are graphs that have both 1 and 2 guarantees on induced distributions from large subsets. We then show that an expander with sufficient spectral gap, or a bi-regular extractor with stronger parameters (the latter is also the construction used in an independent update cite{Moshkovitz15} of cite{Moshkovitz14} with an alternate argument), is a good fortifier. We also show that using a fortifier (in particular 2 guarantees) is necessary for obtaining the robustness required for fortification.