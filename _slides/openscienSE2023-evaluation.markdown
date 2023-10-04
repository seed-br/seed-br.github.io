---
title: OS - 2023
theme: simple
---

<!-- -------------------------------- -->
<section>

<img src="{{ site.baseurl }}/files/openscienSE/capa-artigo-2.png" width="1200" height="650" style="box-shadow:0px 0px 2px gray;background:white" />
</section>

<!-- -------------------------------- -->
<section>

### Contexto

> A sustentabilidade e FAIRness de software de pesquisa são essenciais para a confiabilidade e a reprodutibilidade pesquisa acadêmica.

</section>

<!-- -------------------------------- -->
<section>

### Objetivo

Caracterizar a prática atual de desenvolvimento de software de pesquisa com grupos de pesquisa da Universidade Federal da
Bahia (UFBA).

</section>

<!-- -------------------------------- -->
<section>

### Fluxo de trabalho

4 etapas na interação com cada grupo pesquisado:

- Palestra
- Entrevista
- **Avaliação**
- Relatório

</section>

<!-- -------------------------------- -->
<section>
### Avaliação

Avaliação da sustentabilidade e aderência aos princípios FAIR (FAIRness) de pelo menos um
software de pesquisa desenvolvido pelo grupo de pesquisa com base em critérios e diretrizes bem definidos

</section>

<!-- -------------------------------- -->
<section data-background="#CBC3E3" data-background-transition="slide">
### Abordagens relacionadas
</section>

<!-- -------------------------------- -->
<section>

<!-- ### Abordagens relacionadas -->

#### Avaliação da Sustentabilidade

O Software Sustainability Institute (SSI) fornece um serviço de avaliação online que pode ser usado para avaliar o software de pesquisa.

Com base em alguns critérios do SSI, propomos um modelo com 16 práticas de desenvolvimento.


</section>

<!-- -------------------------------- -->
<section>

### FAIRness

Princípios FAIR
- **F**indable
- **A**ccessible
- **I**nteroperable
- **R**eusable

</section>

<!-- -------------------------------- -->
<section>

<!-- ### Abordagens relacionadas -->

#### Aderência aos princípios FAIR (FAIRness)

Estudos anteriores adaptaram cada princípio FAIR para dados para software de pesquisa.

Utilizamos os materiais desses trabalhos para avaliação de *FAIR*ness de pesquisa.

<small class="cite">
Anna-Lena Lamprecht et al. 2020. Towards FAIR Principles for Research Software.
Data Science 3, 1 (2020), 37–59.
</small>

<small class="cite">
N.P. Chue Hong, D.S. Katz, M. Barker, A. Lamprecht, C. Martinez, F.E. Psomopoulos,
J. Harrow, L.J. Castro, M. Gruenpeter, P.A. Martinez, and others. 2021. FAIR
principles for research software (FAIR4RS principles). Technical Report. ReSA.
https://doi.org/10.15497/RDA00065
</small>

</section>

<!-- -------------------------------- -->
<section>

<!-- ### Abordagens relacionadas -->

#### Guias e Recomendações

SSI fornece guias para conscientizar pesquisadores e desenvolvedores com dicas e orientações sobre boas práticas de desenvolvimento de software.

The Carpentries oferece treinamentos para conduzir pesquisas eficientes, abertas e reprodutíveis, com recursos relacionados a software de pesquisa.

</section>


<!-- -------------------------------- -->
<section data-background="#ADD8E6" data-background-transition="slide">
### Avaliação piloto

Software `MOSYN`

</section>

<!-- -------------------------------- -->
<section>

<!-- ### Avaliação piloto -->

#### Software `MOSYN`

- Software para análise de grafos variáveis no tempo

- Indicado pelo pesquisador sênior e líder do grupo de pesquisa da área de Física Aplicada entrevistado no projeto piloto

</section>

<!-- -------------------------------- -->
<section data-background="#9ED2BE" data-background-transition="slide">
<!-- ### Avaliação piloto -->

### Avaliação da Sustentabilidade do software

`MOSYN`


</section>

<!-- -------------------------------- -->
<section>

<!-- ### Avaliação piloto -->
<!-- ### Avaliação da Sustentabilidade do software -->

Foram consideradas 16 práticas (P1-P16), organizadas em 5 grupos:
- Práticas Básicas
- Organização
- Qualidade
- Gerência
- Reconhecimento


</section>

<!-- -------------------------------- -->
<section>

<!-- ### Avaliação piloto -->

#### Práticas básicas

<div class="table">

