---
layout: research
title: Uma teoria sobre o Debian como um ecossistema sustentável de Software para Ciência
role: Doutorando
researcher: joeniocosta
advisor: chrisflach
project: ecossistema-debian
permalink: /research/ecossistema-debian-research-software
---

## Apresentação

Este documento descreve o planejamento da pesquisa de doutorado em Engenharia
de Software sobre o tema _"Uma teoria sobre o Debian como um ecossistema
sustentável de Software para Ciência"_, de [Joenio Marques da
Costa](https://seed-br.github.io/members/joeniocosta) sob a supervisão de
[Christina von Flach](https://seed-br.github.io/members/chrisflach), no
Programa de Pós-graduação em Computação ([PGCOMP-UFBA][pgcomp]) da Universidade
Federal da Bahia ([UFBA][ufba]).

## Motivação

O plano de pesquisa de doutorado apresentado aqui tem origens na minha
experiência como engenheiro de software e tem suas raízes numa época onde eu
ainda era estudante de graduação em Informática, há 18 anos atrás, na
Universidade Católica na cidade de Salvador (UCSal), período em que comecei a
me interessar por **Software para Pesquisa** (_Research Software_), **Software
Livre** (_Free Software_), e **Debian**.

Em 2006, durante uma bolsa de iniciação científica, eu tive uma primeira
experiência como desenvolvedor de software em ambiente acadêmico, colaborando
com o projeto [XMLNuke](https://github.com/byjg/xmlnuke), um framework CMS
baseado em XML, esta foi a semente do meu interesse no tema _software para
pesquisa_. Ainda na graduação, em 2009, durante o trabalho de final de curso
trabalhei num segundo projeto, o software Analizo (Terceiro et al. 2010), uma
ferramenta de análise estática e métricas de código fonte, esta experiência me
fez aprender na prática algumas questões sobre visibilidade de software na
ciência e sobre o reconhecimento dos desenvolvedores de software para pesquisa.

Alguns anos mais tarde, em 2017, durante minha pesquisa de mestrado, me
interessei ainda mais pelo assunto ao pesquisar sobre sustentabilidade de
software para pesquisa (Costa, Meirelles, e Chavez 2018), um estudo que me fez
perceber um ecossistema de software para pesquisa com pouca colaboração,
comunidades desconectadas, e poucos incentivos à carreira dos autores de
software.

Em paralelo a este período, entre 2014 e 2019, trabalhando como engenheiro de
software no [Laboratório Aplicado de Produção Pesquisa e Inovação em
Software](https://www.lappis.rocks) (LAPPIS), pude perceber também o grande
potencial do software livre na formação de alunos de graduação, através de
projetos com estreita colaboração entre professores, pesquisadores e
profissionais da indústria, na construção de soluções de engenharia de
software, no contexto acadêmico.

Importante destacar que, durante todo este período tenho sido usuário do
sistema Debian, tanto para uso pessoal, quanto em servidores, em 2009 me tornei
contribuidor do projeto, e em 2024 me tornei oficialmente um desenvolvedor
Debian (_Debian Developer_). Um dos aspectos de maior interesse no projeto
Debian são sua longevidade e resiliência em termos da capacidade de entregar
software de qualidade, num modelo transparente, colaborativo e aberto.

Por fim, não menos importante, é oportuno mencionar que atualmente trabalho no
laboratório [Laboratoire Interdisciplinaire Sciences Innovations
Sociétés](https://umr-lisis.fr) (LISIS) de estudos sobre ciência, tecnologia e
sociedade (CTS) como engenheiro de software na [plataforma
Cortext](https://www.cortext.net), tenho acompanhado com interesse o
desenvolvimento do tema em eventos e conferências internacionais sobre Software
Livre, Software para Pesquisa, e Debian.

Tais experiências, combinadas com a colaboração no grupo de pesquisa
[SEED.BR](https://seed-br.github.io) (_Software Ecosystems, Evolution and
Design_), liderado pela orientadora deste trabalho, Christina von Flach, tem me
possibilitado observar e participar ativamente do ecossistema de **Software
para Pesquisa**, do **Software Livre**, e em especial do projeto **Debian**,
despertando meu interesse na pesquisa apresentada aqui.

## Fundamentação

A ciência moderna depende de software. Cientistas não apenas utilizam software
para fazer ciência como são também os seus principais desenvolvedores. Entre os
vários domínios do conhecimento, pesquisadores desenvolvem e constroem novos
sistemas de software como parte de suas pesquisas, no entanto, muitos destes
sistemas de software se tornam indisponíveis tão logo acaba o financiamento
inicial, gerando diversos incovenientes para os cientistas, como dificuldade em
reprodução, retrabalho e até mesmo erros. A comunidade de computação científica
em 1994 já se perguntava: _"How accurate is scientific software?"_
(Hatton e Roberts 1994), se mostrando preocupados com aspectos de qualidade do
software científico, e os impactos que isto causa nos resultados das pesquisas.

Apesar de ainda ser possível notar algumas destas questões hoje, bastante
atenção foi dada nas últimas décadas em compreender e diagnosticar os aspectos
de qualidade do software para pesquisa, especialmente sobre preservação,
sustentabilidade e qualidade. Estudos como o _"Scientific Software Production:
Incentives and Collaboration"_ (Howison e Herbsleb 2011) de 2010 é um dos
exemplos que destacam o papel do software nas pesquisas científicas e como o
desenvolvimento de software para pesquisa se entrelaça com o sistema de
reputação acadêmico. O estudo aponta para incertezas em relação a visibilidade
e o reconhecimento dos autores e instituições produtoras de software para
pesquisa.

Todo este esforço em diagnosticar e compreender o papel do software na ciência,
em conjunto com alertas da comunidade científica sobre a importância de "um
software melhor, para uma pesquisa melhor" (_Better software, better research_)
(Goble 2014), tem levado a uma mudança de paradigma em relação ao
software para pesquisa. Alguns exemplos recentes são percebidos por iniciativas
como a criação da conferência [Conference of Research Software
Engineers](https://society-rse.org/events/rse17) para engajar e conectar a
comunidade global de engenheiros de software para pesquisa, o jornal para
publicação de software [The Journal of Open Source
Software](https://joss.theoj.org), a construção da plataforma [Research
Software Directory](https://research-software-directory.org) para registro de
metadados de software, o arquivo permanente de código fonte de software
[Software Heritage](https://www.softwareheritage.org), a criação de institutos
para promoção de boas práticas e reconhecimento do software na ciência como o
[Software Sustainability Institute](https://www.software.ac.uk), e o
reconhecimento do software como um [patrimônio cultural da humanidade pela
UNESCO](https://unesdoc.unesco.org/ark:/48223/pf0000366715).

Ainda assim, questões sobre como produzir, manter e distribuir software de
pesquisa continuam válidas, sabe-se que as práticas do software livre
influenciam a ciência, ao ponto de ser o _Open Source_ considerado um dos
pilares da Ciência Aberta. Não espanta portanto, tantos inúmeras pesquisas
investigando projetos como Apache, Linux, GCC ou Lua, para citar apenas alguns
exemplos, outras estudos colaboram ainda com infraestrutura para pesquisa, como
por exemplo iniciativas de ferramentas de workflow distribuídas para biologia
computacional usando Debian (Möller et al. 2010), ou projetos de
infraestrutura colaborativa para pesquisa no campo da neurociência como o Neuro
Debian (Halchenko e Hanke 2012), ou o Debian Med para distribuição de software no
campo da medicina (Tille et al. 2011), isto demonstra que o software livre e
seus modelos, em especial o Debian, continuam relevantes cientificamente e
podem contribuir positivamente para um ecossistema sustentável de software para
ciência.

O Debian é um projeto de software com características sustentáveis
(Nano 2023), este projeto desenvolve um dos sistemas operacionais
livres mais antigos e difundidos, o sistema Debian, estabelecido em 1993 e
baseado em Linux, é composto exclusivamente por software livre e é conhecido
por ser um sistema estável e confiável, servindo de base para muitos outros
projetos, notavelmente o Ubuntu, Linux Mint, Tails, Deepin, Raspberry Pi OS,
etc. Além disso o Debian foi também a origem para a definição de [Código
Aberto](https://opensource.org/osd) (_Open Source_) da _Open Source
Initiative_, que utilizou como base a definição de software livre do _Debian
Free Software Guidelines_ (DFSG). Estas características fazem crer que as
estruturas socio-técnicas do projeto e do sistema Debian possuem qualidades
interessantes para o ecossistema de software para pesquisa, em termos de um
modelo sustentável para produção, distribuição e uso de software, de forma
colaborativa, descentralizada e aberta.

## Objetivos

O objetivo geral desta pesquisa é a investigação do projeto Debian como um
ecossistema sustentável de Software para Ciência, em termos de um objeto
técnico-científico na fronteira entre o acadêmico e o não-acadêmico, entre o
industrial e o não-industrial, e com forte participação do terceiro setor na
produção de conhecimento e de soluções de engenharia.

É parte também deste objetivo a construção de uma teoria sobre o projeto Debian
como um ecossistema sustentável de Software para Ciência, seja como Software
para Pesquisa, Software Científico ou Infraestrutura de Software para Pesquisa
(Hasselbring et al. 2025), observando os conceitos, relações e
atributos de uso e qualidade do sistema Debian no contexto científico, com
especial atenção aos seus aspectos de qualidade arquitetural, como meio de
avaliar a sustentabilidade, longevidade e resilência para manutenção de longo
prazo.

## Estratégia de pesquisa

Serão realizados três estudos orientados por _Theory-Oriented Software
Engineering_ (TOSE) (Stol e Fitzgerald 2015) usando como referência o livro
_Theory building_ (Dubin 1978) para guiar o processo de teorização
sobre o tópico de interesse e os objetivos da pesquisa.

Cada estudo será um passo em direção ao objetivo geral da pesquisa, iniciando
por uma revisão de literatura para levantamento de conceitos, questões e
hipóteses, passando por um segundo estudo utilizando experimentos para
responder tais questões e testar hipóteses, um passo necessário para a
construção da teoria, chegando ao estudo final com estudos por amostragem para
testar a teoria com objetivo de ser validada.

<img src="/files/ecossistema-debian/phd-research-design-diagramme.svg" width="100%" style="border:0; box-shadow:0 0 0" />

O planejamento de cada estudo se apoia no _Research Path Schema_ (RPS), um
modelo para definir o caminho de uma pesquisa entre arquétipos arquiteturais
comuns, e no _ABC Framework_ para engenharia de software (Stol e Fitzgerald 2018), um
guia para seleção de métodos de pesquisa, definidos segundo os seguintes
elementos:

- **A** (Actors): Generalização sobre atores.
- **B** (Behaviour): Precisão de mensuração do comportamento dos atores.
- **C** (Context): Realismo sobre o contexto.

A distribuição dos elementos ABC nesta pesquisa, bem como a definição dos
caminhos segundo o RPS, podem ser visualizados no diagrama abaixo,
representando uma visão geral da pesquisa incluindo cada um dos estudos em
relação aos quadrantes do framework ABC e dos domínios de interesse do RPS.

[<img src="/files/ecossistema-debian/joenio-2025-ResearchStrategy-studies-all.png" width="100%" style="border:0; box-shadow:0 0 0" />](/files/ecossistema-debian/joenio-2025-ResearchStrategy-studies-all.png)

Cada um dos estudos serão detalhados nas seções seguintes, em termos de
objetivos, resultados esperados, e estragégia de pesquisa.

### Estudo 1: Estudo de campo guiado por sistema com caminho observacional

O objetivo principal deste estudo é realizar um estudo de campo (_field study_)
através de revisão de literatura multivocal (Garousi, Felderer, e Mäntylä 2019) sobre o
Debian para caracterizar o seu papel nas pesquisas científicas, seja como
Software para Pesquisa, Software Científico, ou Infraestrutura de Software para
Pesquisa. Este estudo visa também compreender os limites entre os conceitos de
Operating System, Software Bundle, Software Collection, FLOSS Distribution,
Global Computing Infrastructure e Collaborative Research Infrastructure, bem
como de posicionar o Debian entre tais idéias.

O estudo 1 é classificado segundo o RPS como uma pesquisa com interesse
particular primário no domínio substantivo (_substantive domain_), com
interesse inicial de observar o sistema e o projeto Debian, tem como interesse
secundário o domínio metodológico (_methodological domain_), e é guidado por
sistema (_system-driven research_), seguindo o caminho observacional
(_observational path, or empirical_). O interesse terciário deste estudo é o
domínio conceitual (_conceptual domain_) para classificação e caracterização do
Debian segundo os conceitos de software para pesquisa.

| Interesse | Domínio               | Definição do domínio    |
| --------- | --------------------- | ----------------------- |
| 1°        | Substantivo           | Debian                  |
| 2°        | Metodológico          | Estudo de Campo         |
| 3°        | Conceptual            | Classificação sobre software para pesquisa |

De acordo com o framework ABC, o estudo 1 tem um alto potencial de realismo no
contexto estudado, se posiciona no Quadrante I em ambiente natural, baixa
manipulação de variáveis e pouca interferência do pesquisador no ambiente
estudado, possuindo um baixo potencial de generalização dos resultados.

Os resultados esperados deste estudo é a caracterização do Debian sob o ponto
de vista científico, segundo os conceitos e definições do software para
pesquisa, software científico e infraestrutura de software para pesquisa.
Espera-se também levantar hipóteses e questões de pesquisa durante este estudo,
incluindo questões sobre o nível de sustentabilidade do projeto Debian em
termos de manutenção, longevidade e qualidade. Serão utilizados aspectos de
qualidade arquitetural do sistema como um intermediário para avaliar a
sustentabilidade e resiliência para manutenção de longo prazo.

### Estudo 2: Experimento de laboratório guiado por conceito com caminho de projeto de estudo

O principal objetivo do segundo estudo é a execução de experimentos
(_experiment study_) sobre a sustentabilidade do sistema Debian segundo
aspectos sócio-técnicos de qualidade de sua arquitetura, do ponto de vista
científico, cruzando dados dos pacotes do sistema, com mineração de código
fonte, e dados bibliométricos de publicações acadêmicas. Estes experimentos
serão realizados com o objetivo de construir uma teoria sobre o Debian como um
ecossistema sustentável de Software na Ciência, sendo tal teoria o objetivo central desta
pesquisa de doutorado.

Segundo o modelo RPS, este estudo tem como interesse particular primário o
domínio conceitual (_conceptual domain_), possui como interesse inicial
realizar experimentos utilizando teorias, hipóteses e conceitos sobre o Debian.
O interesse secundário é o domínio metodológico (_methodological domain_),
guidado por conceito (_concept-driven research_), segue o caminho projeto de
estudo (_study design path, or experimental_), e tem como interesse particular
primário os conceitos de Research Software sobre o Debian. E como domínio
substantivo (_susbstantive domain_) definido em torno dos times do Debian e
subconjuntos de pacotes.

| Interesse | Domínio               | Definição do domínio        |
| --------- | --------------------- | --------------------------- |
| 1°        | Conceitual            | Teoria sobre software para pesquisa |
| 2°        | Metodológico          | Experimento de Laboratório  |
| 3°        | Substantivo           | Times e pacotes do Debian   |

Segundo o framework ABC, o estudo 2 terá um alto potencial de precisão nas
medições do comportamento dos atores estudados, alto potencial para
generalização dos resultados encontrados. Posicionado no Quadrante II em
ambiente artificial, com alta manipulação de variáveis, e com alto grau de
interferência do pesquisador no ambiente estudado.

Os resultados esperados deste estudo incluem uma teoria, ou fragmentos de
teoria, sobre a sustentabilidade do Debian em termos de um ecossistema de
software para ciência, a partir de aspectos de qualidade arquitetural, aspectos
utilizados como intermediário para avaliar a sustentabilidade, custo de
manutenção, longevidade e resiliência. O estudo visa também testar as
hipóteses, e responder às questões elaboradas no estudo anterior.

### Estudo 3: Estudo por amostragem guiado por conceito com caminho hipotético

A terceira e último etapa desta pesquisa tem como objetivo realizar um estudo
por amonstragem (_sample study_) para testar a teoria sobre o Debian como
ecossistema sustentável, segundo os seus aspectos de qualidade arquitetural, em
um contexto de um ecossistema sócio-técnico sustentável e longevo para
pesquisas acadêmicas. A teoria testada neste estudo vem do estudo anterior, que
tem como resultado principal a construção de tal teoria.

Neste estudo o interesse particular primário é o domínio conceitual
(_conceptual domain_), com interesse inicial em realizar estudo por amostragem
(_sample study_) para testar a teoria ou fragmentos de teoria sobre o sistema e
o projeto Debian, o estudo será guidado por conceito (_concept-driven
research_), seguirá o caminho hipotético (_hypothetical path, or theoretical_),
e tem como interesse particular primário a teoria ou fragmentos de teoria. O
domínio substantivo (_substantive domain_) é definido segundo os times ou
subconjuntos de pacotes do Debian.

| Interesse | Domínio               | Definição do domínio     |
| --------- | --------------------- | ------------------------ |
| 1°        | Conceitual            | Teoria sobre software para pesquisa |
| 2°        | Substantivo           | Times e pacotes Debian   |
| 3°        | Metodológico          | Estudo por amonstragem   |

Segundo o framework ABC, o estudo 3 tem um alto potencial de generalização
sobre os atores estudados, podendo ter seus resultados expandidos e aplicados
em outros atores. Se posiciona no Quadrante II em ambiente neutro, pouca
manipulação de variáveis e pouca interferência do pesquisador no ambiente
estudado.

Os resultados esperados incluem a validação da teoria e a avaliação dos
aspectos de qualidade arquitetural do sistema Debian sob o ponto de vista de um
ecossistema sustentável de software para pesquisa.

## Resultados

Os três estudos desta pesquisa completam um processo de triangulação entre
diferentes caminhos de pesquisa (Research Path Schema), utilizando estratégias
de pesquisa que se complementam em termos do grau de generalização dos
resultados e do nível de manipulação do ambiente pesquisado. Segundo os
princípios do TOSE esta triangulação é uma estratégia importante para
estabelecer uma compreensão profunda sobre um tópico particular. Entre os
resultados esperados desta pesquisa encontra-se uma teoria, ou fragmentos de
teoria, sobre o Debian como um ecossistema de software sustentável para uso e
distribuição de software na ciência, seja como Software para Pesquisa, Software
Científico, ou Infraestrutura de Software para Pesquisa.

## Referências

[pgcomp]: https://pgcomp.ufba.br
[ufba]: https://portal.ufba.br

<!--
## Visão Geral

Este estudo investiga o projeto e o sistema Debian como um ecossistema sustentável de software para pesquisa.

O projeto Debian é uma associação de pessoas que têm como causa comum criar o
sistema Debian, um sistema operacional livre.

Sustentabilidade de software é um requisito não-funcional, composto de
atributos centrais de qualidade, o que inclui no mínimo: manutenibilidade,
extensibilidade, usabilidade, longevidade e preservação.

## Questões

- É possível propor uma teoria sobre o papel do sistema e do projeto _Debian_
  no ecossistema de _Research Software_?
- Qual é o papel do sistema e do projeto _Debian_ no ecossistema de _Research
  Software_?

## Hipóteses

- O projeto e o sistema _Debian_ oferecem uma infraestrutura sustentável para distribuição e uso de _Research Software_.
- O sistema _Debian_ é a base fundamental da infraestrutura computacional da comunidade de _Research Software_.

## Planejamento

- Estudo 1: O Debian como um ecossistema sustentável para distribuição e uso de Research Software
- Estudo 2: Análise e caracterização do projeto e do sistema Debian na comunidade científica
- Estudo 3: Evolução e qualidade da arquitetura do sistema Debian e dos pacotes de Research Software
-->

<ul>
<li>
Costa, Joenio, Paulo Meirelles, e Christina Chavez. 2018. <span>“On the
sustainability of academic software: the case of static analysis
tools”</span>. In <em>Proceedings of the <span>XXXII</span>
<span>Brazilian</span> <span>Symposium</span> on <span>Software</span>
<span>Engineering</span></em>, 202–7. <span>SBES</span> ’18. New York,
NY, USA: Association for Computing Machinery. <a
href="https://doi.org/10.1145/3266237.3266243">https://doi.org/10.1145/3266237.3266243</a>.
</li>
<li>
Dubin, Robert. 1978. <em>Theory building</em>. Rev. ed. New York: Free
Press.
</li>
<li>
Garousi, Vahid, Michael Felderer, e Mika V. Mäntylä. 2019.
<span>“Guidelines for including grey literature and conducting
multivocal literature reviews in software engineering”</span>.
<em>Information and Software Technology</em> 106 (fevereiro): 101–21. <a
href="https://doi.org/10.1016/j.infsof.2018.09.006">https://doi.org/10.1016/j.infsof.2018.09.006</a>.
</li>
<li>
Goble, Carole. 2014. <span>“Better software, better research”</span>.
<em>IEEE Internet Computing</em> 18 (5): 4–8. https://doi.org/<a
href="https://doi.org/10.1109/MIC.2014.88">https://doi.org/10.1109/MIC.2014.88</a>.
</li>
<li>
Halchenko, Yaroslav O., e Michael Hanke. 2012. <span>“Open is
<span>Not</span> <span>Enough</span>. <span>Let</span>’s
<span>Take</span> the <span>Next</span> <span>Step</span>:
<span>An</span> <span>Integrated</span>,
<span>Community</span>-<span>Driven</span> <span>Computing</span>
<span>Platform</span> for <span>Neuroscience</span>”</span>.
<em>Frontiers in Neuroinformatics</em> 6 (junho). <a
href="https://doi.org/10.3389/fninf.2012.00022">https://doi.org/10.3389/fninf.2012.00022</a>.
</li>
<li>
Hasselbring, Wilhelm, Stephan Druskat, Jan Bernoth, Philine Betker,
Michael Felderer, Stephan Ferenz, Ben Hermann, et al. 2025.
<span>“Multi-<span>Dimensional</span> <span>Research</span>
<span>Software</span> <span>Categorization</span>”</span>. <em>Computing
in Science &amp; Engineering</em>, 1–10. <a
href="https://doi.org/10.1109/MCSE.2025.3555023">https://doi.org/10.1109/MCSE.2025.3555023</a>.
</li>
<li>
Hatton, L., e A. Roberts. 1994. <span>“How accurate is scientific
software?”</span> <em>IEEE Transactions on Software Engineering</em> 20
(10): 785–97. <a
href="https://doi.org/10.1109/32.328993">https://doi.org/10.1109/32.328993</a>.
</li>
<li>
Howison, James, e James D. Herbsleb. 2011. <span>“Scientific
<span>Software</span> <span>Production</span>: <span>Incentives</span>
and <span>Collaboration</span>”</span>. In <em>Proceedings of the
<span>ACM</span> 2011 <span>Conference</span> on <span>Computer</span>
<span>Supported</span> <span>Cooperative</span> <span>Work</span></em>,
513–22. <span>CSCW</span> ’11. New York, NY, USA: ACM. <a
href="https://doi.org/10.1145/1958824.1958904">https://doi.org/10.1145/1958824.1958904</a>.
</li>
<li>
Möller, Steffen, Hajo Nils Krabbenhöft, Andreas Tille, David Paleino,
Alan Williams, Katy Wolstencroft, Carole Goble, Richard Holland,
Dominique Belhachemi, e Charles Plessy. 2010. <span>“Community-driven
computational biology with <span>Debian</span>
<span>Linux</span>”</span>. <em>BMC Bioinformatics</em> 11 (Suppl 12):
S5. <a
href="https://doi.org/10.1186/1471-2105-11-S12-S5">https://doi.org/10.1186/1471-2105-11-S12-S5</a>.
</li>
<li>
Nano, Edlira. 2023. <span>“Digital obsolescence”</span>. <a
href="https://eda.mutu.net/travaux.html.en">https://eda.mutu.net/travaux.html.en</a>.
</li>
<li>
Stol, Klaas-Jan, e Brian Fitzgerald. 2015. <span>“Theory-oriented
software engineering”</span>. <em>Science of Computer Programming</em>,
Towards general theories of software engineering, 101 (abril): 79–98. <a
href="https://doi.org/10.1016/j.scico.2014.11.010">https://doi.org/10.1016/j.scico.2014.11.010</a>.
</li>
<li>
Stol, Klaas-Jan, e Brian Fitzgerald. 2018. <span>“The <span>ABC</span> of <span>Software</span>
<span>Engineering</span> <span>Research</span>”</span>. <em>ACM
Transactions on Software Engineering and Methodology</em> 27 (3):
11:1–51. <a
href="https://doi.org/10.1145/3241743">https://doi.org/10.1145/3241743</a>.
</li>
<li>
Terceiro, Antonio, Joenio Costa, Joao Miranda, Paulo Meirelles, Luiz
Romario Rios, Lucianna Almeida, Christina Chavez, e Fabio Kon. 2010.
<span>“Analizo: an <span>Extensible</span>
<span>Multi</span>-<span>Language</span> <span>Source</span>
<span>Code</span> <span>Analysis</span> and <span>Visualization</span>
<span>Toolkit</span>”</span>, 6.
</li>
<li>
Tille, Andreas, Steffen Möller, Michael Hanke, e Yaroslav Halchenko.
2011. <span>“Debian <span>Med</span> <span>Integrated</span> software
environment for all medical purposes based on <span>Debian</span>
<span>GNU</span>/<span>Linux</span>”</span>. <em>Med@Tel 2011</em>. <a
href="https://wiki.debian.org/DebianMed">https://wiki.debian.org/DebianMed</a>.
</li>
</ul>
