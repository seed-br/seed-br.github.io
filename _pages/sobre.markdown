---
title: "Sobre o Grupo SEED.BR"
---


O grupo de pesquisa SEED.BR foi criado no dia 2 de julho de 2021, 
como evolução do grupo [aside@ufba](http://wiki.dcc.ufba.br/Aside/), 
pioneiro na pesquisa em Engenharia de Software e Linguagens de Programação
na Universidade Federal da Bahia - [UFBA](portal.ufba.br),
certificado e presente no Diretório de Grupos de Pesquisa (DGP) 
do CNPq  por 18 anos.

O grupo SEED.BR e seus pesquisadores atuam no contexto do 
Programa de Pós-graduação em Computação ([PGCOMP-UFBA](https://pgcomp.ufba.br)) 
e do Instituto de Computação ([IC-UFBA](https://computacao.ufba.br/)).

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

### Colaboradores e Egressos

+ [Egressos](http://wiki.dcc.ufba.br/Aside/Pessoas).

