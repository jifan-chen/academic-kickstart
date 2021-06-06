+++
title = "Can NLI Models Verify QA Systems' Predictions?"

# Date first published.
date = "2021-04-17"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Jifan Chen", "Eunsol Choi", "Greg Durrett"]

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
publication = "arxiv preprint"
publication_short = "arxiv"

# Abstract and optional shortened version.

abstract = "To build robust question answering systems, we need the ability to verify whether answers to questions are truly correct, not just ``good enough'' in the context of imperfect QA datasets. We explore the use of natural language inference (NLI) as a way to achieve this goal, as NLI inherently requires the premise (document context) to contain all necessary information to support the hypothesis (proposed answer to the question). We leverage large pre-trained models and recent prior datasets to construct powerful question converter and decontextualization modules, which can reformulate QA instances as premise-hypothesis pairs with very high reliability. Then, by combining standard NLI datasets with NLI examples automatically derived from QA training data, we can train NLI models to judge the correctness of QA models' proposed answers. We show that our NLI approach can generally improve the confidence estimation of a QA model across different domains, evaluated in a selective QA setting. Careful manual analysis over the predictions of our NLI model shows that it can further identify cases where the QA model produces the right answer for the wrong reason, or where the answer cannot be verified as addressing all aspects of the question."


#abstract_short = "A short version of the abstract."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Links (optional).
url_pdf = "https://arxiv.org/pdf/2104.08731.pdf"
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
#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption 😄"

+++

