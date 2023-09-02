---
title: Sustentabilidade técnica de software acadêmico
theme: simple
---

<!-- -------------------------------- -->

<section>
### Sustentabilidade técnica de software acadêmico no domínio de ferramentas de análise estática de código-fonte

</section>

<!-- -------------------------------- -->

<section>
#### Sustentabilidade técnica de software acadêmico no domínio de ferramentas de análise estática de código-fonte

<small>
_Apresentação para banca examinadora da defesa de mestrado do Programa de
Pós-graduação em Ciência da Computação da Universidade Federal da Bahia,
Salvador-Bahia, 19 de Dezembro de 2017._
</small>

Joenio Marques da Costa

Orientadora: Dra. Christina von Flach G. Chavez<br/>
Co-orientador: Dr. Paulo Roberto Miranda Meirelles
</section>

<!-- -------------------------------- -->

<section>
### Agenda

1. Conceitos, motivação e contextualização
1. Objetivos, estratégia e questão de pesquisa
1. Estudos realizados e seus resultados
1. Síntese de resultados e conclusões
1. Recomendações e trabalhos futuros
</section>

<!-- -------------------------------- -->

<section>
### Software acadêmico

Todo software usado para coletar, processar ou analisar resultados de pesquisas
com intenção de publicação na literatura acadêmica, incluindo desde protótipos
escritos pelos próprios cientistas, a produtos completos desenvolvidos
profissionalmente.

<small class="cite">
ALLEN, A. et al. **Engineering academic software (dagstuhl perspectives workshop
16252)**. In: Dagstuhl Manifestos. [S.l.]: Schloss Dagstuhl-Leibniz-Zentrum fuer
Informatik, 2017.
</small>
</section>

<!-- -------------------------------- -->

<section>
#### Modelos de desenvolvimento de software acadêmico

* Software como serviço de suporte
* Software para crédito acadêmico
  * Software Incidental
  * Prática de software paralela
  * Um subcampo de software

<small class="cite">
HOWISON, J.; HERBSLEB, J. D. **Scientific software production: incentives and
collaboration**. In: Proceedings of the ACM 2011 conference on Computer supported
cooperative work. [S.l.: s.n.], 2011.
</small>
</section>

<!-- -------------------------------- -->

<section>
#### Modelo de processo de software acadêmico

<img src="{{ site.baseurl }}/files/process-model-scientific-software.png" />

<small class="cite">
HOWISON, J. et al. **Understanding the scientific software ecosystem and its
impact: Current and future measures**. Research Evaluation, v. 24, n. 4, p.
454–470, 2015.
</small>
</section>

<!-- -------------------------------- -->

<section>
#### Incentivos de reputação e práticas de software acadêmico

<img src="{{ site.baseurl }}/files/scientific-reputation-diagram.png" style="background: white" />

<small class="cite">
HOWISON, J.; HERBSLEB, J. D. **Scientific software production: incentives and
collaboration**. In: Proceedings of the ACM 2011 conference on Computer supported
cooperative work. [S.l.: s.n.], 2011.
</small>
</section>

<!-- -------------------------------- -->

<section>
**Ecossistema de Software** (_Software Ecosystem_) - SECO é interação entre
diversos atores numa plataforma tecnológica comum, resultando em novas soluções
de software ou novos serviços.

<small class="cite">
MANIKAS, K.; HANSEN, K. M. **Software ecosystems–a systematic literature
review**. Journal of Systems and Software, Elsevier, v. 86, n. 5, p.
1294–1306, 2013.
</small>
</section>

<!-- -------------------------------- -->

<section>
> 56% dos pesquisadores de todas as áreas do Reino Unido desenvolvem software acadêmico.
<small class="cite">
HETTRICK, S. et al. **UK Research Software Survey 2014**. 2014.
</small>
</section>

<!-- -------------------------------- -->

<section>
> 90% dos pesquisadores na astronomia desenvolvem suas próprias ferramentas de software.
<small class="cite">
MOMCHEVA, I.; TOLLERUD, E. **Software use in astronomy: an informal
survey**. arXiv preprint arXiv:1507.03989, 2015.
</small>
</section>

<!-- -------------------------------- -->

<section>
> Muitas pesquisas não mencionam sequer o uso de software acadêmico em suas publicações.
<small class="cite">
HOWISON, J.; BULLARD, J. **Software in the scientific literature: Problems with
seeing, finding, and using software mentioned in the biology literature**.
Journal of the Association for Information Science and Technology, v. 67, n. 9,
p. 2137–2155, 2016.
</section>

