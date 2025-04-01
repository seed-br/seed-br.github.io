---
title: "Sobre o Grupo SEED.BR"
---


__SEED.BR__ (_Software Ecosystems, Evolution and Design_) é um grupo de pesquisa brasileiro
[certificado](https://dgp.cnpq.br/dgp/espelhogrupo/795424) e 
vinculado ao Instituto de Computação ([IC](https://computacao.ufba.br/)) 
da Universidade Federal da Bahia ([UFBA](https://portal.ufba.br)) e seu
Programa de Pós-graduação em Computação ([PGCOMP-UFBA](https://pgcomp.ufba.br)).


O grupo SEED.BR foi criado em 2 de julho de 2021, 
como sucessor do grupo de pesquisa __aside@ufba__ (_Software Design and Evolution_),
certificado no DGP-CNPq por 18 anos (2003-2020)
e pioneiro na pesquisa científica e tecnológica em Engenharia de Software e Linguagens de Programação na UFBA.


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

### Graduação


### Colaboradores
 

### Egressos

<ul class="members-list">
{% for member in site.members %}
  {% if member.role == "Alumni" %}
    {% include member.html year=year member=member %}
  {% endif %}
{% endfor %}
</ul>

+ [Egressos do grupo aside@ufba](http://wiki.dcc.ufba.br/Aside/Pessoas).


