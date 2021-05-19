---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Probabilistic Archetypal Analysis"
event: "Scientific Meeting for Classification and Data Analysis Group"
event_url: "http://cladag2019.unicas.it/download-files/cladag-program-02.pdf"
location:
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: "Given a set of observations, archetypal analysis finds 'extreme' examples, i.e., archetypes that represent the observations well. Following the geometric formulation proposed by Cutler and Breiman (1994) this is achieved by approximating the convex hull of the set of observations with the archetypes such that the observations can be explained as convex combinations of the archetypes; an analogy being the colors red, green and blue that can explain the color spectrum as convex combinations of these archetypal colors. Archetypal analysis can be seen as a matrix factorization problem, and is closely related to other 'prototype' finding approaches, e.g., k-means clustering and topic modelling. 

The standard approach of finding archetypes assumes that the observations are real valued, which, unfortunately, is not compatible with many practical situations. For example, one may ask to find archetypal responses for a set of binary questions, or archetypal document given a set of word count vectors of a set of documents.  In this talk, I will revisit archetypal analysis from the basic principles, and discuss a probabilistic framework that accommodates these scenarios, i.e., data types such as integers, categorical, and stochastic vector. This formulation is equivalent to performing archetypal analysis in the continuous parameter space of the probability distribution than in the discrete observation space, and for a range of exponential family distributions, such as Bernoulli, Poisson, and multinomial, the resulting optimization problem can be efficiently solved using majorization-minimization. For categorical variables, e.g., multiple-option questions, I will introduce an extension of this approach to a generative framework using Dirichlet prior over the mixing parameters for which the approximate posterior distribution can be efficiently inferred using variational Bayes', and associated hyperparameters help finding a suitable number of archetypes.  

I will show the application of these formulations for finding archetypal tourists based on binary survey data, archetypal disaster-affected countries based on disaster count data, archetypal customers using German credit data, archetypal images using SUN image attribute data, and archetypal behaviour from Big Five personality data. I will also present an appropriate visualization tool to summarize the archetypal analysis solution, and address some recent developments in this area and some open questions.
"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2019-09-11T10:00:27+01:00
date_end: 2019-09-11T10:45:27+01:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2021-05-10T20:44:27+01:00

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your talk's folder or a URL.
url_slides:

url_code: https://aalab.github.io
url_pdf: files/cladag2019.pdf
url_video:

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
