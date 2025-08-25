---
title: "DebConf25 Academic Track - Debian in the Research Software Ecosystem"
lead: >
  Talk presenting the paper "Debian in the Research Software ecosystem: A
  Bibliometric Analysis" at Debian Conference 2025 in the Academic Track.
theme: simple
version: 2025.07.04
---

<!-- --------------------  slide  -------------------- -->

<section>
<small style="color: #666">_Debian Conference 2025, Brest, Jul 14th - 19th_</small>

#### Debian in the Research Software Ecosystem: 

#### An Exploratory Bibliometric Analysis

<small style="color: #666">
&nbsp;<br/>
_Joenio M. Costa and Christina von Flach_
<br/>
_Institute of Computing, Federal University of Bahia_
</small>
</section>

<!-- --------------------  slide  -------------------- -->

<section data-background-image="/files/debconf2025-academictrack-talk/goodbye-baloon-inverse.jpg">
<h4 style="color:white">Joenio Marques da Costa</h4>
<a href="http://joenio.me" style="color:burlywood; text-shadow: 0 0 2px blue">http://joenio.me</a>

<small style="color:white">_Institute of Computing, Federal University of Bahia (UFBA)_</small>

<img style="position:relative; float:right; width: 27%" src="/files/debconf2025-academictrack-talk/joenio-2020-800x800.jpg" />
<div style="float: left; max-width: 500px; font-size: 0.95em; color: white">
 - PhD candidate in Software Engineering
 - Work at Cortext Platform (www.cortext.net)
 - Debian Developer
 - Member of the SEED.br research group
</div>
</section>

<!-- --------------------  slide  -------------------- -->

<section data-background-image="/files/debconf2025-academictrack-talk/goodbye-baloon-inverse.jpg">
<h4 style="color:white">Christina von Flach</h4>
<a href="https://christinaflach.github.io" style="color:burlywood; text-shadow: 0 0 2px blue">https://christinaflach.github.io</a>

<small style="color:white">_Institute of Computing, Federal University of Bahia (UFBA)_</small>

<img style="position:relative; float:right; width: 27%" src="/files/debconf2025-academictrack-talk/christina-flach-800x900.jpg" />
<div style="float: left; max-width: 500px; font-size: 0.95em; color: white">
 - Ph.D. in Computer Science (2004)
 - Professor at the UFBA Institute of Computing (1990-today)
 - Head of the SEED.br research group
</div>
</section>

<!-- --------------------  slide  -------------------- -->

<section>
### **Research Software** is software that is designed and developed to support research activities.

<small class="cite" style="font-size:0.7em">
Source: Morane Gruenpeter et al. 2021.<br/>
**Defining Research Software: A controversial discussion**.
</small>
</section>

<!-- --------------------  slide  -------------------- -->

<section>
#### Research Software **Ecosystem**

![](/files/debconf2025-academictrack-talk/scientific-reputation-diagram-en.png)

<small class="cite" style="font-size:0.7em">
Source: James Howison and James D. Herbsleb. 2011.<br/>
**Scientific software production: incentives and collaboration**.
</small>

</section>

<!-- --------------------  slide  -------------------- -->


<section>
### **Bibliometric Analysis** is a method for exploring and analyzing large volumes of scientific data.

<small class="cite" style="font-size:0.7em">
Source: Naveen Donthu et al. 2021.<br/>
**How to conduct a bibliometric analysis: An overview and guidelines**.
</small>

</section>

<!-- --------------------  slide  -------------------- -->

<section>
#### Bibliometric Analysis data

![](/files/debconf2025-academictrack-talk/bibliometric-analysis-paper-metadata-a.png)
</section>

<!-- --------------------  slide  -------------------- -->

<section>
### Research Strategy

- Search and collect data from Scopus
- Filter data by inclusion and exclusion criterias
- Explore the data with a bibliometric analysis

</section>

<!-- --------------------  slide  -------------------- -->

<section style="font-size:0.8em">
### Data search and collection

![](/files/debconf2025-academictrack-talk/debconf25-academictrack-table1-elegibility-criteria.png)

Due to the exploratory nature of our
work, we only collected data from one bibliographic research
database, Scopus.
- Results: 473 documents

</section>

<!-- --------------------  slide  -------------------- -->

<section style="font-size:0.8em">
### Data filter and screening

| Name     | Inclusion criteria  | Exclusion criteria       |
| -------- | ------------------- | ------------------------ |
| Language | Is English          | Isn't English            |
| Year     | Beetween 1993-2024  | Isn't beetween 1993-2024 |
| Author   | Isn't empty         | Is empty                 |
| Title    | Match "debian"      | Doesn't match "debian"   |
| Abstract | Match "debian"      | Doesn't match "debian"   |

