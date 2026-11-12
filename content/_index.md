---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-07-30
type: landing

sections:
  - block: resume-biography-3

    id: homepage-bio # Homepage marker for links and custom CSS
    
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: |
        I am a PhD researcher at KU Leuven, Belgium, with a background in food technology, chemical engineering, and industrial process engineering.
        My expertise combines mathematical modelling, bioscience engineering, and applied data science to develop smarter, more efficient, and sustainable food systems.
        My current research focuses on developing a **[digital twin](https://www.ibm.com/think/topics/digital-twin)** of a commercial fruit cold storage system
        integrating fruit physiology, refrigeration engineering, and predictive modelling to improve fruit quality, storage efficiency, and sustainability.
        This research is part of [ENOUGH Project (H2020 EU)](https://enough-emissions.eu/), a European initiative driving sustainable innovation across the food sector.

        Before pursuing academic research, I worked as a *Chemical Engineer in the food industry*, gaining hands-on experience in process optimisation, technology transfer,
        and industrial projects. This experience shaped my approach to research: bridging scientific understanding with practical engineering solutions.

        ### Research & Expertise
        - **Digital twins & predictive modelling** — food systems monitoring, quality prediction, and operational optimisation.
        - **Postharvest technology & cold chain** — cold storage, fruit quality management, shelf life extension, and energy efficiency.
        - **Food processing & engineering** — process design, optimisation, and technology transfer.
        - **Applied data science & AI** — machine learning, deep learning, statistical modelling, and uncertainty quantification.

        ### Beyond Research
        Outside of the professional world, I enjoy reading, watching anime, learning new things, and exploring culinary cultures around the world. My favourite Vietnamese dish is
        [Bún Bò Huế](https://vietnamnomad.com/eat-drink/bun-bo-hue/) — a bold, spicy noodle soup from Central Vietnam that I highly recommend.
        More broadly, noodles in all their forms are close to my heart. I also like staying active on the badminton court.

    # Show a call-to-action button under your biography? (optional)
      button:
        text: Download myCV
        url: uploads/_maincv.pdf
      headings:
        about: 'About me'
        education: ''

    design:
      # CUSTOM GRADIENT ON:
      # `custom-home-gradient` activates custom.css.
      # `!py-8` preserves 2rem top/bottom padding inside the biography.
      css_class: 'custom-home-gradient [&_.resume-biography]:!py-8'

      # CUSTOM GRADIENT OFF:
      # Replace the line above with this line.
      # The gradient is disabled, but `!py-8` padding is preserved.
      # `!py-8` preserves 2rem top/bottom padding inside the biography.
      # css_class: '[&_.resume-biography]:!py-8'
    
      # Customise alignment of biography text
      biography:
        style: "text-align: justify; text-justify: inter-word; font-size: 1rem; line-height: 1.5;"

      # Outer block padding: top, right, bottom, left
      spacing:
        padding: ['0', '0', '0', '0']
    
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: false

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: date-title-summary # article-grid
      columns: 2

---