| P  | S/N/P | Comentário                                                                                                                    |
|----|-------|-------------------------------------------------------------------------------------------------------------------------------|
| P1 | S     | O software está disponibilizado em um repositório público no GitHub                                                           |
| P2 | S     | O controle de versão é implementado por utilizar o GitHub como plataforma de hospedagem                                       |
| P3 | P     | Um arquivo declarando a licença MIT. Porém não está claro se as permissões se aplicam a qualquer arquivo fonte no repositório |
| P4 | N     | O repositório não menciona um DOI associado a ele mas pode ser encontrado no GitHub pelo nome                                 |

</div>

<small class="cite">
(P1) Hospedagem do software, (P2) Controle de versão, (P3) Licenças de software e (P4) Registro do software
</small>

</section>

<!-- -------------------------------- -->
<section>

<!-- ### Avaliação piloto -->

#### Organização

<div class="table">

| P  | S/N/P | Comentário                                                                                                                         |
|----|-------|------------------------------------------------------------------------------------------------------------------------------------|
| P5 | S     | A estrutura de pastas está organizada de forma descritiva e permite inferir o conteúdo                                             |
| P6 | S     | Apesar de não haver documentação explícita, o software utiliza o formato de entrada e saída que facilita a integração com o MATLAB |
| P7 | P     | O projeto utiliza o GitHub pages mas as informações estão incompletas e algumas URLs direcionam para um destino não válido         |

</div>

<small class="cite">
(P5) Estrutura de arquivos, (P6) Padronização e (P7) Documentação
</small>

</section>

<!-- -------------------------------- -->
<section>

<!-- ### Avaliação piloto -->

#### Qualidade

<div class="table">


| P  	| S/N/P 	| Comentário                                                                                                                                     	|
|----	|-------	|------------------------------------------------------------------------------------------------------------------------------------------------	|
| P8 	| N     	| Não há testes automatizados para o software                                                                                                    	|
| P9 	| P     	| Todos os pull requests listados no repositórios foram aprovados pelo próprio autor, sugerindo que não houve revisão de código por outra pessoa 	|

</div>

<small class="cite">
(P8) Teste automatizado e (P9) Revisão de código
</small>

</section>


<!-- -------------------------------- -->
<section>

<!-- ### Avaliação piloto -->

#### Gerência

<div class="table">


| P   	| S/N/P 	| Comentário                                                                                                         	|
|-----	|-------	|--------------------------------------------------------------------------------------------------------------------	|
| P10 	| S     	| O projeto aproveita a funcionalidade de rastreamento de bugs e tarefas disponível no GitHub                        	|
| P11 	| N     	| Não encontramos tarefas automatizadas no projeto                                                                   	|
| P12 	| N     	| Não há integração contínua. Por ser um plugin instalado manualmente no MATLAB, a implantação contínua não é viável 	|
| P13 	| N     	| O projeto não utiliza a funcionalidade de lançamento de versões no repositório do GitHub                           	|

</div>

<small class="cite">
(P10) Issue Tracker e (P11) Automatização de tarefas, (P12) CI/CD e (P13) Lançamento de versões
</small>

</section>

<!-- -------------------------------- -->
<section>

<!-- ### Avaliação piloto -->

#### Reconhecimento

<div class="table">

| P   	| S/N/P 	| Comentário                                                                               	|
|-----	|-------	|------------------------------------------------------------------------------------------	|
| P14 	| N     	| Há apenas um desenvolvedor como autor                                                    	|
| P15 	| N     	| Não encontramos divulgação em eventos científicos                                        	|
| P16 	| N     	| Não encontramos citação do software em publicações                                       	|

</div>

<small class="cite">
(P14) Comunidade, (P15) Divulgação e (P16) Citação de software
</small>

</section>

<!-- -------------------------------- -->
<section data-background="#F7D9C4" data-background-transition="slide">
<!-- ### Avaliação piloto -->

### Avaliação de FAIRness do software

`MOSYN`


</section>

<!-- -------------------------------- -->
<section>

<!-- ### Avaliação piloto -->
<!-- ### Avaliação de FAIRness do software -->

Avaliamos o software `MOSYN` identificando se o software incorporou os princípios FAIR:

- **F**indable
- **A**ccessible
- **I**nteroperable
- **R**eusable

</section>

<!-- -------------------------------- -->
<section>

<!-- ### Avaliação piloto -->

#### Localizável **F**indable (1)

<div class="table">

