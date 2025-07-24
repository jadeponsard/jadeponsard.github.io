---
layout: page
title: CV
permalink: /cv/
description: Mon curriculum vitae
nav: true
nav_order: 7
---

<div class="cv-container" style="width: 100%; height: 800px; margin: 20px 0;">
    <iframe 
        src="https://drive.google.com/file/d/1vJHmK3pp34EM_TPcJ_FNU2bA-oa1M2v_/preview" 
        width="100%" 
        height="100%" 
        frameborder="0"
        style="border: 1px solid var(--global-divider-color); border-radius: 8px;">
    </iframe>
</div>

<div class="cv-download" style="text-align: center; margin-top: 20px;">
    <a href="https://drive.google.com/file/d/1vJHmK3pp34EM_TPcJ_FNU2bA-oa1M2v_/view?usp=sharing" 
       target="_blank" 
       class="btn btn-primary"
       style="background-color: var(--global-theme-color); border-color: var(--global-theme-color); color: white; padding: 10px 20px; text-decoration: none; border-radius: 5px; display: inline-block;">
        📄 Télécharger le CV (PDF)
    </a>
</div>

<!-- Section optionnelle avec informations complémentaires -->
<div class="cv-info" style="margin-top: 40px; padding: 20px; background-color: var(--global-card-bg-color); border-radius: 8px; border: 1px solid var(--global-divider-color);">
    <h3>À propos de mon CV</h3>
    <p>
        Vous pouvez consulter mon curriculum vitae ci-dessus ou le télécharger directement. 
        Pour toute question ou opportunité professionnelle, n'hésitez pas à me contacter.
    </p>
    
    <h4>Dernière mise à jour</h4>
    <p><em>{{ "now" | date: "%B %Y" }}</em></p>
</div>
