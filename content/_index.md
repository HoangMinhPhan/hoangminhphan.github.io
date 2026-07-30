---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-07-30
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: |
        I am a PhD researcher at **KU Leuven**, working in the **MeBioS Postharvest group** led by **[Prof. Bart Nicolai](https://www.kuleuven.be/wieiswie/en/person/00014537)**.
        My research is at the intersection of postharvest technology, food engineering, advanced predictive modeling, and applied data science to improve the sustainability of the food cold chain.
        I focus on building a **[digital twin](https://www.ibm.com/think/topics/digital-twin)** of a commercial cold storage system for pear fruit — a virtual replica of the physical system that
        enables smarter control, more accurate prediction, and systematic optimization of both **fruit quality** and **storage operations**.

        This work is part of the [ENOUGH Project (H2020 EU)](https://enough-emissions.eu/), a European initiative driving sustainable innovation across the food sector.

        ### My Background
        Driven by a passion for advancing sustainable food systems, I pursued a **[joint Master's in Food Technology (Magna cum laude)](https://www.iupfood.be/)** at **KU Leuven and Ghent University, Belgium**. 
        My **[master's thesis](https://doi.org/10.1016/j.compag.2023.108142)** bridged AI and postharvest science — applying _deep learning_ and _X-ray CT imaging_ 
        to develop a non-destructive sorting technology for pears affected by internal browning disorder, translating advanced AI techniques into practical postharvest sorting solutions. Earlier, my foundation 
        in food science was built at the **University of Technology (HCMUT-VNU), Vietnam**, where I earned a **B.Eng in Food Technology (First Class Honours)**. There, I developed core engineering competencies 
        in process design, quality management, and food systems.

        Beyond academic research, I had worked as a **Chemical Engineer in the food industry**, leading technology transfer & CapEx projects across multiple production lines. This industry chapter gave me a
        perspective that runs from bench scale all the way to the factory floor, and a deep appreciation for what it takes to make innovation work in practice.

        Outside of the professional world, I enjoy reading, watching anime, learn new things, and exploring culinary cultures around the world. My favourite Vietnamese dish is
        [Bún Bò Huế](https://en.wikipedia.org/wiki/B%C3%BAn_b%C3%B2_Hu%E1%BA%BF) — a bold, spicy noodle soup from Central Vietnam that I highly recommend. More broadly, noodles in all their forms are close to my
        heart. I also like staying active on the badminton court.

        ### Research & Expertise
        - **Digital twins & predictive modeling** — food systems monitoring, quality prediction, and operational optimisation.
        - **Postharvest technology & cold chain** — cold storage, fruit quality management, shelf life extension, and energy efficiency.
        - **Food processing & engineering** — process design, optimisation, and technology transfer.
        - **Applied data science & AI** — machine learning, deep learning, statistical modeling, and uncertainty quantification.

        ### What Drives Me
        I believe the most meaningful progress in (agri)-food systems comes from bridging rigorous science with practical engineering. Whether through research, consultancy, or hands-on engineering, my goal is
        to help build systems that are **smarter**, **more efficient**, and **more sustainable** — from the storage room to the supply chain.

        _**If you are working on challenges at the intersection of food, technology, and sustainability, I would love to connect.**_

    # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/cvHoangMinhPhan.pdf
      headings:
        about: 'About me'

    design:
      # Customise alignment of biography text
      biography:
        style: "text-align: justify; text-justify: inter-word; font-size: 1rem; line-height: 1.5;"
      spacing:
        padding: ['0', '0', '2rem', '0'] # [top, right, bottom, left]
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
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

 
---
