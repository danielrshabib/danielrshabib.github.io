---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Highlighted Works
<ul>
  <li>Prasad K, Sharma R, <b>Habib D</b>, Sinard R, Mannion K, Rohde S, Langerman A, Netterville J, Rosenthal E, Lewis J, Topf MC. [How often is cancer present in oral cavity re-resections after initial positive margins?](https://danielrshabib.github.io/publications/prasad2024how) <I>Laryngoscope</i>. 2024;134(2)717-724. doi:10.1002/lary.30959</li>
  <li>Stevens MN, Prasad K, Sharma RK, Gallant J-N, <b>Habib DRS</b>, Langerman A, Mannion K, Rosenthal E, Topf MC, Rohde SL. [Comparative outcomes for microvascular free flap monitoring outside the intensive care unit](https://danielrshabib.github.io/publications/stevens2024comparative). <i>Otolaryngol Head Neck Surg</i>. doi:10.1002/ohn.780</li>
</ul>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
