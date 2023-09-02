---
title: On the Sustainability of Academic Software (Research Software)
theme: simple
---

<!-- -------------------------------- -->

<section>
### On the Sustainability of Academic Software: The Case of Static Analysis Tools

<table style="font-size:0.8em"><tr>
<td style="text-align: center">
Joenio Costa<br/>
Federal University of Bahia
</td>
<td style="text-align:center">
Christina Chavez<br/>
Federal University of Bahia
</td>
<td style="text-align:center">
Paulo Meirelles<br/>
Federal University of São Paulo
</td>
</tr></table>

<small style="font-size: 0.5em">
[https://doi.org/10.1145/3266237.3266243](https://doi.org/10.1145/3266237.3266243)
</small>
</section>

<!-- -------------------------------- -->

<section>
## Software Sustainability

<img src="{{ site.baseurl }}/files/2023-07-12-paper2002.png" style="background: white" style="width:100px"/>

human, social, economic, environmental, **technical**

<small class="cite">
Robert Goodland. 2002. **Sustainability: Human, Social, Economic and Environmental**.
</small>
</section>

<!-- -------------------------------- -->

<section>
### Software Technical Sustainability

Concerned with the long-term usage of software and its capacity to evolve with
changing conditions and requirements.

<small class="cite">
B. Penzenstadler and H. Femmer. 2013.
**A Generic Model for Sustainability with Process- and Product-specific Instances**.
</small>
</section>

<!-- -------------------------------- -->

<section>
### Academic Software

Software developed to collect, process, or analyze research results published
in the academic literature.

<small class="cite">
ALLEN, A. et al. 2017.
**Engineering academic software (dagstuhl perspectives workshop 16252)**.
</small>
</section>

<!-- -------------------------------- -->

<section>
### Research Software

Software developed to collect, process, or analyze research results published
in the academic literature.

<small class="cite">
ALLEN, A. et al. 2017.
**Engineering academic software (dagstuhl perspectives workshop 16252)**.
</small>
</section>

<!-- -------------------------------- -->

<section>
<img src="{{ site.baseurl }}/files/scientific-reputation-diagram-en.png" style="background: white" />

<small class="cite">
James Howison and James D. Herbsleb. 2011.
**Scientific software production: incentives and collaboration**.
</small>
</section>

<!-- -------------------------------- -->

<section data-background="orange" data-background-transition="slide">
## How measure Academic Software Sustainability?
</section>

<!-- -------------------------------- -->

<section>
Three exploratory studies:

1. Publicization
1. Life cycle
1. Recognition
</section>

<!-- -------------------------------- -->

<!-- image source: http://vidracariashowglass.com.br/wp-content/gallery/vitrine-para-loja/vitrine_1.jpg -->
<section data-background="{{ site.baseurl }}/files/vitrine_1.jpg">
#### Study 1

### Publicization of Academic Software

_url, license, source code, and download availability_
</section>

<!-- -------------------------------- -->

<section data-transition="zoom">
<section>
<img src="{{ site.baseurl }}/files/revisao-literatura-big.png" />

found 60 academic software projects of static analysis
</section>

<!-- -------------------------------- -->

<section>
Inclusion criterion and keywords

| Criteria                               | Keywords                      |
| -------------------------------------- | ----------------------------- |
| Mentions the project, software or tool | _tool_ or _framework_         |
| Makes software available for download  | _download_ or _available_     |
| Identifies project URL                 | _http_, _https_ or _ftp_      |
| Static analysis domain                 | _static analysis_ or _parser_ |

</section>

<!-- -------------------------------- -->

<section>
Inclusion criterion for extraction

| Criteria      | Explanation                                                       |
| ------------- | ----------------------------------------------------------------- |
| Identifiable  | Is it possible to identify a software project among the outputs of the article? |
| Available     | Can we find mention to the URL for download the software project? |

</section>
</section>

<!-- -------------------------------- -->

<section>
**Official online presence (RQ1.1)**

from 60 academic software, 15 projects (25%) do not have an official online presence

**Sofware available for download (RQ1.2)**

from 60  academic software, 24 projects (40%) are not available for download
</section>

<!-- -------------------------------- -->

<section>
**Source code available (RQ1.3)**

from 36 academic software available for download, 34 projects has their source code available
</section>

<!-- -------------------------------- -->

<section>
**Software license available (RQ1.4)**

from 34 projects with the source code available, 13 did not provide any
software license, and 21 used free software license

</section>

<!-- -------------------------------- -->

<!-- image source: https://upliftconnect.com/wp-content/uploads/2016/05/Gowing-.jpg -->
<section data-background="{{ site.baseurl }}/files/Gowing-.jpg" data-background-color="black">
<div class="box-green">
#### Study 2

### Life cycle of Academic Software

_evolution stage_
</div>
</section>

<!-- -------------------------------- -->

<section data-transition="zoom">
<img src="{{ site.baseurl }}/files/staged-model-foss-cycle-en.png" style="box-shadow:0px 0px 2px gray;background:white" />

<small class="cite">
CAPILUPPI, A. et al. 2007.
**Adapting the staged model for software evolution to free/libre/open source software**.
</small>
</section>

<!-- -------------------------------- -->

<section>
**Evolution stage of academic software (RQ2.1)**

| Evolution stage      | Academic Software | %     |
| -------------------- | ----------------- | ----- |
| Initial development  | 20                | 33%   |
| Evolution            | 2                 | 3%    |
| Servicing            | 6                 | 10%   |
| Phaseout             | 3                 | 5%    |
| Closedown            | 24                | 40%   |
| Unknown              | 5                 | 8%    |

</section>

<!-- -------------------------------- -->

<!-- image source: https://cdn-images-1.medium.com/max/2000/1*4d4rFBB97fgjZLetKypzxA.jpeg -->
<section data-background="{{ site.baseurl }}/files/1_4d4rFBB97fgjZLetKypzxA.jpeg">
#### Study 3

### Recognition of Academic Software

_number and types of mentions_
</section>

<!-- -------------------------------- -->

<section>
A **mention** means any occurrence of the name of the academic software in a
scientific publication
</section>

<!-- -------------------------------- -->

<section>
<img width="100%" src="{{ site.baseurl }}/files/study2-literature-review-big.png" style="background:white" />
</section>

<!-- -------------------------------- -->

<section>
**Mentions to academic software (RQ3.1)**

only 2 projects -- GUIZMO and protopurity -- were not found in searches carried
out in ACM and IEEE
</section>

<!-- -------------------------------- -->

<section>
**Uses of academic software (RQ3.1)**

there are 124 "usage" mentions to a set of 26 projects
</section>

<!-- -------------------------------- -->

<section>
**Contributions to academic software (RQ3.1)**

there are 43 "contribute" mentions to a set of 17 projects, that is, only 28%
of projects received source code contributions from studies after its initial
publication
</section>

<!-- -------------------------------- -->

<section data-background="#00bfff" data-background-transition="slide">
## Discussion and Conclusions
</section>

<!-- -------------------------------- -->

<section>
Evolution of the recognition of academic software for static analysis published in ASE and SCAM

<img src="{{ site.baseurl }}/files/mentions-type-by-year.png" style="box-shadow: 0px 0px 5px gray; border-radius: 5px; padding: 10px" />
</section>

<!-- -------------------------------- -->

<section>
Growth of 38% per year in the number of mentions

<img src="{{ site.baseurl }}/files/mentions-trend-en.png" style="box-shadow: 0px 0px 5px gray; border-radius: 5px; padding: 10px; display: inline" />
</section>

<!-- -------------------------------- -->

<section>
from 60 academic software projects of static analysis studied, 13 projects
(22%) did not have academic recognition
</section>

<!-- -------------------------------- -->

<section>
Influence of the life cycle stage on the recognition of academic software

large number of mentions for close-down projects -- ESBMC, PARSEWeb, and
TestEra -- including recent publications between 2016 and 2017
</section>

<!-- -------------------------------- -->

<section>
Academic software projects are not yet recognized by Science
as first-class citizens

<small class="cite">
Carole Goble. 2014. **Better software, better research**.
</small>
</section>

<!-- -------------------------------- -->

<section>
<img src="{{ site.baseurl }}/files/code-is-science-model-1.png" style="width: 40%;background:white;margin:0" />

[codeisscience.com](http://www.codeisscience.com)

<img width="60%" src="{{ site.baseurl }}/files/software-carpentry-logo-shirt.png" style="width:40%;background:white;margin:0" />

[software-carpentry.org](https://software-carpentry.org)
</section>

<!-- -------------------------------- -->

<section>
### Future Work

* Why some tools in closedown stage continue to be cited?
* The results found regarding academic software recognition are similar to general software engineering publications?
</section>