|      	| Descrição                                                                                                               	| S/N/P 	|
|------	|-------------------------------------------------------------------------------------------------------------------------	|-------	|
| F    	| O software e seus metadados associados são facilmente encontrados tanto por humanos quanto por máquinas                 	| P     	|
| F1   	| O software recebe um identificador globalmente único e persistente                                                      	| P     	|
| F1.1 	| Aos componentes do software que representam diferentes níveis de granularidade são atribuídos identificadores distintos 	| S     	|
| F1.2 	| As diferentes versões do software recebem identificadores distintos                                                     	| S     	|

</div>

</section>

<!-- -------------------------------- -->
<section>

<!-- ### Avaliação piloto -->

#### Localizável **F**indable (2)

<div class="table">

|      	| Descrição                                                                                                               	| S/N/P 	|
|------	|-------------------------------------------------------------------------------------------------------------------------	|-------	|
| F2   	| O software é descrito com metadados detalhados                                                                          	| P     	|
| F3   	| Os metadados contêm de forma clara e explícita o identificador do software que descrevem                                	| P     	|
| F4   	| Os metadados seguem os princípios FAIR, são pesquisáveis e indexáveis                                                   	| P     	|

</div>

</section>

<!-- -------------------------------- -->
<section>

#### Acessível **A**ccessible

<div class="table">

|      	| Descrição                                                                                                     	| S/N/P 	|
|------	|---------------------------------------------------------------------------------------------------------------	|-------	|
| A    	| O software e seus metadados podem ser obtidos através de protocolos padronizados                              	| P     	|
| A1   	| O software é pode ser obtido por meio de seu identificador utilizando um protocolo de comunicação padronizado 	| S     	|
| A1.1 	| O protocolo é aberto, gratuito e universalmente implementável                                                 	| S     	|
| A1.2 	| O protocolo permite procedimentos de autenticação e autorização, quando necessário                            	| S     	|
| A2   	| Os metadados são acessíveis, mesmo quando o software não está mais disponível                                 	| S     	|

</div>

</section>

<!-- -------------------------------- -->
<section>

#### Interoperável **I**nteroperable

<div class="table">

|      	| Descrição                                                                                                                             	| S/N/P 	|
|------	|---------------------------------------------------------------------------------------------------------------------------------------	|-------	|
| I    	| O software interopera com outros softwares, trocando dados e/ou metadados através da interação via APIs, descrito por meio de padrões 	| P     	|
| I1   	| O software lê, escreve e troca dados de acordo com padrões da comunidade relacionados ao domínio                                      	| P     	|
| I2   	| O software inclui referências qualificadas a outros objetos                                                                           	| P     	|

</div>

</section>

<!-- -------------------------------- -->
<section>

#### Reusável **R**eusable

<div class="table">

|      	| Descrição                                                                                                                                     	| S/N/P 	|
|------	|-----------------------------------------------------------------------------------------------------------------------------------------------	|-------	|
| R    	| O software é utilizável (pode ser executado) e reutilizável (pode ser compreendido, modificado, aprimorado ou incorporado a outros softwares) 	| P     	|
| R1   	| O software é descrito com uma variedade de atributos precisos e relevantes                                                                    	| P     	|
| R1.1 	| É atribuída uma licença clara e acessível ao software                                                                                         	| S     	|
| R1.2 	| O software possui informações detalhadas de procedência                                                                                       	| P     	|
| R2   	| O software inclui referências qualificadas a outros software                                                                                  	| P     	|
| R3   	| O software atende aos padrões relevantes da comunidade do domínio                                                                             	| S     	|

</div>

</section>

<!-- -------------------------------- -->
<section>

<!-- ### Discussion -->

### Limitação

A avaliação foi realizada manualmente, por meio da inspeção de informações disponíveis no repositório público do software

</section>

<section data-background="#CDF0F2" data-background-transition="slide">
### Conclusões
</section>

<!-- -------------------------------- -->
<section>

<!-- ### Conclusões (1)-->

> O estudo piloto mostrou a viabilidade de uma avaliação da sustentabilidade e FAIRness de um software de pesquisa


</section>

<!-- -------------------------------- -->
<section>

<!-- ### Conclusões (2)-->

> Esperamos que os resultados preliminares de nosso estudo piloto inspirem os pesquisadores a refletir sobre a sustentabilidade e FAIRness de seu software de pesquisa, práticas de engenharia de software que podem ajudá-los a alcançá-los, desenvolver ou refinar modelos de avaliação e contribuir para sua adoção


</section>

<section>
### Understanding Sustainability and FAIRness of Research Software


#### (*) Christina von Flach (IC-UFBA): flach@ufba.br

#### Daniela Feitosa (PGCOMP-UFBA)
#### Joenio Costa (LISIS-France)

Campo Grande, 25/9/2023

</section>
