---
title: Home
sections:
  - component: hero_block.html
    content: 'it''s 2020, what will we do?'
    section_id: hero
    type: heroblock
  - actions:
      - label: View Blog
        url: blog/index.html
    component: posts_block.html
    num_posts_displayed: 4
    section_id: recent-posts
    title: posts
    type: postsblock
  - actions:
      - label: Contact Me
        url: /contact
    component: content_block.html
    content: do you know what drives you? me neither.
    section_id: about
    title: about
    type: contentblock
menus:
  main:
    title: home
    weight: 1
layout: home
---

