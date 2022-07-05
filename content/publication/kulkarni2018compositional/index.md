---
title: 'A Compositional Approach to Reactive Games under Temporal Logic Specifications'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jie Fu

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2018'
doi: ''

# Schedule page publish date (NOT publication's date).
# (AK) Only year, month is correct, rest is random.
publishDate: '2018-12-01T07:32:00-08:00'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Annual American Control Conference*
publication_short: In *ACC*

abstract: We study the problem of compositional synthesis of controllers for reactive games with linear temporal logic (LTL) specifications. A reactive game is an abstraction of the interaction between a controllable system and its uncontrolled and dynamic environment. A centralized control design for such systems under complex specifications can be computationally expensive. Instead, a compositional approach aims to synthesize a controller for a complex specification by composing the solutions for its component sub-specifications. This mitigates the issue of scalability and has the advantages of being modular and flexible. This paper solves the problem of reactive game synthesis using the compositional approach in two steps. First, we use the notion of randomized permissive strategy to reduce the strategy synthesis problem to that of identifying only the winning region for the controlled agent against the uncontrolled environment. Then, we exploit the inherent compositional nature of LTL formulas to compose the independently computed winning regions of two sub-games into a superset of the composed-game winning region. We make use of elementary set operations to construct this superset. Finally, we introduce an iterative algorithm to extract the exact winning region from the superset. We prove the correctness of our proposed method and illustrate the solution using a toy-problem and a robot motion planning example.

# Summary. An optional shortened abstract.
summary: compositional reactive synthesis

tags: ['compositional synthesis', 'reactive synthesis']

# Display this page in the Featured widget?
featured: false 

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://akulkarni.me/res/papers/kulkarni2018compositional.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - compositional-synthesis

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""


# {{% callout note %}}
# Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
# {{% /callout %}}

# {{% callout note %}}
# Create your slides in Markdown - click the _Slides_ button to check out the example.
# {{% /callout %}}

# Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
---

