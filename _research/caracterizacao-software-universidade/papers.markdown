---
layout: research
title: Caracterização do Software para Pesquisa na Universidade
role: Mestranda
researcher: danifeitosa
advisor: chrisflach
project: casouni
permalink: /research/caracterizacao-software-universidade/papers
---

## **📚 Publicações**

{% assign grouped = site.data.publications | group_by: "year" %}
{% for year in grouped %}
  {% include publications.html year=year filter=page.project %}
{% endfor %}

