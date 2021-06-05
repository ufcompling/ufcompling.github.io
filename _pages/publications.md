---
layout: page
permalink: /publications/
title: publications
description: Cory Shain's publications
nav: true
---


<div class="publications">

<h4>Journal articles</h4>

{% bibliography -f papers -q @*[section=articles]* %}

</div>

<div class="publications">

<h4>Conference papers</h4>

{% bibliography -f papers -q @*[section=papers]* %}

</div>

<div class="publications">

<h4>Peer reviewed conference abstracts</h4>

{% bibliography -f papers -q @*[section=abstracts]* %}

</div>
