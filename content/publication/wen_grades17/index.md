---
title: 'Finding top k shortest simple paths with improved space efficiency'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Qingsong Wen
  - Ren Chen
  - Lifeng Nai
  - admin
  - Yinglong Xia

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2017-05-19T00:00:00Z'
doi: '10.1145/3078447.3078460'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *International Workshop on Graph Data-management Experiences & Systems (GRADES)*
#publication_short: In *GRADES'17*

abstract: Finding top-K shortest paths is fundamental and crucial to many graph applications, but known to be nontrivial over large graph data and large value of K. This problem becomes much more challenging when the shortest paths require to be simple (paths without loops). When searching for top-K shortest simple paths, MPS algorithm is a practically fast and efficient scheme based on the famous Yen's algorithm. In this paper, we propose an improved MPS algorithm which can significantly reduce the memory consumption and increase the execution speed compared to the original MPS algorithm. First, we design a pruning scheme during the construction of pseudo-tree, such that only the shortest path in each iteration would be added to the pseudo-tree, instead of adding all possible candidate paths as that in the original MPS algorithm. Second, we modify the pseudo-tree of shortest-path candidates with reversed order and internal ID, such that the shortest paths can be retrieved directly from the constructed pseudo-tree without explicitly storing all candidate paths. Furthermore, we evaluate the performance in terms of running time and memory consumption in both synthetic and real graphs with millions of vertices and edges. Compared to the original MPS algorithm, experimental results show that our improved MPS algorithm can bring up to 6x performance gain in both running time and memory consumption.

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
