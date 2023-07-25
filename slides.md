---
theme: seriph
background: false  # Need false to avoid default gradient
layout: cover
aspectRatio: '16/9'
class: text-center
highlighter: shiki
lineNumbers: false
info: |
 Introductory talk at PyHEP.dev 2023
drawings:
  persist: false
favicon: 'https://github.com/favicon.ico?format=100w'
transition: fade-out
selectable: true
download: true
title: feickert_pyhep-dev-2023_2023-07-25
---

# **Working Towards Fully<br>Differentiable Analysis**
<br>
Matthew Feickert

matthew.feickert@cern.ch

[PyHEP.dev Workshop 2023](https://indico.cern.ch/event/1234156/contributions/5510688/)

July 25th, 2023

<!-- UW-Madison logo -->
<div class="abs-bl m-5 flex gap-2">
  <img src=/figures/logos/logo_institution.png style="width: 30%">
</div>

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/matthewfeickert-talks/talk-pyhep-dev-2023" target="_blank" alt="GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!-- IRIS-HEP logo -->
<img src=/figures/logos/logo_IRIS-HEP.png style="position: fixed; bottom: 15px; right: 60px; width: 15%">

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)

TODO: How to add logos?
-->

---

# Introduction

<div class="grid grid-cols-[60%_1fr] gap-4">
<div style="font-size: 30px">

* Postdoc  on ATLAS at the University of Wisconsin-Madison Data Science Institute
* IRIS-HEP Analysis Systems focus area lead
* pyhf core developer and maintainer

</div>
<div>

<div style="display: flex; justify-content:center;">
<img border="rounded" src="/figures/logos/logo_ATLAS.png" style="width: 80%">
</div>

<div style="display: flex; justify-content:center;">
<img border="rounded" src="/figures/logos/logo_IRIS-HEP.png" style="width: 60%">
</div>

<div style="display: flex; justify-content:center;">
<img border="rounded" src="https://raw.githubusercontent.com/scikit-hep/pyhf/main/docs/_static/img/pyhf-logo.svg?raw=true" style="width: 60%">
</div>

</div>
</div>

---

# IRIS-HEP Analysis Systems Pipeline

<div style="display: flex; justify-content:center;">
<a href="https://iris-hep.org/as.html" style="border-style: none;">
<img src="https://iris-hep.org/assets/images/cabinetry-vertical-slice.png" style="width: 100%; margin: 0 auto;">
</a>
</div>

---

# Looking towards differentiability of tools

<div style="display: flex; justify-content:center;">
<a href="https://www.munich-iapbp.de/probabilistic-programming/schedule" style="border-style: none;">
<img src="/figures/MIAPbP-poster.png" style="width: 50%; margin: 0 auto;">
</a>
</div>

<div style="text-align:center;">

[MIAPbP Differentiable and Probabilistic Programming for Fundamental Physics program](https://www.munich-iapbp.de/probabilistic-programming/schedule)

</div>

---

# Prior art on this topic: [neos](https://github.com/gradhep/neos)

<div style="display: flex; justify-content:center;">
<a href="https://github.com/gradhep/neos" style="border-style: none;">
<img src="https://raw.githubusercontent.com/gradhep/neos/fd52e3fc91a24805880cdc0a8d0669a06235955e/animation.gif" style="width: 65%; margin: 0 auto;">
</a>
</div>

<div style="text-align:center;">

Nathan Simpson, Lukas Heinrich

</div>

<div style="font-size:24px;">

"Leverages the shoulders of giants (jax and pyhf) to differentiate through a high-energy physics analysis workflow, including the construction of the frequentist profile likelihood." --- neos docs

</div>

---

# Would love to engage with you on this

<div style="display: flex; justify-content:center;">
<a href="https://github.com/HSF/PyHEP.dev-workshops/issues/27" style="border-style: none;">
<img src="/figures/auto-diff-github-issue.png" style="width: 70%; margin: 0 auto;">
</a>
</div>

<div style="text-align:center;">

[PyHEP.dev 2023 Issue #27](https://github.com/HSF/PyHEP.dev-workshops/issues/27)

</div>

---

# Goals for PyHEP 2023
<br>

<div style="font-size: 22px">

* Working towards tool differentiability (personal focus on pyhf)
   - [HSF/PyHEP.dev-workshops/ Issue #27](https://github.com/HSF/PyHEP.dev-workshops/issues/27)
* Discussion and move towards tool adoption of HEP Statistics Serialization Standard  (HS3)
   - [HSF/PyHEP.dev-workshops/ Issue #5](https://github.com/HSF/PyHEP.dev-workshops/issues/5)
   - [HS3 GitHub](https://github.com/hep-statistics-serialization-standard/hep-statistics-serialization-standard)
* Improve the onboarding experience for new contributors to Scikit-HEP/PyHEP ecosystem (personal focus on pyhf)
   - [HSF/PyHEP.dev-workshops/ Issue #6](https://github.com/HSF/PyHEP.dev-workshops/issues/6)
   - [HSF/PyHEP.dev-workshops/ Issue #9](https://github.com/HSF/PyHEP.dev-workshops/issues/9)
</div>

---
layout: center
---

# Let's talk!
<br>

<div style="font-size: 30px">

Looking forward to a good week
</div>
