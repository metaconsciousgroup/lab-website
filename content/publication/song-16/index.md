---
title: "Training Excitatory-Inhibitory Recurrent Neural Networks for Cognitive Tasks: A Simple and Flexible Framework"
authors:
- H Francis Song
- admin
- Xiao-Jing Wang
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2016-02-29T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*PLOS Computational Biology*"
publication_short: ""

abstract: The ability to simultaneously record from large numbers of neurons in behaving animals has ushered in a new era for the study of the neural circuit mechanisms underlying cognitive functions. One promising approach to uncovering the dynamical and computational principles governing population responses is to analyze model recurrent neural networks (RNNs) that have been optimized to perform the same tasks as behaving animals. Because the optimization of network parameters specifies the desired output but not the manner in which to achieve this output, “trained” networks serve as a source of mechanistic hypotheses and a testing ground for data analyses that link neural computation to behavior. Complete access to the activity and connectivity of the circuit, and the ability to manipulate them arbitrarily, make trained networks a convenient proxy for biological circuits and a valuable platform for theoretical investigation. However, existing RNNs lack basic biological features such as the distinction between excitatory and inhibitory units (Dale’s principle), which are essential if RNNs are to provide insights into the operation of biological circuits. Moreover, trained networks can achieve the same behavioral performance but differ substantially in their structure and dynamics, highlighting the need for a simple and flexible framework for the exploratory training of RNNs. Here, we describe a framework for gradient descent-based training of excitatory-inhibitory RNNs that can incorporate a variety of biological knowledge. We provide an implementation based on the machine learning library Theano, whose automatic differentiation capabilities facilitate modifications and extensions. We validate this framework by applying it to well-known experimental paradigms such as perceptual decision-making, context-dependent integration, multisensory integration, parametric working memory, and motor sequence generation. Our results demonstrate the wide range of neural activity patterns and behavior that can be modeled, and suggest a unified setting in which diverse cognitive computations and mechanisms can be studied.


# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Cognition
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: http://arxiv.org/pdf/1512.04133v1
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
slides:
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
