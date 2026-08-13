---
title: "Membros"
---


## Líder do grupo SEED.BR 

<ul class="members-list">
{% for member in site.members %}
  {% if member.role == "Research Group Leader" %}
    {% include member.html year=year member=member %}
  {% endif %}
{% endfor %}
</ul>

## Estudantes

<ul class="members-list">
{% for member in site.members %}
  {% if member.role == "Master's student" %}
    {% include member.html year=year member=member %}
  {% endif %}
{% endfor %}
</ul>

<ul class="members-list">
{% for member in site.members %}
  {% if member.role == "Ph.D. student" %}
    {% include member.html year=year member=member %}
  {% endif %}
{% endfor %}
</ul>

---

## Egressos

### Doutores

+ Simone Amorim, Doutorado 2022
+ Crescencio Lima, Doutorado 2019
+ Debora Nascimento, Doutorado 2017
+ Bruno Silva, Doutorado 2015
+ Rodrigo Souza, Doutorado 2015
+ Antonio Terceiro, Doutorado 2012


