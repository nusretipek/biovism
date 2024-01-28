---
title: "Combining natural language processing and multidimensional classifiers to predict and correct CMMS metadata"
authors:
- Deloose et al 
author_notes:
- "Arne Deloose and Jan Verwaeren"

date: "2023-01-04T00:00:00Z"
doi: "https://doi.org/10.1016/j.compind.2022.103830"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-01-04T00:00:00Z"

# Publication type
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Computers in Industry"
publication_short: ""

abstract: Computerized maintenance management systems (CMMSs) contain valuable data on the maintenance operations in an organization. A large part of these data consists of unstructured, written texts contained in failure notifications which are generated each time an unexpected failure occurs, enriched with structured metadata consisting of a number of labels that allow to categorize the failures, such as the type of failure, its cause or the corrective action that was taken. In this paper, we show that natural language processing techniques can be used to predict the structured metadata based on the unstructured text and even identify mislabeled notifications or ambiguous labels. Specific attention is given to the complexity that arises from the highly technical nature of the texts combined with a telegraphic writing style and heavy use of sentence fragments and abbreviations. Moreover, it is shown that exploiting dependencies between different components of the metadata, and regarding the prediction problem as a multidimensional classification problem, can improve the reliability of the predicted labels. We illustrate and test our label prediction pipeline on the CMMS data of a large pharmaceutical company.

# Summary. An optional shortened abstract.
#summary: 

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/pii/S0166361522002263/pdfft?md5=d70932140bfe745bd17abadb66d42a46&pid=1-s2.0-S0166361522002263-main.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
