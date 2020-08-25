---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Chronos: Efficient Speculative Parallelism for Accelerators"
subtitle: ""
summary: "Chronos is a framework to build accelerators for applications with speculative parallelism. These applications consist of atomic tasks, sometimes with order constraints, and need speculative execution to extract parallelism. We demonstrate Chronos's feasibility and benefits by building FPGA accelerators for four such applications. When run on commodity AWS FPGA instances, these accelerators outperform state-of-the-art software versions running on a higher-priced multicore instance by 3.5× to 15.3×."
authors: ["Maleen Abeydeera", "Daniel Sanchez"]
tags: []
categories: []
lastmod: 2020-03-15
featured: true
draft: false
publication_short: "In *ASPLOS*"
publication_types: ["1"]

url_code: "https://github.com/SwarmArch/chronos"
url_pdf: "docs/2020.chronos.asplos.pdf"
url_slides: "slides/2020.chronos.asplos.slides.pdf"
url_video: "https://www.youtube.com/watch?v=B5U-J_fKVFY"

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