<!-- -------------------------------- -->

<section>
> Grande parte dos pesquisadores não sabem o quão confiável seus projetos de software são.
<small class="cite">
MERALI, Z. **Computational science: Error, why scientific programming does not
compute**. Nature, Nature Publishing Group, v. 467, n. 7317, p. 775–777, oct
2010.
</section>

<!-- -------------------------------- -->

<section>
O software acadêmico sofre de um fenômeno conhecido por **Desordem Caótica Disfuncional**
(_"dysfunctional chaotic churn"_) - DCD.

<small class="cite">
HOWISON, J. et al. **Understanding the scientific software ecosystem and its
impact: Current and future measures**. Research Evaluation, v. 24, n. 4, p.
454–470, 2015.
</small>
</section>

<!-- -------------------------------- -->

<section>
#### Desordem Caótica Disfuncional (DCD):

1. Existência de muitos projetos com poucos usuários;
1. Projetos com ciclos de vida curtos que se encerram junto ao financiamento inicial;
1. Comunidades de usuários desconectadas e paralelas;
1. Incompatibilidades entre os projetos de maneira persistente e imutável;
1. Tentativas constantes e aparentemente não coordenadas de "reiniciar" tudo (_re-boots_).
</section>

<!-- -------------------------------- -->

<section>
---

#### Manifesto from Dagstuhl Perspectives Workshop 16252

### Engineering Academic Software

---

> "A qualidade e a **sustentabilidade** do software acadêmico deve ser avaliado tanto à _priori_ quanto à _posteriori_."

<small class="cite">
ALLEN, A. et al. **Engineering academic software (dagstuhl perspectives workshop
16252)**. In: Dagstuhl Manifestos. [S.l.]: Schloss Dagstuhl-Leibniz-Zentrum fuer
Informatik, 2017.
</small>
</section>

<!-- -------------------------------- -->

<section>
## Sustentabilidade

individual - social - econômica - ambiental - **técnica**

<small class="cite">
BECKER, C. et al. **The karlskrona manifesto for sustainability design**. CoRR,
abs/1410.6968, 2014.
</small>
</section>

<!-- -------------------------------- -->

<section>
### Sustentabilidade técnica de software

A dimensão técnica diz respeito a capacidade do software de perdurar e de
continuar sendo suportado ao longo do tempo, implicando em qualidades de
longevidade e manutenção.

</section>

<!-- -------------------------------- -->

<section>
### Como medir sustentabilidade de software?

## Qual perspectiva usar?

<!-- sustentabilidade como um princípio a ser seguido, um requisito não-funcional, como uma propriedade emergente -->
<small class="cite">
VENTERS, C. C. et al. **Software sustainability: The modern tower of babel**. In:
CEUR Workshop Proceedings. [S.l.: s.n.], 2014.
</small>
</section>

<!-- -------------------------------- -->

<section>
### Questão de pesquisa

Como a DCD pode explicar a **sustentabilidade** técnica dos projetos do
ecossistema de software acadêmico de análise estática em termos de
publicização, reconhecimento e estágio de evolução?
</section>

<!-- -------------------------------- -->

<section>
### Estratégia de pesquisa

Estudo de caso exploratório, características:

* Foco num fenômeno, organização ou sistema em particular;
* Baixo nível de generalização e alto realismo do contexto;
* Sem intervenção do pesquisador no ambiente.

<small class="cite">
STOL, K.-J.; FITZGERALD, B. **A holistic overview of software engineering
research strategies**. In: 3rd International Workshop on Conducting Empirical
Studies in Industry.  [S.l.: s.n.], 2015.
</small>
</section>

<!-- -------------------------------- -->

<section>
<img src="{{ site.baseurl }}/files/estrategia-pesquisa.png" style="background:white;padding:10px" />
</section>

<!-- -------------------------------- -->

<section>
#### Estudo 1:

### Publicização de software acadêmico de análise estática
</section>

<!-- -------------------------------- -->

<section>
### Análise estática

Análise estática é a atividade de obter informações acerca de um programa a
partir do seu código-fonte, tem suas origens nos estudos e desenvolvimentos de
compiladores.

