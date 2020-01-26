---
title: "URECA: A Compiler Solution to Manage Unified Register File for CGRAs"
# authors: ["Shail Dave", "Mahesh Balasubramanian", "Aviral Shrivastava"]
date: 2018-03
doi: "10.23919/DATE.2018.8342172"

# Shail Dave, Mahesh Balasubramanian, Aviral Shrivastava, "", in Proceedings of the 21st International Conference on Design Automation and Test in Europe (DATE), 2018 [Paper] [Slides] (acceptance rate:  185/766 = 24%)
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

# Schedule page publish date (NOT publication's date).
# publishDate: {{ 2017 }}

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
# publication: "21st International Conference on Design Automation and Test in Europe"
# publication_short: "DATE"

abstract: "Coarse-grained reconfigurable array (CGRA) is a
promising solution to accelerate loops featuring loop-carried
dependencies or low trip-counts. One challenge in compiling
for CGRAs is to efficiently manage both recurring (repeatedly
written and read) and nonrecurring (read-only) variables of
loops. Although prior works manage recurring variables in
rotating register file (RF), they access the nonrecurring variables
through the on-chip memory. It increases memory accesses and
degrades the performance. Alternatively, both the variables can
be managed in separate rotating and nonrotating RFs. But,
it increases code size and effective utilization of the registers
becomes challenging. Instead, this paper proposes URECA, a
compiler solution to manage the variables in a single nonrotating
RF. During mapping loop operations on CGRA, the compiler
allocates necessary registers and splits RF in rotating and
nonrotating parts. It also pre-loads read-only values in the unified
RF, which are then directly accessed at run-time. Evaluating
compute-intensive benchmarks from MiBench show that URECA
provides a geomean speedup of 11.41x over sequential loop
execution. It improves the loop acceleration through CGRAs by
1.74x at 32% reduced energy consumption over state-of-the-art."

# Summary. An optional shortened abstract.
# summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# url_pdf:
# url_code:
# url_dataset:
# url_poster:
# url_project:
# url_slides:
# url_source:
# url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
# image:
#   caption: ""
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""
---
