---
title: JAI 3 - Princípios e Práticas para Sustentabilidade do Software de Pesquisa - Parte 1
theme: simple
---

<!-- -------------------------------- -->
<section>

## Princípios e Práticas para Sustentabilidade do Software de Pesquisa

Apresentadoras:

Christina von Flach (IC-UFBA) 

Daniela Feitosa (PGCOMP-UFBA)

</section>

<!-- -------------------------------- -->
<section>

> 92% dos pesquisadores do Reino Unido usam software em suas pesquisas e 69% declaram que a pesquisa não poderia ser realizada sem software.

> **56%** dos pesquisadores de todas as áreas do Reino Unido **desenvolvem o software usado em sua pesquisa**.

<small class="cite">
HETTRICK, S. et al. **UK Research Software Survey 2014**, 2014.
</small>
</section>

<!-- -------------------------------- -->
<section>
### Software **Acadêmico** 
### _Academic Software_

Todo software usado para coletar, processar ou analisar resultados de pesquisas
com intenção de publicação na literatura acadêmica, incluindo desde protótipos
escritos pelos próprios cientistas, a produtos completos desenvolvidos
profissionalmente.

<small class="cite">
ALLEN, A. et al. **Engineering Academic Software (Dagstuhl Perspectives Workshop
16252)**. In: Dagstuhl Manifestos. [S.l.]: Schloss Dagstuhl-Leibniz-Zentrum fuer
Informatik, 2017.
</small>
</section>

<!-- -------------------------------- -->
<section>
### Software de **Pesquisa** 
### _Research Software_

Todo software desenvolvido pelos próprios cientistas no _contexto da pesquisa_,
com recomendação para que, ao lado dos conjuntos de dados da pesquisa, 
o código-fonte ou o ambiente de execução do software também sejam disponibilizados.