<small class="cite">
CRUZ, D. d.; HENRIQUES, P. R.; PINTO, J. S. **Code analysis: Past and present**. 2009.
</small>
</section>

<!-- -------------------------------- -->

<section>
<img src="{{ site.baseurl }}/files/estudo1-etapas.png" width="60%" style="background:white" />
</section>

<!-- -------------------------------- -->

<section>
Revisão de literatura nas conferências ASE e SCAM

<img src="{{ site.baseurl }}/files/revisao-literatura.png"  width="80%" style="background:white" />
</section>

<!-- -------------------------------- -->

<section>
Escopo

* Publicações das conferências ASE e SCAM
* Incluindo todas as ediçoes até 2015
  * 25 edições da conferência ASE
  * 15 edições da conferência SCAM
</section>

<!-- -------------------------------- -->

<section>
Triagem automática

| Critério               | String                    |
| ---------------------- | ------------------------- |
| Menciona projeto       | _tool_ ou _framework_     |
| Disponibiliza download | _download_ ou _available_ |
| Informa URL            | _http_, _https_ ou _ftp_  |
| Análise estática       | _static analysis_ ou _parser_ |

</section>

<!-- -------------------------------- -->

<section>
Extração

| Critério      | Explicação                                                        |
| ------------- | ----------------------------------------------------------------- |
| Identificável | É possível identificar software entre as contribuições do artigo? |
| Disponível    | Podemos encontrar menção a URL do software para download?         |

</section>

<!-- -------------------------------- -->

<section>
#### Resultados da revisão de literatura do estudo 1

<img src="{{ site.baseurl }}/files/artigos-com-software-por-ano.png" />

**61 artigos** com publicação de **60 projetos** de software acadêmico de análise estática.
</section>

<!-- -------------------------------- -->

<section>
✓ Nome, URL, Artigo, Conferência, Ano

✗ Descrição, Acesso, Distribuição, Licença, Código fonte
</section>

<!-- -------------------------------- -->

<section>
Caracterização dos **60** projetos em relação a disponibilidade de download.

| Download                   | Número | Proporção |
| -------------------------- | ------ | --------- |
| Disponível para download   | 36     | 60%       |
| Indisponível para download | 24     | 40%       |

</section>

<!-- -------------------------------- -->

<section>
Caracterização dos **36** projetos disponíveis para download em relação à disponibilidade de código fonte.

| Código fonte                   | Número | Proporção |
| ------------------------------ | ------ | --------- |
| Disponibiliza código fonte     | 34     | ~94%      |
| Não disponibiliza código fonte | 2      | ~6%       |

</section>

<!-- -------------------------------- -->

<section>
Caracterização dos **34** projetos com código fonte disponível em relação ao uso de licenças de software livre.

| Uso de licenças livres            | Número | Proporção |
| --------------------------------- | ------ | --------- |
| Utiliza licença de software livre | 21     | ~62%      |
| Não adota licença alguma          | 13     | ~38%      |

</section>

<!-- -------------------------------- -->

<section>
Caracterização em relação à linguagem de programação.

<img src="{{ site.baseurl }}/files/linguagens.png" />
</section>

<!-- -------------------------------- -->

<section>
#### Estudo 2:

### Reconhecimento de software acadêmico de análise estática
</section>

<!-- -------------------------------- -->

<section>
### Menção

O número e tipo de menção foi utilizado como _proxy_ para medir o grau
de reconhecimento ao software acadêmico.
</section>

<!-- -------------------------------- -->

<section>
Revisão de literatura nas bases ACM e IEEE

<img width="90%" src="{{ site.baseurl }}/files/estudo2-revisao-literatura.png" style="background:white" />
</section>

<!-- -------------------------------- -->

<section>
Busca

| String de busca para o software s6                       |
| -------------------------------------------------------- |
| content.ftsec:(+civl +concurrency +intermediate +verification +language) |
| ('concurrency intermediate verification') AND CIVL |

...
</section>

<!-- -------------------------------- -->

<section>
Triagem

Inspeção manual dos artigos em busca de ocorrências ao nome do projeto (menção) em todo o conteúdo.
</section>

<!-- -------------------------------- -->

<section>
Keywording

| ID | Artigo | Anotação                           |
| -- | ------ | ---------------------------------- |
| s3 | p250   | Cita o software como exemplo de ferramenta para recomendação de API numa tabela comparativa. |
| s3 | p546   | Nenhuma referência ao nome do software encontrado no texto. |
| s3 | p799   | Cita o software como trabalho relacionado. |

