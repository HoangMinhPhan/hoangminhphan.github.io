---
title: 'Non-destructive internal disorder segmentation in pear fruit by X-ray radiography and AI'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Astrid Tempelaere
  - me
  - Tim Van De Looverbosch
  - Pieter Verboven
  - Bart Nicolai


# Author notes (optional)
author_notes:


date: '2023-08-20'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal-article']

# Publication metadata — structured fields used by citation styles and BibTeX export.
publication:
  name: "Computers and Electronics in Agriculture"
  volume: 212


peer_reviewed: true
open_access: false

# Awards, honors, and recognitions. Surfaced as badges on the page and in listings.
awards:
# Funders and grants. Required by many funders for compliance reporting.
funding:

abstract: |
  A particular challenge for food quality inspection remains the quantification of internal defects. 
  This work addresses the challenge of internal defects segmentation in pear fruit (cv. Conference) 
  based on high-throughput inline X-ray radiography images in combination with deep learning. 
  Unlike previous approaches, which focused on healthy vs defect classification, the current segmentation 
  approach is able to determine the type of defect, its dimensions, and location. 
  To this end, a novel simulation method was designed to obtain input-target image pairs of radiography 
  data, and more diverse defect pears were generated using a conditioned generator model. 
  The obtained data contributed to the design of a segmentation model that labeled every pixel 
  in the X-ray radiographs of pear fruit as ‘external air’, ‘healthy tissue’, ‘core’, ‘browning’, 
  or ‘cavity’. We demonstrated that additional synthetic data in the learning process drastically improved 
  the model performance. For instance, the mean IoU increased from 0.781 ± 0.112 to 0.883 ± 0.088 
  for consumable pears with minor cavities and browning. In terms of utility, our segmentation maps provide 
  more detailed information about the type, size, and location of the disorders compared to the heatmaps 
  produced by existing benchmark classifiers.

# Summary. An optional shortened abstract.
summary: 

tags:
  - Deep Learning
  - X-ray imaging

# Display this page in the Featured widget?
featured: false


# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1016/j.compag.2023.108142


# Custom links
links:


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:


# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/projects/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
