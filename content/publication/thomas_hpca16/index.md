---
title: 'Core tunneling: Variation-aware voltage noise mitigation in GPUs'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Renji Thomas	
  - Kristin Barber
  - Naser Sedaghati
  - admin
  - Radu Teodorescu

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2016-03-12T00:00:00Z'
doi: '10.1109/HPCA.2016.7446061'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Symposium on High Performance Computer Architecture (HPCA)*
#publication_short: In *HPCA'16*

abstract: Voltage noise and manufacturing process variation represent significant reliability challenges for modern microprocessors. Voltage noise is caused by rapid changes in processor activity that can lead to timing violations and errors. Process variation is caused by manufacturing challenges in low-nanometer technologies and can lead to significant heterogeneity in performance and reliability across the chip. To ensure correct execution under worst-case conditions, chip designers generally add operating margins that are often unnecessarily conservative for most use cases, which results in wasted energy. This paper investigates the combined effects of process variation and voltage noise on modern GPU architectures. A distributed power delivery and process variation model at functional unit granularity was developed and used to simulate supply voltage behavior in a multicore GPU system. We observed that, just like in CPUs, large changes in power demand can lead to significant voltage droops. We also note that process variation makes some cores much more vulnerable to noise than others in the same GPU. Therefore, protecting the chip against large voltage droops by using fixed and uniform voltage guardbands is costly and inefficient. This paper presents core tunneling, a variation-aware solution for dynamically reducing voltage margins. The system relies on hardware critical path monitors to detect voltage noise conditions and quickly reacts by clock-gating vulnerable cores to prevent timing violations. This allows a substantial reduction in voltage margins. Since clock gating is enabled infrequently and only on the most vulnerable cores, the performance impact of core tunneling is very low. On average, core tunneling reduces energy consumption by 15%.

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
