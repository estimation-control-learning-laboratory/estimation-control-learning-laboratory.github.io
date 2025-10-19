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
Preprints count: {% bibliography_count --query @unpublished %}
{% bibliography --query @unpublished %}
</div>

<div class="jumbotron">
### arXiv preprints
<!-- We'll render all articles hidden and split them client-side based on the "Preprint (arXiv)" badge
         This avoids jekyll-scholar query parsing that can return nil for complex regex queries. -->
<div id="all-articles" style="display:none;">
{% bibliography --query @article %}
</div>

<ol id="arxiv-articles" reversed></ol>
</div>

<div class="jumbotron">
### Refereed journal articles
<ol id="refereed-articles" reversed></ol>

<script>
// Move rendered article list items from the hidden container into arXiv or refereed lists.
document.addEventListener('DOMContentLoaded', function () {
    try {
        var container = document.getElementById('all-articles');
        if (!container) return;
        // The bibliography tag usually renders an <ol> with <li> children. Find all list items.
        var items = container.querySelectorAll('li');
        var arxivList = document.getElementById('arxiv-articles');
        var refList = document.getElementById('refereed-articles');
        items.forEach(function (li) {
            var text = li.innerText || li.textContent || '';
            // Look for our badge text (rendered by the bibtemplate) or the substring 'arxiv' in the entry.
            var isArxiv = /preprint \(arxiv\)/i.test(text) || /arxiv/i.test(text);
            if (isArxiv) {
                arxivList.appendChild(li.cloneNode(true));
            } else {
                refList.appendChild(li.cloneNode(true));
            }
        });
    } catch (e) {
        console.error('Error splitting articles by arXiv status:', e);
    }
});
</script>
</div>


<div class="jumbotron">
### Refereed conference proceedings
{% bibliography --query @inproceedings %}
</div>
