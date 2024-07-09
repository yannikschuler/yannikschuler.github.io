---
layout: page
permalink: /publications/
title: publications
description: 
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<p>My publications and preprints. You can also find my arXiv entries <a href='https://arxiv.org/a/schuler_y_1.html'>here</a>.</p>
<div class="publications">

<h3>published:</h3>
{% bibliography -f {{ site.scholar.bibliography }}  --query @article[keywords^=published] %}

</div>

<div class="publications">
  
<h3>preprint:</h3>
{% bibliography -f {{ site.scholar.bibliography }}  --query @article[keywords^=preprint] %}

</div>


<div class="publications">
  
<h3>theses:</h3>
{% bibliography -f {{ site.scholar.bibliography }}  --query @article[keywords^=thesis] %}

</div>
