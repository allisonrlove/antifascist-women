---
title: Biographies
layout: base
header-title: Biographies
---

# Biographies of Anti-Fascist Women in Europe in the Early 20th Century

{% assign essay_pages = site.pages | where_exp: "p", "p.path contains 'essays/'" | where_exp: "p", "p.name == 'index.md'" | where_exp: "p", "p.path != 'essays/index.md'" %}

{% include nav/profile-list profiles=essay_pages %}
