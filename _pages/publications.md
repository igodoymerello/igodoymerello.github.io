<!-- 
title: "Publications"
layout: page
permalink: /publications/


# Publications

<input type="text" class="pub-search" id="pubSearch" placeholder="Filter by title, author, or year...">

<div class="section-card" id="pubList">
<h2>Preprints</h2>

{% bibliography --query @unpublished %}

<h2>Refereed Journal Articles</h2>

{% bibliography --query @article %}

<h2>Refereed Conference Proceedings</h2>

{% bibliography --query @inproceedings %}
</div>
-->

---
title: "Publications"
layout: page
permalink: /publications/
---

# Publications

<input type="text" class="pub-search" id="pubSearch" placeholder="Filter by title, author, or year...">

<div class="section-card" id="pubList">
<h2>Policy Papers & Reports</h2>

{% bibliography --query @techreport %}

<h2>Theses</h2>

{% bibliography --query @mastersthesis %}

<h2>Working Papers & Preprints</h2>

{% bibliography --query @unpublished %}

<h2>Journal Articles</h2>

{% bibliography --query @article %}
</div>
