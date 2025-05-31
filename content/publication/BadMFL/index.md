---
title: "Bad-MFL: A Cross-Modality Bi-Trigger Backdoor Attack against Multi-Modal Federated Learning"
authors:
- Yuefeng Lai
- Lizhao Wu*
- Hui Lin
date: "2025-05-01T12:00:00Z"
# doi: "10.1109/JIOT.2024.3506159"

# Schedule page publish date (NOT publication's date).
# publishDate: "2025-05-01T12:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Internet of Things Journal"
publication_short: "IEEE IoTJ"

abstract: Against the backdrop of the rapid proliferation of Industrial Internet of Things, due to the rapid increase in edge devices and multi-modal data, Multi-modal Federated Learning (MFL)—an extension of Federated Learning(FL)—has become the mainstream solution for fusing heterogeneous sensor data in edge computing. Although MFL is inherently vulnerable to backdoor attacks similar to FL, its cross-modal fusion techniques for verifying semantic consistency gradually may cause single modal triggers to be faded during training. To address the aforementioned issue, we propose a cross-modality bi-trigger backdoor attack against MFL, named Bad-MFL, which are the first backdoor attack specifically targeting MFL. Bad-MFL employs two trigger generation modes to randomly implant logically correlated, invisible bi-trigger in two modalities. By maintaining semantic consistency between the triggers, BadMFL bypasses cross-modal fusion validation and successfully implants a backdoor into the global model. Moreover, it ensures the backdoor will not disappear as training progresses. Our experiments indicate that, compared to traditional backdoor attack methods, Bad-MFL achieving an Attack Success Rate up to 89.04%, which is 56% higher than the baseline attack, and its backdoor remains effective in high heterogeneous environments throughout training.
# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Federated Learning, Backdoor Attack.
featured: True

# links:
# - name: ""
#   url: ""
# url_pdf: https://ieeexplore.ieee.org/document/10772315
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
