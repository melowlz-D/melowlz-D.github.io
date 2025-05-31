---
title: "Defending Against Backdoor Attacks through  Causality-Augmented Diffusion Models for Dataset  Purification"
authors:
- Yuefeng Lai
- Lizhao Wu*
- Hui Lin
- Xiaokang Zhou
date: "2024-12-17T12:00:00Z"
doi: "10.1109/TrustCom63139.2024.00127"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-12-17T12:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "2024 IEEE 23rd International Conference on Trust, Security and Privacy in Computing and Communications (TrustCom)"
publication_short: "IEEE TrustCom2024"

abstract: Dataset-Based Defense is a common proactive defense method aimed at countering backdoor attacks by filtering and removing poisoned samples from the training dataset. Recent research has utilized diffusion models to purify contaminated samples. However, during both forward and backward denoising processes, the inherent noise and distribution characteristics of the data can also affect the purification of poisoned samples, making the process unreliable. To address this issue, this paper re-examines the purification process from the perspective of causal graphs, revealing how backdoor triggers and noise act as confounding factors, generating false associations between contaminated images and labels. To eliminate this false association, we propose a Causality-Augmented Diffusion Model-Based Defense (CADMBD) method. CADMBD applies multiple iterations of forward noise addition and backward denoising to the data input in the diffusion model. During the backward denoising process, residual calculation and causal layer adjustment are used to eliminate backdoor pathways, thereby establishing a true causal relationship between benign features and labels. Finally, the most suitable generated image is selected as the final purified image based on pixel and feature distances from each iteration. Experimental results demonstrate that CADMBD effectively addresses various complex attacks, significantly enhancing the purification effect while minimizing the impact on benign sample accuracy, outperforming baseline defense methods.
# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Backdoor Attack, Casual Inference.
featured: True

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/document/10944967
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
slides: example
---
<!-- A novel framework to train GAN model with heterogeneous model in federated learning. -->
<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
