---
title: Opensuse h4ckweek 2024
toc: true
carousels:
  - images: 
    - image: /assets/img/first_measure.jpg
    - image: /assets/img/first_digital.jpg
    - image: /assets/img/ergogen.png
    - image: /assets/img/matrix.png
    - image: /assets/img/routing.png
    - image: /assets/img/switch_reversible_cluster.png
    - image: /assets/img/switch_socket_draw_front.jpg
    - image: /assets/img/nee_drill.jpg
    - image: /assets/img/desk_mess_pulse.jpg
---

{% include carousel.html height="50" unit="%" duration="60" number="1" %}

# Opensuse hackweek 2024 - navigation log

This project is about creating the design of a split mechanical keyboard


[Project page](https://hackweek.opensuse.org/24/projects/build-a-split-keyboard-from-scratch)

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

## Backlog and ideas

* Document design principles
* List used tools
* Progress in PCB design

## Documentation and link collection

- Main keyboard project repo: [Zenga](https://github.com/michelepagot/zenga)
- ZKM config for a hand wired 4 keys something: [nne](https://github.com/michelepagot/zmk-config-nne)
- [Jekyll and github pages](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll)
