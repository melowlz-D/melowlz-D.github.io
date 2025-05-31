---
title: "Federated Training Generative Adversarial Networks  for Heterogeneous Vehicle Scheduling in IoV"
authors:
- Lizhao Wu
- Hui Lin
- Xiaoding Wang
date: "2025-03-01T12:00:00Z"
doi: "10.1109/JIOT.2024.3506159"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-03-01T12:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Internet of Things Journal"
publication_short: "IoTJ"

abstract: In autonomous driving environments, generative adversarial networks (GANs) are often used to predict the future trajectories of objects in the scene, providing decision support for autonomous driving systems. However, integrating GAN models into the Internet of Vehicles (IoV) poses numerous challenges. First, GAN models necessitate user data and extensive computing resources, whereas diverse intelligent connected vehicle (ICV) possess limited bandwidth and computational capabilities, making it challenging to deploy models of the same scale as those in the cloud. Second, multifaceted aspects, including energy consumption, computation, communication, and vehicle training scheduling, have yet to be thoroughly examined, particularly in the context of IoV’s limited resources. To address the above issues, we propose a novel federated learning framework, heterogeneous-vehicle-scheduling-GAN (HVS-GAN), for training GANs in resource-constrained IoV environments. HVS-GAN balances GAN generation quality and training costs in IoV. It supports multiple ICVs training GAN models of different structures, breaking the strong assumption of uniform GAN model size constraints in previous works and enabling collaborative learning within IoV. Furthermore, to balance quality and training costs, we incorporate deep deterministic policy gradients learning to manage varying model size constraints, training delays, and training consumption across participating ICVs. Experimental results and analysis confirm the superiority of our proposed HVSGAN solution, which achieves better outcomes in IoV scenarios with stringent model size constraints compared to state-of-the-art algorithms.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Deep deterministic policy gradients (DDPGs), federated learning (FL), generative adversarial etworks (GAN), Internet of Vehicles (IoV), reinforcement learning (RL).
featured: false

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

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
