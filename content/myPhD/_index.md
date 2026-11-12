---
title: "My PhD Thesis"
summary: "My doctoral research explained for a general audience."
type: landing
# draft: false # Change to false when the page is ready

sections:
  # Layperson-friendly introduction
  - block: markdown
    id: introduction
    content:
      title: "My PhD in a Nutshell"
      text: |
        Write your layperson-friendly introduction here.


    # Download PhD thesis
  - block: markdown
    id: download-thesis
    content:
      text: |
        {{< button
          url="/uploads/_maincv.pdf"
          size="md"
          align="center"
          style="primary"
          icon="arrow-down-tray"
          new_tab="true"
        >}}
        Download my thesis
        {{< /button >}}



  # Embedded YouTube defense video
  - block: markdown
    id: defense-video
    content:
      title: "Watch my PhD Defense"
      text: |
        Watch the recording of my PhD defense below.
        The video recording will be added later in this block.


  # Photographs from the defense
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
