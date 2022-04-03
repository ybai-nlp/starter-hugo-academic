---
title: "Multiple perspective answer reranking for multi-passage reading comprehension"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Mucheng Ren
- Heyan Huang
- Ran Wei
- Hongyu Liu
- admin
- Yang Wang
- Yang Gao

# Author notes (optional)
# author_notes:
# - 
# - 
# - "Coresponding author"
# date: "2021-07-01T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: The CCF International Conference on Natural Language Processing and Chinese Computing 2019.
publication_short:  NLPCC 2019

abstract: This study focuses on multi-passage Machine Reading Comprehension (MRC) task. Prior work has shown that retriever, reader pipeline model could improve overall performance. However, the pipeline model relies heavily on retriever component since inferior retrieved documents would significantly degrade the performance. In this study, we proposed a new multi-perspective answer reranking technique that considers all documents to verify the confidence of candidate answers; such nuanced technique can carefully distinguish candidate answers to improve performance. Specifically, we rearrange the order of traditional pipeline model and make a posterior answer reranking instead of prior passage reranking. In addition, new proposed pre-trained language model BERT is also introduced here. Experiments with Chinese multi-passage dataset DuReader show that our model achieves competitive performance.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'http://tcci.ccf.org.cn/conference/2019/papers/EV12.pdf'
url_code: 'https://github.com/trib-plan/TriB-QA'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

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
slides: []
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
