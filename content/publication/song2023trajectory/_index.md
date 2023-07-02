---
title: "Trajectory Alignment: Understanding the Edge of Stability Phenomenon via Bifurcation Theory"
authors:
- admin
- Chulhee Yun
date: "2023-07-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "*arXiv preprint*"
publication_short: ""

abstract: Cohen et al. [8] empirically study the evolution of the largest eigenvalue of the loss Hessian, also known as sharpness, along the gradient descent (GD) trajectory and observe a phenomenon called the *Edge of Stability* (EoS). The sharpness increases at the early phase of training (referred to as *progressive sharpening*), and eventually saturates close to the threshold of $\frac{2}{\text{(step size)}}$. In this paper, we start by demonstrating through empirical studies that when the EoS phenomenon occurs, different GD trajectories (after a proper reparameterization) align on a specific bifurcation diagram determined solely by the loss function, independent of the network architecture, training data, and step size.  We rigorously prove this *trajectory alignment* phenomenon for a two-layer fully-connected linear network and a single-neuron nonlinear network trained with a single data point. Our trajectory alignment analysis establishes both progressive sharpening and EoS phenomena, encompassing and extending recent findings in the literature.

# Summary. An optional shortened abstract.
summary: ""

tags: ''
featured: false

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image: ""
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
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
slides: ""
---

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
