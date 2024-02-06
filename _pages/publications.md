---
layout: archive
title: ""
permalink: /research/
author_profile: true
---

<style type="text/css">
  ul { font-size: 16px; }
  ol { font-size: 16px; }
  details { margin-left: 10px; font-size: 14px; }
  h3 + ul { margin-top: 5px; }
  h4 + p { margin-top: -15px; }
  h4 + details { margin-top: -15px; }
  p + details { margin-top: -15px; }
  summary + p { text-align: justify; }
</style>


## Working papers
<ul>
  <li>
    Experience, Narratives and Climate Change Beliefs, with <a href="https://sites.google.com/site/milenadjourelova/home">Milena Djourelova</a>, <a href="https://www.rubendurante.net/">Ruben Durante</a> and <a href="https://www.epatacchini.com/">Eleonora Patacchini</a><br />
    <a href="https://www.dropbox.com/scl/fi/vaq27tzxu2rko56my7zes/Experience_Narratives_Climate_Change_Beliefs_20240118.pdf?rlkey=i8v3r5147p220sryiv6a2u6k2&dl=0"><b>Working Paper</b></a>
    <details> <summary> Abstract </summary>
    <p>
Linking the location and timing of FEMA-declared disasters to large-scale electoral survey data, we study how the experience of a natural disaster affects climate change beliefs, and how experience interacts with ideology. Contrary to the predictions of standard learning models, we find evidence for divergence in beliefs – exposure to the same disaster event increases stated climate change and environmental concerns among liberals, but decreases them among conservatives, widening the ideological gap by 11-17%. We further provide evidence of conflicting ideological media discourse on climate change in the aftermath of disasters by applying GPT as a novel text annotation approach. Our findings are consistent with natural disasters making the debate around climate change and partisan cleavages on this issue more salient and further polarizing initial beliefs. 
    </p>
    </details>
  </li>
</ul>


---
## Work in progress
<ul>
  <li>
    Insult Politics in the Age of Social Media
  </li>
  <li>
    Does jury gender composition affect trial outcomes? Evidence from French criminal courts, with <a href="https://mariebeigelman.github.io/">Marie Beigelman</a>
  </li>
</ul>

---
## Pre-doctoral publications

<ol>
  <li>
    The road to recovery: the role of poverty in the exposure, vulnerability and resilience to floods in Accra, with <a href="https://blogs.worldbank.org/team/alvina-erman">Alvina Erman</a>, <a href="https://sites.google.com/view/radhika-goyal/home?authuser=0">Radhika Goyal</a>, Akosua Asare, Shinya Takamatsu, Xiaomeng Chen, Silvia Malgioglio, Alexander Skinner, Nobuo Yoshida, and <a href="https://www.worldbank.org/en/about/people/s/stephane-hallegatte">Stéphane Hallegatte</a> <br />
    <a href="https://link.springer.com/article/10.1007/s41885-019-00056-w">Publication</a>
  </li>
</ol>



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
