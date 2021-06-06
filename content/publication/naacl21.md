+++
title = "Robust Question Answering Through Sub-part Alignment"

# Date first published.
date = "2021-03-10"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Jifan Chen", "Greg Durrett"]

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
publication = "2021 Annual Conference of the North American Chapter of the Association for Computational Linguistics"
publication_short = "NAACL"

# Abstract and optional shortened version.
abstract = "Current textual question answering models achieve strong performance on in-domain test sets, but often do so by fitting surface-level patterns in the data, so they fail to generalize to out-of-distribution settings. To make a more robust and understandable QA system, we model question answering as an alignment problem. We decompose both the question and context into smaller units based on off-the-shelf semantic representations (here, semantic roles), and align the question to a subgraph of the context in order to find the answer. We formulate our model as a structured SVM, with alignment scores computed via BERT, and we can train end-to-end despite using beam search for approximate inference. Our explicit use of alignments allows us to explore a set of constraints with which we can prohibit certain types of bad model behavior arising in cross-domain settings. Furthermore, by investigating differences in scores across different potential answers, we can seek to understand what particular aspects of the input lead the model to choose the answer without relying on post-hoc explanation techniques. We train our model on SQuAD v1.1 and test it on several adversarial and out-of-domain datasets. The results show that our model is more robust cross-domain than the standard BERT QA model, and constraints derived from alignment scores allow us to effectively trade off coverage and accuracy."

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
url_pdf = "https://arxiv.org/pdf/2004.14648.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = "slides/naacl21.pdf"
url_video = "https://screencast-o-matic.com/watch/crhX0fVfqyB"
url_poster = "posters/naacl21.pdf"
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

