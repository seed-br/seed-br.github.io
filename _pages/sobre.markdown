---
title: "Sobre SEED.BR"
---


__SEED.BR__ (_Software Ecosystems, Evolution and Design_) é um grupo de pesquisa brasileiro
[certificado](https://dgp.cnpq.br/dgp/espelhogrupo/795424) e 
vinculado ao Instituto de Computação ([IC](https://computacao.ufba.br/)) 
da Universidade Federal da Bahia ([UFBA](https://portal.ufba.br)) e seu
Programa de Pós-graduação em Computação ([PGCOMP-UFBA](https://pgcomp.ufba.br)).


O grupo SEED.BR foi criado em 2 de julho de 2021, 
como sucessor do grupo de pesquisa __aside@ufba__ (_Software Design and Evolution_),
certificado no DGP-CNPq por 18 anos (2003-2020)
e pioneiro na pesquisa científica em Engenharia de Software na UFBA.


## Membros

### Líder 

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


---

## Egressos


<ul class="members-list">
{% for member in site.members %}
  {% if member.role == "Alumni" %}
    {% include member.html year=year member=member %}
  {% endif %}
{% endfor %}
</ul>

### Doutorado

+ Simone Amorim, Doutorado 2022
+ Crescencio Lima, Doutorado 2019
+ Debora Nascimento, Doutorado 2017
+ Bruno Silva, Doutorado 2015
+ Rodrigo Souza, Doutorado 2015
+ Antonio Terceiro, Doutorado 2012

### Mestrado

+ Angela Peixoto, Mestrado 2023
+ Erinaldo Santos, Mestrado 2023
+ Moara Britto, Mestrado 2021
+ Joenio Marques, Mestrado 2017
+ Leandro Soriano, Mestrado 2014 (MMCC)
+ Antonio Oliveira, Mestrado 2009 (Unifacs)

### Graduação

+ Alberto Lucas, TCC 2025
+ Daniele Valverde, TCC 2025

## Egressos do grupo aSide@ufba

![Alumni](/assets/images/aside-members-3.jpg){:width="100%"}

