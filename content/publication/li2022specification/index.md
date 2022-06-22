---
title: 'Dynamic Hypergames for Synthesis of Deceptive Strategies with Temporal Logic Objectives'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Lening Li
  - Haoxiang Ma
  - admin
  - Jie Fu

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022'
doi: 'https://doi.org/10.1109/TASE.2022.3150167'

# Schedule page publish date (NOT publication's date).
# (AK) Only year, month is correct, rest is random.
publishDate: '2022-05-27T07:32:00-08:00'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Automation Science and Engineering*
publication_short: In *TASE*

abstract: In this paper, we study the use of deception for strategic planning in adversarial environments. We model the interaction between the agent (player 1) and the adversary (player 2) as a two-player concurrent stochastic game in which the adversary has incomplete information about the agent's task specification given as a temporal logic formula. During the interaction, the adversary can infer the agent's intention from observations and adapt its strategy so as to prevent the agent from satisfying the objective. To plan against such an adaptive opponent, the agent must leverage its knowledge about the adversary's incomplete information to influence the behavior of the opponent, and thereby be deceptive. To synthesize a deceptive strategy, we introduce a class of hypergame models that capture the interaction between the agent and its adversary given asymmetric, incomplete information. We develop a solution concept for this class of hypergames and show that the subjectively rationalizable strategy for the agent is deceptive and maximizes the probability of satisfying the task in temporal logic. Such a deceptive strategy is obtained by modeling the opponent's evolving perception of the agent's objective and integrating it into planning. This allows the agent to manipulate the opponent's perception so as to induce the opponent into taking actions that benefit the agent. We demonstrate the effectiveness of our deceptive planning algorithm using robot motion planning examples with temporal logic objectives and design a detection mechanism to notify the agent of potential errors in modeling the adversary's behavior.

# Summary. An optional shortened abstract.
summary: Specification Deception

tags: ['deception']

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://arxiv.org/abs/2007.15726
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

