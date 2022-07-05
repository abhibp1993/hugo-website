---
title: 'Decoy Allocation Games on Graphs with Temporal Logic Objectives'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jie Fu
  - Huan Luo
  - Charles A. Kamhoua
  - Nandi O. Leslie

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2020'
doi: ''

# Schedule page publish date (NOT publication's date).
# (AK) Only year, month is correct, rest is random.
publishDate: '2020-08-01T07:32:00-08:00'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Conference on Decision and Game Theory for Security*
publication_short: In *GameSec*

abstract: We study a class of games, in which the adversary (attacker) is to satisfy a complex mission specified in linear temporal logic, and the defender is to prevent the adversary from achieving its goal. A deceptive defender can allocate decoys, in addition to defense actions, to create disinformation for the attacker. Thus, we focus on the problem of jointly synthesizing a decoy placement strategy and a deceptive defense strategy that maximally exploits the incomplete information the attacker about the decoy locations. We introduce a model of hypergames on graphs with temporal logic objectives to capture such adversarial interactions with asymmetric information. Using the hypergame model, we analyze the effectiveness of a given decoy placement, quantified by the set of deceptive winning states where the defender can prevent the attacker from satisfying the attack objective given its incomplete information about decoy locations. Then, we investigate how to place decoys to maximize the defender's deceptive winning region. Considering the large search space for all possible decoy allocation strategies, we incorporate the idea of compositional synthesis from formal methods and show that the objective function in the class of decoy allocation problem is monotone and non-decreasing. We derive the sufficient conditions under which the objective function for the decoy allocation problem is submodular, or supermodular, respectively. We show a sub-optimal allocation can be efficiently computed by iteratively composing the solutions of hypergames with a subset of decoys and the solution of a hypergame given a single decoy. We use a running example to illustrate the proposed method.

# Summary. An optional shortened abstract.
summary: Labeling Misperception 

tags: ['deception']

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://arxiv.org/abs/2010.01208
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
  - deception

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

