---
title: 'An edge-set based large scale graph processing system'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yinglong Xia
  - Hui Zang
  - Jian Xu
  - Mingzhen Xia

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2016-12-05T00:00:00Z'
doi: '10.1109/BigData.2016.7840780'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Big Data (Big Data)*
#publication_short: In *BigData16*

abstract: Next generation analytics will be all about graphs, though performance has been a fundamental challenge for large scale graph processing. In this paper, we present an industrial graph processing engine for exploring various large scale linked data, which exhibits superior performance due to the several innovations. This engine organizes a graph as a set of edge-sets, compatible with the traditional edge-centric sharding for graphs, but becomes more amenable for large scale processing. Each time only a portion of the sets are needed for computation and the data access patterns can be highly predictable for prefetch for many graph computing algorithms. Due to the sparsity of large scale graph structure, this engine differentiates logical edge-sets from the edge-sets physically stored on the disk, where multiple logical edge-sets can be organized into a same physical edge-set to increase the data locality. Besides, in contrast to existing solution, the data structures utilized for the physical edge-sets can vary from one to another. Such heterogeneous edge-set representation explores the best graph processing performance according to local data access patterns. We conduct experiments on a representative set of property graphs on multiple platforms, where the proposed system outperform the baseline systems consistently.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags: []

# Display this page in the Featured widget?
#featured: true

# Custom links (uncomment lines below)
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
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
