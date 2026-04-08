---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 15

title: Portfólió
subtitle: ''

content:
  page_type: portfolio
  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0
  # Filter toolbar (optional).
  # To show all items, set `tag` to "*".
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
    - name: All
      tag: '*'
    - name: Fényképek
      tag: photography
    - name: Gyűjtemények
      tag: collections
    - name: Köztéri művészet
      tag: public-art
    - name: Zene
      tag: music

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 2

  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---
