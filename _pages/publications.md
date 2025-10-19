---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
years: [2016, 2017, 2018, 2019, 2020, 2021]
---

<style>
.jumbotron{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
}
</style>

<div class="jumbotron">
### Preprints
{% bibliography --query @unpublished %}
</div>

<div class="jumbotron">
### arXiv preprints
{% comment %}Articles listed on arXiv (journal field contains 'arXiv'){% endcomment %}
{% bibliography --query @article[journal *= arXiv] %}
</div>

<div class="jumbotron">
### Refereed journal articles
{# exclude article entries that are arXiv preprints (journal contains 'arXiv') #}
{% bibliography --query @article[journal !*= arXiv] %}
</div>

<div class="jumbotron">
### Refereed conference proceedings
{% bibliography --query @inproceedings %}
</div>
