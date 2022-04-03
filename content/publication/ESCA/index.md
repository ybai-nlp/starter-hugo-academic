---
title: "Exploring Explainable Selection to Control Abstractive Summarization"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Haonan Wang
- Yang Gao
- admin
- Mirella Lapata
- Heyan Huang

# Author notes (optional)
author_notes:
- 
- "Coresponding author"
- 
- 
- 
# date: "2021-07-01T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: The Thirty-Fifth AAAI Conference on Artificial Intelligence
publication_short: AAAI 2021

abstract: Like humans, document summarization models can interpret a document's contents in a number of ways. Unfortunately, the neural models of today are largely black boxes that provide little explanation of how or why they generated a summary in the way they did. Therefore, to begin prying open the black box and to inject a level of control into the substance of the final summary, we developed a novel select-and-generate framework that focuses on explainability. By revealing the latent centrality and interactions between sentences, along with scores for sentence novelty and relevance, users are given a window into the choices a model is making and an opportunity to guide those choices in a more desirable direction. A novel pair-wise matrix captures the sentence interactions, centrality, and attribute scores, and a mask with tunable attribute thresholds allows the user to control which sentences are likely to be included in the extraction. A sentence-deployed attention mechanism in the abstractor ensures the final summary emphasizes the desired content. Additionally, the encoder is adaptable, supporting both Transformer- and BERT-based configurations. In a series of experiments assessed with ROUGE metrics and two human evaluations, ESCA outperformed eight state-of-the-art models on the CNN/DailyMail and NYT50 benchmark datasets.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2004.11779.pdf'
url_code: 'https://github.com/Wanghn95/Esca_Code'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

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
# - example

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