In this step 53 documents were removed in a semi-automated procedure.

- Results: 420 documents
</section>

<!-- --------------------  slide  -------------------- -->

<section>
#### Paper excluded from our dataset:

<small class="cite" style="font-size:0.7em">
Rodríguez R. et al. 1995.<br/>
**La perspectiva profesional en la reforma de la atención primaria de salud: una aproximación cualitativa**.
</small>

<small>
Abstract:
_"La mayor parte de los profesionales opinaban que los programas de
enfermedades prevalentes **debían** venir elaborados de forma vertical..."_
</small>

<small>Paper metadata:<br/>
`Type = Article, Language = English`<br/>
`Source = Gaceta Sanitaria`
</small>

</section>

<!-- --------------------  slide  -------------------- -->

<section>
#### Paper included in our dataset:
<small class="cite" style="font-size:0.7em">
Ahsan Ullah et al. 2024.<br/>
**A Comparative Study on Vulnerabilities, Challenges, and Security Measures in
Wireless Network Security**.
</small>

<small>
Abstract:
_"Dataset, generated using Tpot within **Debian** operating system, serves as
the cornerstone of this research, with..."_
</small>

<small>Paper metadata:<br/>
`Type = Article, Language = English,`<br/>
`Source = Lecture Notes in Networks and Systems`
</small>

</section>

<!-- --------------------  slide  -------------------- -->

<section>


#### Publication count per year
#### What is the annual number of publications?

![](/files/debconf2025-academictrack-talk/debconf25-academictrack-annual-scientific-production_2025-07-03_14-37-09.png)

</section>

<!-- --------------------  slide  -------------------- -->

<section>
#### What is oldest publication found?

<small class="cite" style="font-size:0.7em">
Tommi Syrjänen. 2000.<br/>
**Including Diagnostic Information in Configuration Models**.
</small>

<small>
Abstract:
_"As an example, a subset of the configuration problem for the **Debian**
GNU/Linux system is formalized using the new rule-based language."_
</small>

<small>
The first paper indexed by Scopus mentioning Debian was published only 7 years
after the Debian release in 1993.
</small>

<small>Paper metadata:<br/>
`Type = Conference paper, Language = English,`<br/>
`Source = Lecture Notes in Artificial Intelligence`
</small>
</section>

<!-- --------------------  slide  -------------------- -->

<section>
#### Which papers have been cited the most by other papers?
#### The top-cited papers are **Research Software**

<small class="cite" style="font-size:0.7em">
Ardavan F. Oskooi. 2010.<br/>
**Meep: A flexible free-software package for electromagnetic simulations by the FDTD method**.<br/>
(cited 2,437 times)
</small>

<small>
Abstract:
_"Operating system: Any Unix-like system; developed under **Debian** GNU/Linux 5.0.2."_
</small>

<small>Scopus metadata:<br/>
`Type = Article, Language = English,`<br/>
`Source = Computer Physics Communications`
</small>
</section>

<!-- --------------------  slide  -------------------- -->

<section>
#### The 1st top-cited paper is a **Research Software**
#### Role-based category: **Modeling, Simulation, and Data Analytics**

<small class="cite" style="font-size:0.7em">
Ardavan F. Oskooi. 2010.<br/>
**Meep: A flexible free-software package for electromagnetic simulations by the FDTD method**.<br/>
</small>

<small>
Abstract:
_"This paper describes Meep, a popular free implementation of the
finite-difference time-domain (FDTD) method for simulating electromagnetism. In
particular, we focus on aspects of implementing a full-featured FDTD package
that go beyond standard textbook descriptions of the algorithm, or ways in
which Meep differs from typical FDTD implementations...<br/>
Operating system: Any Unix-like system; developed under **Debian** GNU/Linux
5.0.2..."_
</small>
</section>

<!-- --------------------  slide  -------------------- -->

<section style="font-size:0.45em">

The top 10 most cited papers are about algorithm implementation
and research software (tools).

| #  | Title                                                                                                       | Year | Cited by | Type |
| -- | --------------------------------------------------------------------------------------------------------------- | ---- | ---- | ---------------- |
| 01 | Meep: A flexible free-software package for electromagnetic simulations by the FDTD method                       | 2010 | 2437 | Article          |
| 02 | SNP-sites: rapid efficient extraction of SNPs from multi-FASTA alignments                                       | 2016 | 893  | Article          |
| 03 | Seamless R and C++ integration with Rcpp                                                                        | 2013 | 281  | Book             |
| 04 | Herding cats: Modelling, simulation, testing, and data mining for weak memory                                   | 2014 | 227  | Article          |
| 05 | Toward Large-Scale Vulnerability Discovery using Machine Learning                                               | 2016 | 216  | Conference paper |
| 06 | ReDeBug: Finding unpatched code clones in entire OS distributions                                               | 2012 | 208  | Conference paper |
| 07 | THERMINATOR: THERMal heavy-IoN generATOR                                                                        | 2006 | 190  | Article          |
| 08 | Flip feng Shui: Hammering a needle in the software stack                                                        | 2016 | 189  | Conference paper |
| 09 | A new monotonic, clone-independent, reversal symmetric, and condorcet-consistent single-winner election method  | 2011 | 174  | Article          |
| 10 | FreeContact: Fast and free software for protein contact prediction from residue co-evolution                    | 2014 | 134  | Article          |

