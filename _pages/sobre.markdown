---
title: "Sobre o Grupo SEED.BR"
---


O grupo de pesquisa SEED.BR foi criado no dia 2 de julho de 2021, dando continuidade a uma longa e maravilhosa jornada de 18 anos do grupo [aside@ufba](http://wiki.dcc.ufba.br/Aside/), pioneiro na pesquisa em Engenharia de Software e Linguagens de Programação na Computação-UFBA). 

O grupo de pesquisa SEED.BR e seus pesquisadores caminham ao lado do [PGCOMP-UFBA](https://pgcomp.ufba.br) e do [Instituto de Computação](https://computacao.ufba.br/) da Universidade Federal da Bahia.

## Líder

<ul class="members-list">
{% for member in site.members %}
  {% if member.role == "Research Group Leader" %}
    {% include member.html year=year member=member %}
  {% endif %}
{% endfor %}
</ul>

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
