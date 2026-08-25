---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 2
---

<div class="publications">

<h2 class="bibliography">Journal Articles &amp; Preprints</h2>

{% bibliography --query @article %}

<h2 class="bibliography">Conference Papers</h2>

{% bibliography --query @inproceedings %}

</div>
