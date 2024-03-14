---
layout: page
permalink: /research/
title: Research
nav: true
nav_order: 3
---
<button onclick="toggleAbstracts()">Show Abstracts</button>

<div id="abstract1" style="display: none;">
    <h5>**Collective action and gender roles: evidence from women suffrage demonstrations**, JMP</h5>
    <p>Abstract: Can collective action drive transformations in social roles and attitudes? ...</p>
</div>

<div id="abstract2" style="display: none;">
    <h5>**Roads, education and employment: evidence from the US rural highways**, with [Clément Bosquet](https://sites.google.com/site/clementbosquet/)</h5>
    <p>Abstract: We study education and employment responses of teenagers to changes in local economic opportunities... </p>
</div>

<div id="abstract3" style="display: none;">
    <h5>**Forbidden love: the impact of banning interracial marriages**, with [Björn Brey](https://sites.google.com/view/bjoernbrey/home) and [Roberta Ziparo](https://sites.google.com/site/rziparo/)</h5>
    <p>Abstract: The majority of US states enacted miscegenation laws (racial mixing) at varying points... </p>
</div>

<script>
function toggleAbstracts() {
    var abstracts = document.querySelectorAll('#abstract1, #abstract2, #abstract3');
    abstracts.forEach(function(abstract) {
        if (abstract.style.display === "none") {
            abstract.style.display = "block";
            document.querySelector('button').textContent = "Hide Abstracts";
        } else {
            abstract.style.display = "none";
            document.querySelector('button').textContent = "Show Abstracts";
        }
    });
}
</script>
