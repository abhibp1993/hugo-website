---
title: 'Synthesis of Deceptive Strategies in Reachability Games with Action Misperception'

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

date: '2020'
doi: ''

# Schedule page publish date (NOT publication's date).
# (AK) Only year, month is correct, rest is random.
publishDate: '2020-12-01T07:32:00-08:00'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *International Joint Conferences on Artificial Intelligence Organization*
publication_short: In *IJCAI*

abstract: We consider a class of two-player turn-based zerosum games on graphs with reachability objectives, known as reachability games, where the objective of Player 1 (P1) is to reach a set of goal states, and that of Player 2 (P2) is to prevent this. In particular, we consider the case where the players have asymmetric information about each other’s action capabilities - P2 starts with an incomplete information (misperception) about P1’s action set, and updates the misperception when P1 uses an action previously unknown to P2. When P1 is made aware of P2’s misperception, the key question is whether P1 can control P2’s perception so as to deceive P2 into selecting actions to P1’s advantage? To answer this question, we introduce a dynamic hypergame model to capture the reachability game with evolving misperception of P2. Then, we present a fixedpoint algorithm to compute the deceptive winning region and strategy for P1 under almost-sure winning condition. Finally, we show that the synthesized deceptive winning strategy is at least as powerful as the (non-deceptive) winning strategy in the game in which P1 does not account for P2’s misperception. We illustrate our algorithm using a robot motion planning in an adversarial environment.

# Summary. An optional shortened abstract.
summary: Action  Misperception 

tags: ['deception']

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://www.ijcai.org/Proceedings/2020/0031.pdf
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

