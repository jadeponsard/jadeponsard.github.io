---
layout: page
permalink: /research/
subtitle: Work in progress
title: Research
nav: true
nav_order: 3
---
<meta name="viewport" content="width=device-width, initial-scale=1">
layout: page
permalink: /research/
subtitle: Work in progress
title: Research
nav: true
nav_order: 3
---

###### **• Collective action and gender roles: evidence from women suffrage demonstrations**, JMP.
<button onclick="toggleAbstract('abstract1')" style="padding: 2px 5px; font-size: 0.7em; border: none !important; outline: none !important;">Abstract <span class="arrow" style="font-size: inherit;">▼</span></button>
<button onclick="togglePresentation('presentation1')" style="padding: 2px 5px; font-size: 0.7em; margin-left: 5px; border: none; outline: none;">Presentation <span class="arrow">▼</span></button>
<div id="abstract1" style="display: none;">
    <p style="font-size: 0.85em; text-align: justify;"> Can collective action drive transformations in social roles and attitudes? ... </p>
</div>
<div id="presentation1" style="display: none;">
    <p style="font-size: 0.85em; text-align: justify;"> IMERA-AMSE Workshop in Gender inequalities (Marseille, France), ... </p>
</div>

###### **• Roads, education and employment: evidence from the US rural highways**, with [`Clément Bosquet`](https://sites.google.com/site/clementbosquet/)

<button onclick="toggleAbstract('abstract2')" style="padding: 2px 5px; font-size: 0.7em; border: none; outline: none;">Abstract <span class="arrow" style="font-size: inherit;">▼</span></button>
<button onclick="togglePresentation('presentation2')" style="padding: 2px 5px; font-size: 0.7em; margin-left: 5px; border: none; outline: none;">Presentation <span class="arrow">▼</span></button>
<div id="abstract2" style="display: none;">
    <p style="font-size: 0.85em; text-align: justify;"> We study education and employment responses of teenagers to changes in local economic opportunities ... </p>
</div>
<div id="presentation2" style="display: none;">
    <p style="font-size: 0.85em; text-align: justify;"> RES & SES Annual Conference (Glasgow, Scottland), ... </p>
</div>

###### **• Forbidden love: the impact of banning interracial marriages**, with [`Björn Brey`](https://sites.google.com/view/bjoernbrey/home) and [`Roberta Ziparo`](https://sites.google.com/site/rziparo/)

<button onclick="toggleAbstract('abstract3')" style="padding: 2px 5px; font-size: 0.7em; border: none; outline: none;">Abstract <span class="arrow" style="font-size: inherit;">▼</span></button>
<button onclick="togglePresentation('presentation3')" style="padding: 2px 5px; font-size: 0.7em; margin-left: 5px; border: none; outline: none;">Presentation <span class="arrow">▼</span></button>
<div id="abstract3" style="display: none;">
    <p style="font-size: 0.85em; text-align: justify;"> The majority of US states enacted miscegenation laws (racial mixing) at varying points ... </p>
</div>
<div id="presentation3" style="display: none;">
    <p style="font-size: 0.85em; text-align: justify;"> EHA 2022 (La Crosse WI, USA), AMSE PhD Seminar 2022 (Marseille, France) ... </p>
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

function togglePresentation(presentationId) {
    var presentation = document.getElementById(presentationId);
    var arrow = presentation.previousElementSibling.querySelector('.arrow');
    if (presentation.style.display === "none") {
        presentation.style.display = "block";
        arrow.innerHTML = "▲"; // Change to up arrow when visible
    } else {
        presentation.style.display = "none";
        arrow.innerHTML = "▼"; // Change back to down arrow when hidden
    }
}
</script>

