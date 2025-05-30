---
title: "Toward Personalized Federated Meta-learning with
Constrained Hypernetwork on Non-IID Data"
authors:
- Lizhao Wu
- Xiaoding Wang
- Hui Lin
- Xu Yang
- Jiwu Shu
- Xun Yi
- Ibrahim Khalil
- Albert Y. Zomaya
date: "2025-04-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Personalized Federated Learning (pFL) tailors models to each client’s local data distribution in heterogeneous federated learning settings. Federated Meta-learning (FML), a branch of pFL, uses meta-learning for rapid adaptation, where clients start with a meta-model and personalize it by finetuning with local data. Due to the limitations of a single global meta-model when client data distributions differ significantly, the meta-model personalization in FML should be considered. However, most benchmark pFL methods lack meta-model personalization, often lacking meta-learning or relying on a single global meta-model. Besides, these methods do not offer both meta-model personalization and assurances on generalization and convergence due to challenges in measuring meta-model to client model distance effectively in FML. To address these issues, we combine FML with hypernetwork and propose a constrained hypernetwork-based FML framework called FMLH by innovatively uses a hypernetwork to capture fine-tuned model differences, allowing personalized meta-models for each client. We provide rigorous mathematical proofs illustrating how the hypernetwork affects the convergence and generalization bounds of FMLH. Experimental results demonstrate that FMLH significantly improves the model’s generalization in cross-client shifts, with up to an 18.71% increase in lowest decile accuracy. FMLH also outperforms representative pFL algorithms by up to 5.6% in maximum accuracy improvement.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Federated learning
- Meta-learning
- Data heterogeneity
- Hypernetwork

featured: true

links:
- name: Custom Link
  url: http://example.org
# url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/Wlzzzz-del/FMLH.git'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