</section>

<!-- -------------------------------- -->

<section>
Extração

Cada menção foi classificada a partir do esquema para classificação de menções elaborado na fase de Keywording.
</section>

<!-- -------------------------------- -->

<section>
<img width="100%" src="{{ site.baseurl }}/files/estudo2-revisao-literatura-resultados.png" style="background:white" />
</section>

<!-- -------------------------------- -->

<section>
| Tipo de menção                          | Número | Proporção |
| --------------------------------------- | ------ | --------- |
| Mencionado apenas na publicação inicial | 14     | ~23%      |
| Utilizado apenas na publicação inicial  | 16     | ~27%      |
| Utilizado em outros estudos             | 12     | 20%       |
| Recebe contribuição de outros estudos   | 18     | 30%       |

</section>

<!-- -------------------------------- -->

<section>
#### Estudo 3:

### Ciclo de vida de software acadêmico de análise estática

</section>

<!-- -------------------------------- -->

<section>
#### Ciclo de vida de software

<img src="{{ site.baseurl }}/files/staged-model-foss-cycle.png" style="box-shadow:0px 0px 2px gray;background:white" />

<small class="cite">
CAPILUPPI, A. et al. **Adapting the staged model for software evolution to
free/libre/open source software**. In: Ninth international workshop on Principles
of software evolution: in conjunction with the 6th ESEC/FSE joint meeting.
[S.l.: s.n.], 2007.
</small>
</section>

<!-- -------------------------------- -->

<section>
* Número de lançamentos de cada projeto
* Número de versão, data e URL para código fonte de cada lançamento
* Download de todos(*) os lançamentos com código fonte disponível
  * (*) Apenas aqueles escritos em C, C++ ou Java
</section>

<!-- -------------------------------- -->

