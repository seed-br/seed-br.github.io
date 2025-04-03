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

## Discentes

### Doutorado

<ul class="members-list">
{% for member in site.members %}
  {% if member.role == "Ph.D. student" %}
    {% include member.html year=year member=member %}
  {% endif %}
{% endfor %}
</ul>

### Mestrado

<ul class="members-list">
{% for member in site.members %}
  {% if member.role == "Master's student" %}
    {% include member.html year=year member=member %}
  {% endif %}
{% endfor %}
</ul>


---

## Egressos


<ul class="members-list">
{% for member in site.members %}
  {% if member.role == "Alumni" %}
    {% include member.html year=year member=member %}
  {% endif %}
{% endfor %}
</ul>

### Doutores

+ Simone Amorim, Doutorado 2022
+ Crescencio Lima, Doutorado 2019
+ Debora Nascimento, Doutorado 2017
+ Bruno Silva, Doutorado 2015
+ Rodrigo Souza, Doutorado 2015
+ Antonio Terceiro, Doutorado 2012

### Mestres

+ Angela Peixoto, Mestrado 2023
+ Erinaldo Santos, Mestrado 2023
+ Moara Britto, Mestrado 2021
+ Joenio Marques, Mestrado 2017
+ Leandro Soriano, Mestrado 2014 (MMCC)
+ Antonio Oliveira, Mestrado 2009 (Unifacs)

### Graduação

+ Alberto Lucas, TCC 2025
+ Daniele Valverde, TCC 2025

### Outros

![Alumni](/assets/images/aside-members-3.jpg){:width="100%"}

