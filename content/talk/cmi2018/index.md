---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Estimating Bacterial and Cellular Load in FCFM Imaging"
event: "Center for Medical Informatics Seminar Series"
event_url:
location:
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: "We address the task of estimating bacterial and cellular load in the human distal lung with fibered confocal fluorescence microscopy (FCFM). In pulmonary FCFM some cells can display autofluorescence, and they appear as disc like objects in the FCFM images, whereas bacteria, although not autofluorescent, appear as bright blinking dots when exposed to a targeted smartprobe. Estimating bacterial and cellular load becomes a challenging task due to the presence of background from autofluorescent human lung tissues, i.e., elastin, and imaging artifacts from motion etc. We create a database of annotated images for both these tasks where bacteria and cells were annotated, and use these databases for supervised learning. We extract image patches around each pixel as features, and train a classifier to predict if a bacterium or cell is present at that pixel. We apply our approach on two datasets for detecting bacteria and cells respectively. For the bacteria dataset, we show that the estimated bacterial load increases after introducing the targeted smartprobe in the presence of bacteria. For the cell dataset, we show that the estimated cellular load agrees with a clinician’s assessment."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2018-09-24T12:00:15+01:00
date_end: 2018-09-24T13:00:15+01:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2021-05-10T20:04:15+01:00

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

url_code: https://github.com/sohanseth/mcls
url_pdf: files/cmi2018.pdf
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
