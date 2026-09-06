---
layout: page
permalink: /publications/
title: Publications
description:
nav: true
nav_order: 3
---

<!-- _pages/publications.md -->
<h2>Journal Articles</h2>
<div class="publications">

{% bibliography -q @article %}

</div>

<h2>Articles Under Review</h2>
<div class="publications">

{% bibliography -q @unpublished %}

</div>

<h2>Proceedings/Conference Articles</h2>
<div class="publications">

{% bibliography -q @proceedings,@inproceedings,@incollection %}

</div>

<h2>Thesis</h2>
<div class="publications">

{% bibliography -q @phdthesis,@mastersthesis %}

</div>
