---
title: "GDLL: A Scalable and Share Nothing Architecture Based Distributed Graph Neural Networks Framework"
author_notes:
- 
- 
-
- "ORCID: 0000-0003-1659-6040"
authors:
- Doung Thi  Thu Van
- Muhammad Numan Khan
- Tariq Habib Afridi
- admin
- Aftab Alam
- Young-Koo Lee
date: "2022-01-31T00:00:00Z"
doi: ''
# doi: "https://doi.org/10.1109/ACCESS.2022.3148126"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Access, IEEE*"
publication_short: "IEEE Access, IEEE"

abstract: Deep learning has recently been shown to be effective in uncovering hidden patterns in non-Euclidean space, where data is represented as graphs with complex object relationships and interdependencies. Because of the implicit data dependence in the big graphs with millions of nodes and billions of edges, it is hard for industrial communities to exploit these methods to address real-world challenges at scale. The skewness property of big graphs, distributed file system performance penalty on small k-hop neighborhood subgraphs, and varying size of subgraph makes Graph Neural Networks (GNNs) training further challenging in a distributed environment using parameter servers. To address such issues, we propose a scalable, layered, fault-tolerance, and in-memory distributed computing-based graph neural network framework called Graph Distributed Learning Library (GDLL). The base layer utilizes an optimized distributed file system and a scalable graph data store to reduce the performance penalty. The second layer provides distributed graph processing using in-memory graph programming models while optimizing and hiding the underlying complexity of information complete subgraph computation. In the third layer, GNN modules are deployed on top of the first two layers for efficient distributed training using parameter servers. Finally, we evaluate and compare GDLL with the state-of-the-art solutions and outperform it significantly in terms of efficiency while maintaining similar GNN convergence.

# Summary. An optional shortened abstract.
summary: This paper introduces the Graph Distributed Learning Library (GDLL), a fault-tolerant, in-memory distributed framework for scalable GNN training. GDLL’s layered design combines an optimized distributed file system and graph data store, an in-memory graph-processing layer for k-hop subgraph computation, and a GNN training layer with parameter‐server support. Experimental results demonstrate that GDLL significantly outperforms state-of-the-art solutions in efficiency while maintaining comparable convergence.

tags:
- Graph Neural Networks
- Distributed Computing
- In-Memory Processing
- Fault Tolerance
- Scalable Architecture
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9698236
url_code: 'https://github.com/dke-lab/DGLL-2022/tree/main/Python'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
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
