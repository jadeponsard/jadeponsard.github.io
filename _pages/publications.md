---
layout: page
permalink: /research/
title: Research
nav: true
nav_order: 3
---
##### **Collective action and gender roles: evidence from women suffrage demonstrations**, JMP

<button onclick="toggleAbstract('abstract1')">Abstract <span class="arrow" style="font-size: 0.8em;">▼</span></button>
<div id="abstract1" style="display: none;">
    <p><p align="justify"> Can collective action drive transformations in social roles and attitudes? I study the effect of local exposure to women’s suffrage protests in the early 20th century in the US on different indicators of gender role. Enfranchisement was anticipated to enhance women’s awareness, leading to a critical reevaluation of more traditional family structures, according to suffrage movement leaders. This study investigates whether raising awareness about one’s rights, alongside obtaining them, can foster social transformations. I study cross-county marches organized between 1912 and 1914 by some suffragettes to ask women’s right to vote. I build a novel historical database using local newspaper archives to map the itinerary of the marches. Then, using individual-level data from US censuses (1880-1930), I compare individual outcomes in localities along the suffragettes’ paths with those along other roads in the same state, both before and after the marches. Results suggest that exposure to suffragette demonstrations led to significant changes in the lives of young women, including (i) residing alone, without the presence of parents or a spouse and, (ii) having fewer children and delaying the birth of their first child. Additionally, evidence from newspaper coverage suggests that women were likely exposed to suffragette ideas beyond the marches due to the relative growing interest in the topic in the towns treated in the following years, as evidenced by newspaper mentions of suffrage-related activities.  </p></p>
</div>

##### **Roads, education and employment: evidence from the US rural highways**, with [`Clément Bosquet`](https://sites.google.com/site/clementbosquet/)

<button onclick="toggleAbstract('abstract2')">Abstract <span class="arrow" style="font-size: 0.8em;">▼</span></button>
<div id="abstract2" style="display: none;">
    <p><p align="justify"> We study education and employment responses of teenagers to changes in local economic opportunities driven by transport infrastructure improvement. We exploit the timeline of the US highways construction in the mid-20th century to measure how rural individuals aged 14 and 15—the legal working age—respond to new economic opportunities triggered by highway connectivity. We combine US Census data from 1940 to 1970 with historical records on highway locations and opening  times, and employ an established instrumental variable to account for the non-random placement of highways. Preliminary results suggest that road connectivity increases participation in the labor market. This is driven by young boys starting to work as (unpaid family) farm laborers in the agricultural sector, which has declined at a slower rate in connected counties. Further investigations indicate that, although highways do not affect school enrollment, early employment in agriculture, implying long working hours, is negatively correlated with teenagers’ education level. Looking at 24- and 25-years old men, we show that these effects of an early connection to the highway network seem to persist after 10 years.</p> </p>
</div>

##### **Forbidden love: the impact of banning interracial marriages**, with [`Björn Brey`](https://sites.google.com/view/bjoernbrey/home) and [`Roberta Ziparo`](https://sites.google.com/site/rziparo/)

<button onclick="toggleAbstract('abstract3')">Abstract <span class="arrow" style="font-size: 0.8em;">▼</span></button>
<div id="abstract3" style="display: none;">
    <p><p align="justify"> The majority of US states enacted miscegenation laws (racial mixing) at varying points during the 19th and 20th century. These laws made interracial marriages “prohibited and void”’ making them a cornerstone policy of segregation. Exploiting variations in introduction and coverage across states, we study how these laws shaped family structures and reinforced differences in economic outcomes across racial groups. To do so, we combined information on statelevel miscegenation laws with longitudinal data from the US censuses (1850- 1940). Preliminary results suggest that the implementation of miscegenation laws changed the composition of marriages and increased out-of-state migration of Black Americans. In addition, the codification of race was essential to the enforcement of interracial marriage prohibitions, which led to the introduction of blood purity rules. In line with this, we find that racial identity changes of initially Black Americans, a non-negligible phenomenon, declined when miscegenation laws were introduced. Further preliminary explorations suggest that the laws also had an impact on keeping an exploitative economic model in place.</p></p>
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
