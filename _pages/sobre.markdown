---
title: "Sobre o Grupo SEED.BR"
---

SEED.BR é um grupo de pesquisa brasileiro 
[certificado no Diretório de Grupos de Pesquisa (DGP) do CNPq](dgp.cnpq.br/dgp/espelhogrupo/8666467021813204) e
vinculado ao Instituto de Computação ([IC](https://computacao.ufba.br/)) 
da Universidade Federal da Bahia ([UFBA](portal.ufba.br)) e 
ao Programa de Pós-graduação em Computação ([PGCOMP-UFBA](https://pgcomp.ufba.br)) do IC-UFBA.


O grupo SEED.BR foi criado no dia 2 de julho de 2021, 
como evolução do grupo [aside@ufba](http://wiki.dcc.ufba.br/Aside/), 
pioneiro na pesquisa em Engenharia de Software e Linguagens de Programação
na Universidade Federal da Bahia ([UFBA](portal.ufba.br)),
e certificado no DGP do CNPq por 18 anos.


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


