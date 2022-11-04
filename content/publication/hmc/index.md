---
title: "Bayesian Estimation of DSGE Models with Hamiltonian Monte Carlo"
authors: [ "Mátyás Farkas", "Bálint Tatár"]
date: "2020-08-01T00:00:00Z"
doi: ""   

# Schedule page publish date (NOT publication's date).
publishDate: "2020-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "IMFS WORKING PAPER SERIES NO. 144, R&R in Journal of Applied Econometrics"
publication_short: ""

abstract: In this paper we adapt the Hamiltonian Monte Carlo (HMC) estimator to DSGE models, a method presently applied in various fields due to its superior sampling and diagnostic properties. We implement it into a state-of-the-art, freely available high-performance software package, Stan. We estimate a small scale textbook New-Keynesian model and the Smets-Wouters model using US data. Our results and sampling diagnostics confirm the parameter estimates available in existing literature. In addition, we find bimodality in the Smets Wouters model even if we estimate the model using the original tight priors. Finally, we combine the HMC framework with the Sequential Monte Carlo (SMC) algorithm to create a powerful tool which permits the estimation of DSGE models with ill-behaved posterior densities.


# Summary. An optional shortened abstract.
summary: This paper introduces the Hamiltonian Monte Carlo (HMC) estimator to DSGE models. 

tags:
- Source Themes
featured: false

links:
# - name: Custom Link
#  url: http://example.org
# url_pdf: https://www.imfs-frankfurt.de/fileadmin/user_upload/IMFS_WP/IMFS_WP_144.pdf
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Bimodality in SW07 model - SHMC'
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
# slides: example
---

