---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "SAM: Optimizing Multithreaded Cores for Speculative Parallelism"
subtitle: ""
summary: "This work studies the interplay between multithreaded cores and speculative parallelism. These techniques are often
used together, yet they have been developed independently, causing major performance pathologies. This paper presents SAM, a simple instruction issue policy that addresses these pathologies by focusing execution resources on work that is more likely to commit, avoiding aborts and using speculation resources more efficiently. On a system with 64, 8-threaded SMT cores, SAM reduces wasted work by 52%."
authors: ["Maleen Abeydeera", "Suvinay Subramanian", "Mark C. Jeffrey", "Joel Emer", "Daniel Sanchez"]
tags: []
categories: []
lastmod: 2017-09-15
featured: true
draft: false
publication_short: "In *PACT*"
publication_types: ["1"]

url_pdf: "docs/2017.sam.pact.pdf"
url_slides: "slides/sam.slides.pdf"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