`Role-based Category = Modeling, Simulation, and Data Analytics`

</section>

<!-- --------------------  slide  -------------------- -->

<section style="font-size:0.5em">
There are Research Software among the 10 oldest publications?

| #  | Title | Research software? |
| -- | ---------------------------------------- | ------------------------------- |
| 01 | Including diagnostic information in configuration models (2000) | Yes: Smodels lang |
| 02 | Demudi: The Debian Multimedia Distribution (2001) | Yes: Debian-derivative |
| 03 | Statistically based postprocessing of phylogenetic analysis by clustering (2002) | Yes: Matlab lang |
| 04 | Towards intelligent support for managing evolution of configurable software product families (2003) | Yes: Product-line prototype |
| 05 | A Framework for Blood Flow Analysis and Research (2003) | Yes: Ultrasound Doppler |
| 06 | Open source software development should strive for even greater code maintainability (2004) | No |
| 07 | Managing volunteer activity in free software projects (2004) | No |
| 08 | Can we trust cryptographic software? Cryptographic flaws in GNU privacy guard v1.2.3 (2004) | No |
| 09 | Demonstration abstract: BNF converter (2004) | Yes: BNF converter |
| 10 | Configurable coprocessing with an ARC-PCI board (2004) | Yes: Hardware + Linux driver |

(Yes = 7, No = 3)
</section>

<!-- --------------------  slide  -------------------- -->

<section style="font-size:0.6em">
### Most active researchers
#### Who are the most active researchers, measured by number of published papers?

| # | Author        | N. of papers | The oldest paper |
| - | ------------- | ------------ | ---------------- |
| 1 | Zacchiroli S. | 13 papers    | **The Ultimate Debian Database: Consolidating bazaar metadata for Quality Assurance and data mining** (2010) |
| 2 | German D.M.   | 10 papers    | **A Model to Understand the Building and Running Inter-Dependencies of Software** (2007) |
| 3 | Di Cosmo R.   | 9 papers     | **Predicting upgrade failures using dependency analysis** (2011) |
| 4 | Robles G.     | 9 papers     | **Evolution of volunteer participation in libre software projects: Evidence from debian** (2005) |

_"Among the most active researchers, there are publications with studies about Debian or for Debian."_
</section>

<!-- --------------------  slide  -------------------- -->

<section>
#### Active countries
#### Which countries are contributing the most, based on the affiliations of the researchers?

![](/files/debconf2025-academictrack-talk/debconf25-academictrack-top10-corresponding-author-countries_2025-06-18_19-47-20.png)

<small>
(MCP: Multiple Country Publications,
SCP: Single Country Publications)
</small>

</section>

<!-- --------------------  slide  -------------------- -->

<section>
#### Top-relevant terms and frequent words
#### What are the most relevant terms and concepts in the field?

![](/files/debconf2025-academictrack-talk/debconf25-academictrack-WordCloud_2025-07-03_14-28-40.png)

</section>

<!-- --------------------  slide  -------------------- -->

<section>
### Future work and next steps:

1. Current study:
  - Add more databases besides Scopus: WOS, Pubmed, etc.
  - Finish the bibliometric analysis.
1. New study:
  - Cross bibliometric data with upstream source code metrics.
  - Cross bibliometric data with Debian source package metadata.

</section>

<!-- --------------------  slide  -------------------- -->

<section data-background="#c4a000">
<section>

### Thanks!

<span class="url">joenio@joenio.me</span>

<br/>
_This presentation is available at:_

<span class="url">{{ page.url | prepend: site.url | remove: '/index.html' }}</span>

<small>
  <a style="color:blue" href="{{ page.url | prepend: site.url | remove: '/index.html' | append: '?print-pdf' }}">
    Export this presentation as PDF
  </a>
  (require chromium browser)
</small>

</section>
<section>
### Presentation history

<small>Where and when this presentation was done</small>

<ul style="font-size: 24px">
  <li>15 July 2025, Brest, <a href="https://debconf25.debconf.org">DebConf25</a></li>
</ul>
</section>
</section>
