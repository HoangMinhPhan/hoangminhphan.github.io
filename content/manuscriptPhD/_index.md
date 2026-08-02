---
title: "My PhD Thesis"
summary: "My doctoral research explained for a general audience."
type: landing

sections:
  # 1. Layperson-friendly introduction
  - block: markdown
    id: introduction
    content:
      title: "My PhD in Simple Terms"
      text: |
        Write your layperson-friendly introduction here.

        Explain the problem without assuming that the reader has a scientific
        background. Describe why the problem matters, what motivated your
        research, and how it could benefit society or industry.

  # 2. Summary of the principal results
  - block: markdown
    id: results
    content:
      title: "What I Discovered"
      text: |
        Summarise your main results here.

        - **Result 1:** Explain the first important result.
        - **Result 2:** Explain the second important result.
        - **Result 3:** Explain the practical implications.

        Finish by explaining the overall contribution of your PhD research.

  # 3. Download button for the bundled PDF
  - block: cta-card
    id: download-thesis
    content:
      title: "Read the Full Thesis"
      text: "Download the complete doctoral dissertation as a PDF."
      button:
        text: "Download Thesis"
        url: "/thesis/phd-thesis.pdf"
        icon: "hero/arrow-down-tray"
        new_tab: true

  # 4. Embedded YouTube defense video
  - block: markdown
    id: defense-video
    content:
      title: "PhD Defense"
      text: |
        Watch the recording of my PhD defense below.

        <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
          <iframe
            src="https://www.youtube-nocookie.com/embed/YOUTUBE_VIDEO_ID"
            title="PhD defense of Hoang Minh Phan"
            loading="lazy"
            style="position: absolute; inset: 0; width: 100%; height: 100%; border: 0;"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen>
          </iframe>
        </div>

  # 5. Photographs from the defense
  - block: gallery
    id: defense-photos
    content:
      title: "Defense Moments"
      subtitle: "Photographs from my PhD defense."
      items:
        - src: "images/defense-01.jpg"
          alt: "Presenting my doctoral research"
          caption: "Presenting the main findings of my PhD research."

        - src: "images/defense-02.jpg"
          alt: "Discussion with the examination committee"
          caption: "Discussion with the examination committee."

        - src: "images/defense-03.jpg"
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