<small class="cite">
Nieuwpoort, Rob van and Katz, Daniel S. **Defining the Roles of Research Software**. [DOI: 10.54900/9akm9y5-5ject5y](https://doi.org/10.54900/9akm9y5-5ject5y), 2023.
</small>
</section>

<!-- -------------------------------- -->
<section>
### Software de Pesquisa
### Analizo

<img src="{{ site.baseurl }}/files/parte1/analizo-website.png" width="500" style="box-shadow:0px 0px 2px gray;background:white" />

</section>

<!-- -------------------------------- -->
<section>
### Software de Pesquisa

+ Você desenvolve software durante a sua pesquisa?
+ Qual a principal função do seu software?
+ Você considera o seu software como um instrumento ou como um resultado de sua pesquisa?
+ O software é usado por outros membros de seu grupo de pesquisa ou outros grupos de pesquisa?
+ O software é modificado por outros membros de seu grupo de pesquisa ou outros grupos de pesquisa?
</section>

<!-- -------------------------------- -->
<section>
### Hoje

1. Princípios da Ciência Aberta
2. Software de Pesquisa Sustentável e FAIR
3. Práticas para o Desenvolvimento de Software de Pesquisa Sustentável
4. Avaliação do Software de Pesquisa
</section>

<!-- -------------------------------- 
<section>
### Software de Pesquisa e Ciência Aberta

<img src="{{ site.baseurl }}/files/parte1/unesco-OS-pilar1.png" width="450" style="box-shadow:0px 0px 2px white;background:white" />

</section>
-->

<!-- -------------------------------- -->
<section>

### O que é Ciência Aberta?

> Recomendação da UNESCO sobre Ciência Aberta.

</section>

<!-- -------------------------------- -->
<section>

<img src="{{ site.baseurl }}/files/parte1/ciencia-aberta-arquitetura.png" width="750" style="box-shadow:0px 0px 2px gray;background:white" />

</section>

<!-- -------------------------------- -->
<section>
### Pilares da Ciência Aberta

<img src="{{ site.baseurl }}/files/parte1/unesco-OS-pilares.png" width="500" style="box-shadow:0px 0px 2px white;background:white" />

</section>

<!-- -------------------------------- -->
<section>
### Conhecimento Científico Aberto

<img src="{{ site.baseurl }}/files/parte1/unesco-OS-pilar1.png" width="450" style="box-shadow:0px 0px 2px white;background:white" />

</section>

<!-- -------------------------------- -->
<section>
### Dados Abertos

> Dados digitais e analógicos, tanto brutos como processados, e os metadados que os acompanham, assim como pontuações numéricas, registros textuais, imagens e sons, protocolos, códigos de análise e fluxos de trabalho que podem ser usados, reutilizados, retidos e redistribuídos **abertamente** por qualquer pessoa, sujeitos a reconhecimento. 

</section>

<!-- -------------------------------- -->
<section>
### DOI (Digital Object Identifier)

Um identificador de objeto digital (DOI) é um identificador exclusivo atribuído a um conjunto de dados para garantir que os dados não sejam perdidos ou identificados incorretamente.
</section>

<!-- -------------------------------- -->
<section>
### DOI (Digital Object Identifier)

O DOI facilita a citação e o rastreamento do impacto dos conjuntos de dados, assim como os artigos de periódicos citados. 
</section>

<!-- -------------------------------- -->
<section>
### Citação de dados
A citação de dados deve ser considerada tão importante quanto a citação de artigos de periódicos e outros documentos científicos. 

Em geral, uma citação de dados deve incluir nome do autor/criador, data de publicação e título do conjunto de dados, editora/organizador e DOI.

</section>

<!-- -------------------------------- -->
<section>
### Dados Abertos e seus Incentivos 

A FAPESP lançou as bases para a abertura de dados com a exigência, a partir do final de 2017, de Planos de Gestão de Dados quando da submissão de projetos.
</section>

<!-- -------------------------------- -->
<section>
### Princípios FAIR para dados de pesquisa abertos

FAIR (findable, accessible, interoperable, and reusable) 
- localizável, acessível, interoperável e reutilizável
</section>

<!-- -------------------------------- -->
<section>
### Acesso Aberto

> O Movimento de Acesso Aberto surgiu com o propósito de tornar todos os resultados de pesquisa disponíveis para o público sem quaisquer restrições. 

<small class="cite">
https://en.unesco.org/open-access/open-access-movement.
</small>
</section>

<!-- -------------------------------- -->
<section>
### Acesso Aberto
<img src="{{ site.baseurl }}/files/parte1/acesso-aberto-paywall.png" width="700" style="box-shadow:0px 0px 2px white;background:white" />
</section>

<!-- -------------------------------- -->
<section>
### Acesso Aberto
<img src="{{ site.baseurl }}/files/parte1/acesso-aberto-3b.png" width="700" style="box-shadow:0px 0px 2px white;background:white" />
</section>


<!-- -------------------------------- -->
<section>
<img src="{{ site.baseurl }}/files/parte1/acesso-aberto-ri.png" width="700" style="box-shadow:0px 0px 2px white;background:white" />

- Auto-arquivamento (RI, arXiv)
- Periódicos de acesso aberto

</section>

<!-- -------------------------------- -->
<section>
### Pesquisa Reprodutível Aberta

> “O ato de praticar Ciência Aberta e oferecer aos usuários acesso sem custos a elementos experimentais para reprodução de pesquisas”

+ artigo científico
+ dados de pesquisa
+ software de pesquisa
+ fluxos de trabalho

</section>

<!-- -------------------------------- -->
<section>
### Software de Pesquisa

</section>

<!-- -------------------------------- -->
<section>
---

- software científico
- software acadêmico
- software de pesquisa

---
</section>

<!-- -------------------------------- -->
<section>
### Software na Ciência

Resultados digitais da pesquisa, como publicações científicas e conjuntos de dados abertos, não podem ser visualizados ou usados sem o software apropriado.

</section>

<!-- -------------------------------- -->
<section>
### Software na Ciência

Instituições, grupos e pesquisadores reconhecem que todo o software desenvolvido no contexto de uma pesquisa científica deve ser considerado um **resultado de pesquisa** [Jay et al. 2021]

- Software como Instrumento
- Software como Contribuição científica
- Better software, better research

</section>

<!-- -------------------------------- -->
<section>
<img src="{{ site.baseurl }}/files/parte1/scientific-reputation-diagram.png" width="500" style="box-shadow:0px 0px 2px gray;background:white" />

</section>

<section>
## Sustentabilidade

Um dos princípios norteadores da Ciência Aberta [UNESCO 2021].
 > A Ciência Aberta deve se basear em práticas, serviços, infraestruturas e modelos de financiamento **de longo prazo** que garantam a participação igualitária dos indivíduos que produzem ciência originários de instituições e países menos privilegiados.

</section>

<!-- -------------------------------- -->
<section>
## Sustentabilidade

bem-estar individual - social - econômica - ambiental - viabilidade **técnica**
de longo prazo
<small class="cite">
BECKER, C. et al. **The karlskrona manifesto for sustainability design**. CoRR,
abs/1410.6968, 2014.
</small>
</section>

<!-- -------------------------------- -->
<section>
Na Engenharia de Software, há duas linhas de pesquisa voltadas para Sustentabilidade que se destacam: 

(i) Sustentabilidade de Software
 
(ii) Engenharia de Software para Sustentabilidade (SE4S) 

</section>

<!-- -------------------------------- -->
<section>
### Sustentabilidade do Software 

"Concerned with the **long-term usage** of software and its capacity to evolve with changing conditions and requirements".

<small class="cite">
B. Penzenstadler and H. Femmer. 2013.
**A Generic Model for Sustainability with Process- and Product-specific Instances**.
</small>
</section>

<!-- -------------------------------- -->
<section>
### Sustentabilidade do Software 

A preocupação com a longevidade do software estende-se ao atributo de manutenibilidade, e ao modelo e processo de desenvolvimento de software adotados, que podem influenciar atributos relacionados à sustentabilidade.

</section>

<!-- -------------------------------- -->
<section>
### Engenharia de Software para Sustentabilidade (SE4S)

SE4S preocupa-se com sistemas intensivos em software, como integrar a sustentabilidade em seus processos de desenvolvimento de software e apoiar a sustentabilidade ambiental na ampla variedade de domínios em que o software é implantado.

</section>

<!-- -------------------------------- -->
<section>
### Sustentabilidade do Software 

> Requisito composto, não-funcional, de primeira classe, abrangendo as medidas de alguns conceitos centrais de atributos de qualidade de software, incluindo, no mínimo, manutenibilidade, extensibilidade e usabilidade.

<small class="cite">
C. Venters, et al. 2021. 
** Software Sustainability: Beyond the Tower of Babel**. 
</small>
</section>

<!-- -------------------------------- -->
<section>
### Software de Pesquisa Sustentável

O Software de Pesquisa Sustentável deve permanecer **disponível** e **funcional** para a comunidade científica durante períodos de tempo significativos. 

- Por quanto tempo? Depende da área de pesquisa, finalidade, função, frequência de uso, e da comunidade que desenvolveu o software.

</section>

<!-- -------------------------------- -->
<section>
### Software de Pesquisa Sustentável

- Mudança do software de pesquisa.

> A manutenção do software de pesquisa deve garantir a **confiabilidade nos resultados** gerados pelas **versões mais antigas do software**.

- Alinhamento entre artigos e versões do software usadas na pesquisa.

</section>

<!-- -------------------------------- -->
<section>
### FAIRness

> O **software de pesquisa deve seguir os princípios FAIR**.

- Software também é um artefato de pesquisa digital e, como tal, deve ser facilmente localizável, acessível, interoperável e reutilizável.

</section>

<!-- -------------------------------- -->
<section>

<img src="{{ site.baseurl }}/files/parte1/tabelaFAIRness.png" style="box-shadow:0px 0px 2px white;background:white" />

</section>

<!-- -------------------------------- -->
<section>
### Avaliação do Software de Pesquisa

(1) Sustentabilidade, direcionada a sua **longevidade**, e 

(2) FAIRness (aderência aos princípios FAIR), direcionada ao **grau de abertura** (openness) do software de pesquisa.

</section>

<!-- -------------------------------- -->
<section>
### Avaliação de Sustentabilidade

A avaliação da sustentabilidade do software de pesquisa busca determinar se o mesmo é sustentável com base em **critérios relevantes para o ecossistema científico**.

- Uso de atributos de qualidade ou práticas.

</section>

<!-- -------------------------------- -->
<section>
### _Nossa_ Avaliação de Sustentabilidade

- Modelo de desenvolvimento de software livre.

As práticas estão relacionadas a identidade e disponibilidade do software, adoção de licenças, controle de versão, documentação, estrutura do código-fonte, testes, política de contribuidores e suporte.

</section>

<!-- -------------------------------- -->
<section>

<img src="{{ site.baseurl }}/files/parte1/as16praticas-avaliacao.png" style="box-shadow:0px 0px 2px white;background:white" />

</section>

<!-- -------------------------------- -->
<section>
### Avaliação FAIRness

A avaliação de FAIRness do software de pesquisa pode ser definida como um processo de avaliação do seu grau de aderência aos princípios FAIR (de dados abertos de pesquisa) adaptados para software de pesquisa.

<small class="cite">
M. Barker et al. (2022). **Introducing the FAIR Principles for Research Software**. Scientific Data, 9(622). 
</small>
</section>

<!-- -------------------------------- -->
<section>
### Desenvolvimento de Software de Pesquisa

- 56% dos cientistas do Reino Unido envolvidos no desenvolvimento de software de pesquisa.

> O desenvolvimento de software de pesquisa requer conhecimento específico sobre o domínio da pesquisa.

</section>

<!-- -------------------------------- -->
<section>

> Pesquisadores que desenvolvem o seu software de pesquisa não testam ou documentam os seus projetos de software, e não seguem práticas básicas de desenvolvimento, como escrever código legível, revisar código, usar controle de versão ou testes unitários.

<small class="cite">
G. Wilson, et al. 2017. **Good enough practices in scientific computing**. 
</small>
</section>

<!-- -------------------------------- -->
<section>

</section>

<!-- -------------------------------- -->
<section>
> O desconhecimento sobre práticas de desenvolvimento colaborativo e aberto pode causar um impacto negativo na **visibilidade do software de pesquisa**, na capacidade de ser encontrado e compartilhado [Howison and Herbsleb 2013, Katz 2014] e em sua sustentabilidade.
</section>

<!-- -------------------------------- -->
<section>

A falta de conhecimento sobre a natureza do software, conceitos e práticas de desenvolvimento de software pode ocasionar sérios erros computacionais em conclusões centrais da literatura acadêmica, gerando retrabalho para retratar tais erros nas mais diversas áreas da Ciência.

</section>

<!-- -------------------------------- -->
<section>
### Ciclo de Vida do Software

<img src="{{ site.baseurl }}/files/parte1/staged-model-versions.png" style="box-shadow:0px 0px 2px white;background:white" />

</section>

<!-- -------------------------------- -->
<section>
<img src="{{ site.baseurl }}/files/parte1/staged-model-foss-cycle.png" style="box-shadow:0px 0px 2px gray;background:white" />

<small class="cite">
CAPILUPPI, A. et al. 2007.
**Adapting the staged model for software evolution to free/libre/open source software**.
</small>
</section>

<!-- -------------------------------- -->
<section>
### Evolução de um software de pesquisa 

</section>

<!-- -------------------------------- -->
<section>
---

#### Manifesto from Dagstuhl Perspectives Workshop 16252

### Engineering Academic Software

---

> "A qualidade e a **sustentabilidade** do software de pesquisa devem ser avaliadas tanto à _priori_ quanto à _posteriori_."

<small class="cite">
ALLEN, A. et al. **Engineering academic software (dagstuhl perspectives workshop
16252)**. In: Dagstuhl Manifestos. [S.l.]: Schloss Dagstuhl-Leibniz-Zentrum fuer
Informatik, 2017.
</small>
</section>



<!-- -------------------------------- -->
<section>
> Fim da Parte 1: Intervalo
</section>
