---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
## Highlighted Works
<ul>
    <li>Collins RS, Lee IA, <b>Habib DRS</b>, Garner DC, Johnson DB, Patel PN, Topf MC. <a href="https://danielrshabib.github.io/publications/collins2025cost">Cost evaluation in head and neck cancer clinical trials: Implications for high-value care</a>. <i>Am J Otolaryngol</i>. 2025;46(5):104655. doi:10.1016/j.amjoto.2025.104655</li>
    <li><b>Habib DRS</b>, Jamal N, Patel K, Wootten CT, Belcher RH. <a href="https://danielrshabib.github.io/publications/habib2024perioperative">Perioperative outcomes of branchial cleft sinus tract excision in pediatric patients without the use of intraoperative dye</a>. <i>Ann Otol Rhinol Laryng</i>. 2024;134(4):245-248. doi:10.1177/00034894241303021</li>
    <li><b>Habib DRS</b>*, Shou M*, Phillips RH, Pickens A, Hawkins A, Idrees K, Khan A. <a href="https://danielrshabib.github.io/publications/habib2024association">Association of neoadjuvant immunotherapy with postoperative major morbidity after oncologic surgery</a>. <i> Ann Surg Onc</i>. 2024;31(13):8508-8513. doi:10.1245/s10434-024-16284-8</li>
    <li>Stevens MN, Prasad K, Sharma RK, Gallant J-N, <b>Habib DRS</b>, Langerman A, Mannion K, Rosenthal E, Topf MC, Rohde SL. 
    <a href="https://danielrshabib.github.io/publications/stevens2024comparative">Comparative outcomes for microvascular free flap monitoring outside the intensive care unit</a>. <i>Otolaryngol Head Neck Surg</i>. 2024;171(2):381-386. doi:10.1002/ohn.780</li>
  <li>Prasad K, Sharma R, <b>Habib D</b>, Sinard R, Mannion K, Rohde S, Langerman A, Netterville J, Rosenthal E, Lewis J, Topf MC. 
    <a href="https://danielrshabib.github.io/publications/prasad2024how">How often is cancer present in oral cavity re-resections after initial positive margins?</a> <i>Laryngoscope</i>. 2024;134(2):717-724. doi:10.1002/lary.30959</li>
</ul>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
