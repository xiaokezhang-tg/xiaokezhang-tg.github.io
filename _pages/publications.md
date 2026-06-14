---
layout: page
permalink: /publications/
title: Research
description:
nav: true
nav_order: 1
---

<!-- _pages/publications.md -->

{% include bib_search.liquid %}

<div class="publications">

<h3 id="journal-publications"><b>Journal Publications</b></h3>

{% bibliography --query @*[category=journal]* %}

<h3 id="working-papers"><b>Working Papers</b></h3>

{% bibliography --query @*[category=working_paper]* %}

<h3 id="work-in-progress"><b>Work in Progress</b></h3>

{% bibliography --query @*[category=wip]* %}

<h3 id="other-proceedings"><b>Conference Proceedings</b></h3>

{% bibliography --query @*[category=proceedings]* %}

</div>
