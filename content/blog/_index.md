---
title: Blog
description: |
  
author: ""
show_post_thumbnail: true
thumbnail_left: true # for list-sidebar only
show_author_byline: true
show_post_date: true
show_button_links: false
# for listing page layout
layout: list-sidebar # list, list-sidebar, list-grid

# for list-sidebar layout
sidebar: 
  title: Blog
  description: |
    Carly is... Read her thoughts on... 
    ___
    #### [All Tags](/tags/)
    #### [RSS](/index.xml)

  author: ""
  text_link_label: #RSS
  text_link_url: #/index.xml
  categories_link: false
  series_link: false
  tags_link: false
  show_sidebar_adunit: true # show ad container

# set up common front matter for all pages inside blog/
cascade:
  author: "Carly Hilbert"
  show_author_byline: true
  show_post_date: true
  show_comments: true # see site config to choose Disqus or Utterances
  # for single-sidebar layout
  sidebar:
    text_link_label: View recent posts
    text_link_url: /blog/
    show_sidebar_adunit: false # show ad container
---

** No content below YAML for the blog _index. This file provides front matter for the listing page layout and sidebar content. It is also a branch bundle, and all settings under `cascade` provide front matter for all pages inside blog/. You may still override any of these by changing them in a page's front matter.**