<section>
<img src="{{ site.baseurl }}/files/analizo.png" style="box-shadow: 0px 0px 5px gray; border-radius: 5px" />
<br/>
[analizo.org](http://analizo.org)

<small class="cite">
Terceiro, A. et al. **Analizo: an extensible multi-language source code
analysis and visualization toolkit**. In: CBSOFT-Ferramentas. [S.l.: s.n.],
2010.
</small>
</section>

<!-- -------------------------------- -->

<section>
| Projetos                                                   | Estágio                 |
| ------------------------------------------------------ --- | ----------------------- |
| Sem informação sobre lançamentos                           | Desenvolvimento inicial |
| Com apenas um lançamento                                   | Desenvolvimento inicial |
| Indisponível para download                                 | Encerrado               |
| Tornaram-se indisponíveis durante a realização da pesquisa | Descontinuado           |

</section>

<!-- -------------------------------- -->

<section>
Os demais projetos com informações sobre lançamento e código fonte disponível
foram analisados para coleta das seguintes métricas:

* Número de módulos
* Número de linhas de código fonte (eloc)
</section>

<!-- -------------------------------- -->

<section>
| Estágio de evolução                                 | Número | Proporção |
| --------------------------------------------------- | ------ | --------- |
| Inicial, descontinuado ou encerrado                 | 47     | 78%       |
| Evolução ou manutenção                              | 8      | 14%       |
| Indícios de estágio inicial, evoluçao ou manutenção | 5      | 8%        |

</section>

<!-- -------------------------------- -->

<section>
### Síntese de resultados

</section>

<!-- -------------------------------- -->

<section>
O reconhecimento ao software acadêmico de análise estática vem crescendo

<img src="{{ site.baseurl }}/files/mentions-trend.png" style="box-shadow: 0px 0px 5px gray; border-radius: 5px; padding: 10px" />
</section>

<!-- -------------------------------- -->

<section>
Os projetos com licenças de software livre possuem maior reconhecimento

<img width="80%" src="{{ site.baseurl }}/files/license-vs-mentions.png" style="box-shadow: 0px 0px 5px gray; border-radius: 5px; padding: 15px" />
</section>

<!-- -------------------------------- -->

<section>
O crescimento médio no número de módulos confirma a lei de "Crescimento Contínuo" do software

<img width="65%" src="{{ site.baseurl }}/files/modules-evolution-average.png" style="box-shadow: 0px 0px 5px gray; border-radius: 5px" />
</section>

<!-- -------------------------------- -->

<section>
**Questão:** Como a desordem caótica disfuncional (DCD) pode explicar a
sustentabilidade técnica dos projetos do ecossistema de software acadêmico de
análise estática em termos de publicização, reconhecimento e estágio de
evolução?
</section>

<!-- -------------------------------- -->

<section>
<ul style="list-style-type: none">
  <li><b>C1:</b> Existência de muitos projetos com poucos usuários;</li>
  <li><b>C2:</b> Projetos com ciclos de vida curtos que se encerram junto ao financiamento inicial;</li>
  <li><b>C3:</b> Comunidades de usuários desconectadas e paralelas;</li>
  <li><b>C4:</b> Incompatibilidades entre os projetos de maneira persistente e imutável;</li>
  <li><b>C5:</b> Tentativas constantes e aparentemente não coordenadas de "reiniciar" tudo (<i>re-boots</i>).</li>
</ul>
</section>

<!-- -------------------------------- -->

<section>
### DCD C1:

## Existência de muitos projetos com poucos usuários

50% é mencionado ou utilizado apenas na publicação inicial.
</section>

<!-- -------------------------------- -->

<section>
### DCD C2:

## Projetos com ciclos de vida curtos que se encerram junto ao ~~financiamento~~ inicial

78% está em estágio inicial de desenvolvimento, descontinuado ou encerrado.
</section>

<!-- -------------------------------- -->

<section>
**80 artigos** apresentam fortes indícios de serem impossíveis de reproduzir
uma vez que fazem menção (**uso ou contribuição**) a projetos em estágio
**Encerrado**.
</section>

<!-- -------------------------------- -->

<section>
---

### Better Software, Better Research

---

> "Devemos reconhecer o software como instrumento experimental de primeira-classe na Ciência."

<small class="cite">
GOBLE, C. **Better software, better research**. IEEE Internet Computing, IEEE, v.
18, n. 5, p. 4–8, 2014.
</small>
</section>

<!-- -------------------------------- -->

<section>
<img src="{{ site.baseurl }}/files/code-is-science-model-1.png" style=";background:white;margin:0" />

[CodeIsScience.com](http://www.codeisscience.com)

</section>

<!-- -------------------------------- -->

<section>
<img width="60%" src="{{ site.baseurl }}/files/software-carpentry-logo-shirt.png" style=";background:white;margin:0" />

[Software-Carpentry.org](https://software-carpentry.org)
</section>

<!-- -------------------------------- -->

<section>
### Recomendações

* Tornar o código fonte do software público o mais cedo possível
* Fazer o software fácil de ser encontrado e citado fornecendo metadados
* Adotar uma licença de software e respeitar as licenças dos outros projetos
* Definir processos claros e transparentes de contribuição, governança e comunicação

<small class="cite">
JIMéNEZ, R. C. et al. **Four simple recommendations to encourage best practices
in research software**. F1000Research, v. 6, p. 876, jun. 2017.
</small>
</section>

<!-- -------------------------------- -->

<!--
<section>
<ul style="list-style-type: none">
  <li><b>✓ C1:</b> Existência de muitos projetos com poucos usuários;</li>
  <li><b>✓ C2:</b> Projetos com ciclos de vida curtos que se encerram junto ao financiamento inicial;</li>
  <li><b>✗ C3:</b> Comunidades de usuários desconectadas e paralelas;</li>
  <li><b>✗ C4:</b> Incompatibilidades entre os projetos de maneira persistente e imutável;</li>
  <li><b>✗ C5:</b> Tentativas constantes e aparentemente não coordenadas de "reiniciar" tudo (<i>re-boots</i>).</li>
</ul>
</section>
-->

<!-- -------------------------------- -->

<section>
### Trabalhos futuros

* Incluir 2017 na revisão de literatura para seleção de projetos
* Adicionar conferências ICSE, ICSME, SANER e SBES
* Caracterizar dimensões do software na visão de engenheiros de software
* Coletar dados dos jornais JOSS, JORS e SoftwareX
</section>

<!--
<section>
### Contribuições

* Um catálogo de projetos de software acadêmico para serem utilizados em outras pesquisas
* Amadurecimento no debate sobre sustentabilidade de software
* Alerta sobre os problemas causados pela indisponibilidade dos códigos produzidos nas pesquisas
* Um framework para avaliação do fenômeno DCD em um domínio de aplicação específico
</section>
-->
