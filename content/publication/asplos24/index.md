---
title: 'Optimizing Deep Learning Inference via Global Analysis and Tensor Expression'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Chunwei Xia
  - Jiacheng Zhao
  - Qianqi Chen
  - Zheng Wang
  - Xiaobing Feng
  - Huimin Cui

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-04-29T00:00:00Z'
doi: '10.1145/3617232.3624858'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-04-17T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 29th ACM International Conference on Architectural Support for Programming Languages and Operating Systems*
publication_short: In *ASPLOS '24*

abstract: Optimizing deep neural network (DNN) execution is important but becomes increasingly difficult as DNN complexity grows. Existing DNN compilers cannot effectively exploit optimization opportunities across operator boundaries, leaving room for improvement. To address this challenge, we present Souffle, an open-source compiler that optimizes DNN inference across operator boundaries. Souffle creates a global tensor dependency graph using tensor expressions, traces data flow and tensor information, and partitions the computation graph into subprograms based on dataflow analysis and resource constraints. Within a subprogram, Souffle performs local optimization via semantic-preserving transformations, finds an optimized program schedule, and improves instruction-level parallelism and data reuse. We evaluated Souffle using six representative DNN models on an NVIDIA A100 GPU. Experimental results show that Souffle consistently outperforms six state-of-the-art DNN optimizers by delivering a geometric mean speedup of up to 3.7× over TensorRT and 7.8× over Tensorflow XLA.

# Summary. An optional shortened abstract.
summary: ''

tags:
  - Tensor Compiler

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/pdf/10.1145/3617232.3624858'
url_code: 'https://github.com/summerspringwei/souffle-ae/tree/main'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'slides/ASPLOS2024-Souffle.pdf'
url_source: ''
url_video: 'https://ucla.app.box.com/s/3hqli8jm3frvdji6tf4jnnmoh0y7w0dz'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Tensor Compiler'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
