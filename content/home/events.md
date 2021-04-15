---
#
# Documentation: 
#    https://wowchemy.com/docs/getting-started/page-builder/#pages
#

widget: pages   # Page type to display. E.g. post, event, or publication.
headless: true
weight: 12

title: "Events"
subtitle: "Upcoming & Recent"

content:
  page_type: event   # Page type to display. E.g. post, event, or publication.
  count: 0          # Choose how much pages you would like to display (0 = all pages)
  offset: 0         # Choose how many pages you would like to offset by
  order: desc       # Page order. Descending (desc) or ascending (asc) date.
  filters:          # Optionally filter posts by a taxonomy term.
    tag: ''
    category: ''
    publication_type: ''
    exclude_featured: false
    exclude_past: false
    exclude_future: false

design:
  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)  
  view: 3


design:
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns: '2'
advanced:
  css_style:
  css_class:
---
