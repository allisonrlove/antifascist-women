---
title: "Women, Europe, and Antifascism in the Early 20th Century"
layout: base
date: 2025-10-21
header-image: "/assets/images/antifascist-march-mural-hh-2.jpeg"
header-title: Women, Europe, and Antifascism in the Early 20th Century
header-subtitle: >-
  This project explores the biographies and histories of prominent European and
  American women antifascist activists from the early 20th century, emphasizing
  their actions, writings, organizing, and participation in transnational
  antifascism between 1914 and 1945.
header-position: 35% center
header-height: 79vh
---

## Explore the Profiles

Browse the biographies below to learn more about each historical figure.

{% assign essay_pages = site.pages | where_exp: "p", "p.path contains 'essays/'" | where_exp: "p", "p.name == 'index.md'" | where_exp: "p", "p.path != 'essays/index.md'" %}

{% include nav/profile-list profiles=essay_pages %}

