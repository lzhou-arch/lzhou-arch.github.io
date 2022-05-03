---
title: 'Nvcool: When non-volatile caches meet cold boot attacks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xiang Pan
  - Anys Bacha
  - Spencer Rudolph
  - admin
  - Yinqian Zhang
  - Radu Teodorescu

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2018-10-07T00:00:00Z'
doi: '10.1109/ICCD.2018.00072'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Computer Design (ICCD)*
#publication_short: In *ICCD'18*

abstract: Non-volatile memories (NVMs) are expected to replace traditional DRAM and SRAM for both off-chip and on-chip storage. It is therefore crucial to understand their security vulnerabilities before they are deployed widely. This paper shows that NVM caches are vulnerable to so-called "cold boot" attacks, which involve physical access to the processor's cache. SRAM caches have generally been assumed invulnerable to cold boot attacks, because SRAM data is only persistent for a few milliseconds even at cold temperatures. Our study explores cold boot attacks on NVM caches and defenses against them. In particular, this paper demonstrates that hard disk encryption keys can be extracted from the NVM cache in multiple attack scenarios. We demonstrate a reproducible attack with very high probability of success. This paper also proposes an effective software-based countermeasure that can completely eliminate the vulnerability of NVM caches to cold boot attacks with a reasonable performance overhead.

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
