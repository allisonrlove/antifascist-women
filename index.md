---
title: "Women, Europe, and Antifascism in the Early 20th Century"
layout: base
date: 2025-10-21
header-image: "/assets/images/antifascist-march-mural-hh-2.jpeg"
header-title: Women, Europe, and Antifascism in the Early 20th Century
header-subtitle:
header-tier: hero
header-position: 35% center
---
This website explores the biographies and histories of prominent European and American women antifascist activists from the early 20th century. This project will introduce readers to historical antifascism (1914-1945) by emphasizing the role of European and American women’s actions, writings, organizing, and participation within the transnational antifascism movement of the interwar period.

# Explore the Profiles

Browse the biographies below to learn more about each historical figure.

{% assign essay_pages = site.pages | where_exp: "p", "p.path contains 'essays/'" | where_exp: "p", "p.name == 'index.md'" | where_exp: "p", "p.path != 'essays/index.md'" %}

{% include nav/profile-list profiles=essay_pages %}

