---
title: "Endogenous Belief Switching"
authors: ["Mátyás Farkas"]
date: "2022-08-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Working paper - Updated Draft"
publication_short: ""

abstract:  Forward guidance has emerged as a crucial tool for central banks as short-term interest rates approach the zero lower bound. While economic theory has extensively examined the effectiveness of unconventional monetary policy, recent attention has focused on the fundamental role of expectations in macroeconomic models. However, limited research exists on forward guidance in an adaptive learning environment, particularly when expectations become adaptive at the zero lower bound. This paper aims to address this gap by investigating the forward guidance puzzle within an adaptive learning framework and emphasizing the significance of monetary policy in expectation formation.
To explain the role of learning and dynamic expectation formation in the context of unconventional monetary policy, I propose the framework of endogenous belief switching. This framework combines rational and adaptive learning approaches to solve the forward guidance puzzle. It posits that expectations are determined by central bank actions, making the effectiveness of forward guidance endogenous - I allow agents to learn the transmission of pre-announced policy rate changes based by alternating between forward-looking beliefs or focusing solely on current conditions and forming backward-looking beliefs. I endogenize belief switching by incorporating a mean squared learning transition between these two belief regimes. Agents update their beliefs every period using a switching K\'alm\'an filter \citep{murphy1998switching}, which allows them to dynamically determine whether to adopt a forward-looking or backward-looking perspective based on the probability that either regime best describes the economy.
Simulation results demonstrate that the effectiveness of forward guidance is nonlinear. When agents are adaptive and backward-looking, the forward guidance puzzle does not arise. However, if expectations are adaptive and forward-looking, the puzzle emerges. The framework predicts that forward guidance is highly effective in low uncertainty environments, where the model aligns well with the data and observation error is minimal. Conversely, in high uncertainty economies, forward guidance can become ineffective. In such cases, agents may opt to become backward-looking due to excessive noise relative to the signal provided by forward guidance. However, agents can learn to trust the central bank if it conveys a strong enough signal regarding its commitment.

# Summary. An optional shortened abstract.
summary: This paper presents theoretical solution to the forward guidance puzzle amid adaptive expectations. It argues that the effectiveness of forward guidance is endogenous and argues that central bank action can determine expectation formation and establish or destroy credibility of forward guidance. 

tags:
- Source Themes
featured: false

links:
# - name: Custom Link
#  url: http://example.org
url_pdf: ebs.pdf
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
url_slides: EBS_presentation.pdf
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Endogenous belief switching diagramm'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: "EBS_presentation"
---

