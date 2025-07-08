---
title: "DAFOS: Dynamic Adaptive Fanout Optimization Sampler"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Young-Koo Lee

# Author notes (optional)
author_notes:
  - "ORCID: 0000-0003-1659-6040"
  - 'Equal contribution'

date: '2013-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the Korean DabaBase Conference*
publication_short: In *KDBC Proceedings*

abstract: Graph Neural Networks (GNNs) are becoming an essential tool for learning from graph-structured data, however uniform neighbor sampling and static fanout settings frequently limit GNNs’ scalability and efficiency. In this paper, we propose the Dynamic Adaptive Fanout Optimization Sampler (DAFOS), a novel approach that dynamically adjusts the fanout based on model performance and prioritizes important nodes during training. Our approach leverages node scoring based on node degree to focus computational resources on structurally important nodes, incrementing the fanout as the model training progresses. DAFOS also integrates an early stopping mechanism to halt training when performance gains diminish. Experiments conducted on three benchmark datasets, ogbnarxiv, Reddit, and ogbn-products, demonstrate that our approach significantly improves training speed and accuracy compared to a state-of-the-art approach. DAFOS achieves a 3.57x speedup on the ogbn-arxiv dataset and a 12.6x speedup on the Reddit dataset while improving the F1 score from 68.5% to 71.21% on ogbn-arxiv and from 73.78% to 76.88% on the ogbn-products dataset, respectively. These results highlight the potential of DAFOS as an efficient and scalable solution for large-scale GNN training.

# Summary. An optional shortened abstract.
summary: This paper introduces DAFOS, a dynamic adaptive fanout sampler for GNNs that leverages node-degree scoring and early stopping to achieve substantial speedups and accuracy gains on large graph benchmarks.

tags:
  - Graph Neural Networks
  - Dynamic Sampling
  - Adaptive Fanout
  - Scalability
  - Performance Optimization
  - Early Stopping

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: "https://drive.google.com/file/d/1jTMFkkzgVl-p7LZZMyJkUrRQtXswUMof/view?usp=drive_link"
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
