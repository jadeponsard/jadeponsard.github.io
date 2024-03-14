---
layout: page
permalink: /research/
title: Research
nav: true
nav_order: 3
---
#### Collective action and gender roles: evidence from women suffrage demonstrations, JMP

<button onclick="toggleAbstract('abstract1')">Abstract <span class="arrow">▼</span></button>
<div id="abstract1" style="display: none;">
    <p>Abstract: Can collective action drive transformations in social roles and attitudes? ...</p>
</div>

#### Roads, education and employment: evidence from the US rural highways, with [`Clément Bosquet`](https://sites.google.com/site/clementbosquet/)

<button onclick="toggleAbstract('abstract2')">Abstract <span class="arrow">▼</span></button>
<div id="abstract2" style="display: none;">
    <p>Abstract: We study education and employment responses of teenagers to changes in local economic opportunities... </p>
</div>

#### Forbidden love: the impact of banning interracial marriages, with [`Björn Brey`](https://sites.google.com/view/bjoernbrey/home) and [`Roberta Ziparo`](https://sites.google.com/site/rziparo/)

<button onclick="toggleAbstract('abstract3')">Abstract <span class="arrow">▼</span></button>
<div id="abstract3" style="display: none;">
    <p>Abstract: The majority of US states enacted miscegenation laws (racial mixing) at varying points... </p>
</div>

<script>
function toggleAbstract(abstractId) {
    var abstract = document.getElementById(abstractId);
    var arrow = abstract.previousElementSibling.querySelector('.arrow');
    if (abstract.style.display === "none") {
        abstract.style.display = "block";
        arrow.innerHTML = "▲"; // Change to up arrow when visible
    } else {
        abstract.style.display = "none";
        arrow.innerHTML = "▼"; // Change back to down arrow when hidden
    }
}
</script>
