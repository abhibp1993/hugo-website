---
title: 'Synthesizing Attack-Aware Control and Active Sensing Strategies under Reactive Sensor Attacks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Sumukha Udupa
  - admin
  - Shuo Han
  - Nandi O. Leslie
  - Charles A. Kamhoua
  - Jie Fu

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023'
doi: ''

# Schedule page publish date (NOT publication's date).
# (AK) Only year, month is correct, rest is random.
publishDate: '2022-06-01T07:32:00-08:00'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Control System Letters*
publication_short: In *L-CSS*

abstract: We consider the probabilistic planning problem for a defender (P1) who can jointly query the sensors and take control actions to reach a set of goal states while being aware of possible sensor attacks by an adversary (P2) who has perfect observations. To synthesize a provably correct, attack-aware control and active sensing strategy for P1, we construct a stochastic game on graph where the augmented state includes the actual game state (known by the attacker), the belief of the defender about the game state (constructed by the attacker given the attacker's information about the defender's information). We presented an algorithm to solve a belief-based, randomized strategy for P1 to ensure satisfying P1's reachability objective with probability one, under the worst case sensor attacks carried out by an informed P2. The correctness of the algorithm is proven and illustrated with an example.

# Summary. An optional shortened abstract.
summary: One-sided Sensor Attack

tags: ['deception']

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://arxiv.org/abs/2204.01584
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
  - sensors

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

