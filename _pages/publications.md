---
layout: page
permalink: /publications/
title: publications
description: 
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<p>My publications and preprints. You can also find my arXiv entries <a href='http://arxiv.org/a/schuler_y_1'>here</a>.</p>
<div class="publications">

<h3>published:</h3>
{% bibliography -f {{ site.scholar.bibliography }}  --query @article[keywords^=published] %}

</div>

<div class="publications">
  
<h3>preprint:</h3>
{% bibliography -f {{ site.scholar.bibliography }}  --query @article[keywords^=preprint] %}

</div>
