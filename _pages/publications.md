---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

### Work in progress

"Experience, narratives, and climate change beliefs: evidence from extreme weather events", with
[Milena Djourelova](https://sites.google.com/site/milenadjourelova/home), [Ruben Durante](https://www.rubendurante.net/) and [Eleonora Patacchini](https://www.epatacchini.com/).

“Does jury gender composition affect trial outcomes? Evidence from French criminal courts”, with
[Marie Beigelman](https://mariebeigelman.github.io/).


### Publications

1. "The road to recovery: the role of poverty in the exposure, vulnerability and resilience to floods in Accra.", with Alvina Erman, Radhika Goyal, Akosua Asare, Shinya Takamatsu, Xiaomeng Chen, Silvia Malgioglio, Alexander Skinner, Nobuo Yoshida, and Stephane Hallegatte. *Economics of Disasters and Climate Change* (2020).
Paper available [here](https://link.springer.com/article/10.1007/s41885-019-00056-w).


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
