---
title: Publications
cms_exclude: true

# View.
# view: citation

# Optional header image (relative to `static/media/` folder).
banner:
  caption: ''
  image: ''


# CUSTOMIZED: Separate paper types
type: landing

sections:
  - block: collection
    id: journal-articles
    content:
      title: Journal Articles
      count: 0 # Show all matching publications
      order: desc
      filters:
        folders:
          - publications
        publication_type: article-journal
    design:
      view: citation
      columns: 1
      spacing:
        padding: ['2rem', '0', '1rem', '0']

  - block: collection
    id: conference-papers
    content:
      title: Conference Papers
      count: 0
      order: desc
      filters:
        folders:
          - publications
        publication_type: conference-paper
    design:
      view: citation
      columns: 1
      spacing:
        padding: ['1rem', '0', '1rem', '0']

  - block: collection
    id: other-publications
    content:
      title: Other Publications
      count: 0
      order: desc
      filters:
        folders:
          - publications
        publication_type: science-outreach
    design:
      view: citation
      columns: 1
      spacing:
        padding: ['1rem', '0', '1rem', '0']
---

