---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 2
---

<div class="publications">

<h2 style="color: var(--global-text-color);">Journal Articles &amp; Preprints</h2>

{% bibliography --query @article %}

<h2 style="color: var(--global-text-color);">Conference Papers</h2>

{% bibliography --query @inproceedings %}

</div>
