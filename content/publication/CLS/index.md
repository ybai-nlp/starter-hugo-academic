---
title: "Cross-Lingual Abstractive Summarization with Limited Parallel Resources"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Yang Gao
- Heyan Huang

# Author notes (optional)
author_notes:
- 
- 
- "Coresponding author"
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
publication: Main conference paper at the Joint Conference of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing.
publication_short: ACL-IJCNLP 2021

abstract: Parallel cross-lingual summarization data is scarce, requiring models to better use the limited available cross-lingual resources. Existing methods to do so often adopt sequence-to-sequence networks with multi-task frameworks. Such approaches apply multiple decoders, each of which is utilized for a specific task. However, these independent decoders share no parameters, hence fail to capture the relationships between the discrete phrases of summaries in different languages, breaking the connections in order to transfer the knowledge of the high-resource languages to low-resource languages. To bridge these connections, we propose a novel Multi-Task framework for Cross-Lingual Abstractive Summarization (MCLAS) in a low-resource setting. Employing one unified decoder to generate the sequential concatenation of monolingual and cross-lingual summaries, MCLAS makes the monolingual summarization task a prerequisite of the cross-lingual summarization (CLS) task. In this way, the shared decoder learns interactions involving alignments and summary patterns across languages, which encourages attaining knowledge transfer. Experiments on two CLS datasets demonstrate that our model significantly outperforms three baseline models in both low-resource and full-dataset scenarios. Moreover, in-depth analysis on the generated summaries and attention heads verifies that interactions are learned well using MCLAS, which benefits the CLS task under limited parallel resources.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2105.13648'
url_code: 'https://github.com/ybai-nlp/MCLAS'
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
{{% /callout %}} -->


<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
