---
title: Home
sections:
  - component: HeroBlock
    content: >-
      Hei! salve... come tu ci sia capitato qui è un mistero.\

      Ma se ci sei, prenditi un momento per leggere e magari ascoltare quello
      che ho da dire...


      Ovvio, ti chiederai su cosa...facile! Su ciò che mi appassiona e mi
      condisce il quotidiano.


      # E' un contenitore delle mie Esperenzie
    section_id: hero
    type: heroblock
  - actions:
      - label: Scrivimi
        url: /contact
    component: ContentBlock
    content: >-
      Vedi il pulsantino sotto? Se vuoi commentare un "articolo", farmi sapere
      la tua opinione su di un podcast che ho pubblicato... ehhh beh, sentiti
      liberissimo di farlo. Pigia violentemente su quel pulsante e scrivimi!
    section_id: about
    title: Altro
    type: contentblock
  - actions:
      - label: View Blog
        url: blog/index.html
    component: PostsBlock
    num_posts_displayed: 4
    section_id: recent-posts
    title: Pubblicazioni recenti
    type: postsblock
menus:
  main:
    identifier: home
    title: Home
    weight: 1
template: home
---

