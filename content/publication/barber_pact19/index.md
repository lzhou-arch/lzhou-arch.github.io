---
title: 'Specshield: Shielding speculative data from microarchitectural covert channels'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Kristin Barber
  - Anys Bacha
  - admin
  - Yinqian Zhang
  - Radu Teodorescu

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2019-09-23T00:00:00Z'
doi: '10.1109/PACT.2019.00020'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Parallel Architectures and Compilation Techniques (PACT)*
#publication_short: In *PACT'19*

abstract: Hardware security has recently re-surfaced as a first-order concern to the confidentiality protections of computing systems. Meltdown and Spectre introduced a new class of microarchitectural exploits which leverage transient state as an attack vector, revealing fundamental security vulnerabilities of speculative execution in high-performance processors. These attacks profit from the fact that, during speculative execution, programs may execute instructions outside their legal control flows. This is used to gain access to restricted data, which is then exfiltrated through a covert channel. This paper proposes SpecShield, a family of microarchitectural mitigation techniques for shielding speculative data from covert channels used in transient execution attacks. Unlike prior work that has focused on closing individual covert channels used to leak sensitive information, SpecShield prevents the use of speculative data by downstream instructions until doing so is determined to be safe, thus isolating it from any covert channel. The most secure version of SpecShield eliminates transient execution attacks at a cost of 21% average performance degradation. A more aggressive version of SpecShield, which prevents the propagation of speculative data to known or probable covert channels provides only slightly relaxed security guarantees with an average of 10% performance impact.

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
