---
layout: page
permalink: /publications/
title: publications
description:
nav: true
---

<div class="publications">

<h4>Preprints</h4>

{% bibliography -f bibliography -q @*[section=preprints]* %}

</div>

<div class="publications">

<h4>Journal articles</h4>

{% bibliography -f bibliography -q @*[section=articles]* %}

</div>

<div class="publications">

<h4>Conference papers</h4>

{% bibliography -f bibliography -q @*[section=papers]* %}

</div>

<div class="publications">

<h4>Peer reviewed conference abstracts</h4>

{% bibliography -f bibliography -q @*[section=abstracts]* %}

</div>

<div class="publications">

<h4>Theses</h4>

{% bibliography -f bibliography -q @*[section=theses]* %}

</div>

<div class="publications">

<h4>Unpublished materials</h4>

{% bibliography -f bibliography -q @*[section=unpublished]* %}

</div>
