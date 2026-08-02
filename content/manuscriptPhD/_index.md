---
title: "My PhD Thesis"
summary: "My doctoral research explained for a general audience."
type: landing
draft: true # Change to false when the page is ready

sections:
  # 1. Layperson-friendly introduction
  - block: markdown
    id: introduction
    content:
      title: "My PhD in Simple Terms"
      text: |
        Write your layperson-friendly introduction here.


  # 2. Summary of the principal results
  - block: markdown
    id: results
    content:
      title: "What I Discovered"
      text: |
        Summarise your main results here.


  # 3. Download button for the bundled PDF
  - block: cta-card
    id: download-thesis
    content:
      title: "Read the Full Thesis"
      text: "Download the complete doctoral dissertation as a PDF."
      button:
        text: "Download Thesis"
        url: "" # add "/path/to/phd-thesis.pdf"
        icon: "hero/arrow-down-tray"
        new_tab: true

  # 4. Embedded YouTube defense video
  - block: markdown
    id: defense-video
    content:
      title: "PhD Defense"
      text: |
        Watch the recording of my PhD defense below.
        The video recording will be added later in this block.


  # 5. Photographs from the defense
  - block: gallery
    id: defense-photos
    content:
      title: "Defense Moments"
      subtitle: "Photographs from my PhD defense."
      items:
        - src: "" # add "images/example.jpg"
          alt: "Presenting my doctoral research"
          caption: "Presenting the main findings of my PhD research."

        - src: "" # add "images/example.jpg"
          alt: "Discussion with the examination committee"
          caption: "Discussion with the examination committee."

        - src: "" # add "images/example.jpg"
          alt: "After the PhD defense"
          caption: "Celebrating after the successful defense."

    design:
      layout: grid        # grid | masonry | justified | carousel | slideshow
      columns: 3
      gap: md             # sm | md | lg
      aspect_ratio: landscape
      caption_position: below
      hover_zoom: true
      lightbox: true
---
