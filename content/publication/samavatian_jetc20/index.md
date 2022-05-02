---
title: 'Rnnfast: An accelerator for recurrent neural networks using domain-wall memory'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Mohammad Hossein Samavatian
  - Anys Bacha
  - admin
  - Radu Teodorescu

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2020-09-18T00:00:00Z'
doi: '10.1145/3399670'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *ACM Journal on Emerging Technologies in Computing Systems (JETC)*
#publication_short: In *JETC*

abstract: Recurrent Neural Networks (RNNs) are an important class of neural networks designed to retain and incorporate context into current decisions. RNNs are particularly well suited for machine learning problems in which context is important, such as speech recognition and language translation. This work presents RNNFast, a hardware accelerator for RNNs that leverages an emerging class of non-volatile memory called domain-wall memory (DWM). We show that DWM is very well suited for RNN acceleration due to its very high density and low read/write energy. At the same time, the sequential nature of input/weight processing of RNNs mitigates one of the downsides of DWM, which is the linear (rather than constant) data access time. RNNFast is very efficient and highly scalable, with flexible mapping of logical neurons to RNN hardware blocks. The basic hardware primitive, the RNN processing element (PE), includes custom DWM-based multiplication, sigmoid and tanh units for high density and low energy. The accelerator is designed to minimize data movement by closely interleaving DWM storage and computation. We compare our design with a state-of-the-art GPGPU and find 21.8× higher performance with 70× lower energy.

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
