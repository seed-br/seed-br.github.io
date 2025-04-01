---
title: "Sobre o Grupo SEED.BR"
---


SEED.BR é um grupo de pesquisa brasileiro
[certificado](https://dgp.cnpq.br/dgp/espelhogrupo/795424)
e presente no Diretório de Grupos de Pesquisa do Conselho Nacional de Desenvolvimento Científico e Tecnológico ([DGP-CNPq](https://lattes.cnpq.br/web/dgp)),
vinculado ao Instituto de Computação ([IC](https://computacao.ufba.br/)) 
da Universidade Federal da Bahia ([UFBA](https://portal.ufba.br)) e 
ao Programa de Pós-graduação em Computação ([PGCOMP-UFBA](https://pgcomp.ufba.br)) do IC-UFBA.


O grupo SEED.BR foi criado no dia 2 de julho de 2021, 
como evolução do grupo **aside@ufba**,
certificado no DGP-CNPq por 18 anos (2003-2020),
e pioneiro na pesquisa científica e tecnológica em Engenharia de Software e Linguagens de Programação
na UFBA.


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


