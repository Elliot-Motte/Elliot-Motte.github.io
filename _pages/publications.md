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
    Experience, Narratives and Climate Change Beliefs, with <a href="https://sites.google.com/site/milenadjourelova/home" style="text-decoration: none;">Milena Djourelova</a>, <a href="https://www.rubendurante.net/" style="text-decoration: none;">Ruben Durante</a> and <a href="https://www.epatacchini.com/" style="text-decoration: none;">Eleonora Patacchini</a><br />
    <a href="https://raw.githubusercontent.com/Elliot-Motte/Elliot-Motte.github.io/master/files/02_Climate_Change_Narratives/Experience_Narratives_Climate_Change_Beliefs_20240529.pdf" download style="text-decoration: none; color: #494e52;"><b>Working Paper</b></a>
    <details> <summary> Abstract </summary>
    <p>
Linking the location and timing of FEMA-declared disasters to large-scale electoral survey data, we study how the experience of a natural disaster affects climate change beliefs, and how experience interacts with ideology. Contrary to the predictions of standard learning models, we find evidence for divergence in beliefs – exposure to the same disaster event increases stated climate change and environmental concerns among liberals, but decreases them among conservatives, widening the ideological gap by 11-17%. We further provide evidence of conflicting ideological media discourse on climate change in the aftermath of disasters by applying GPT as a novel text annotation approach. Our findings are consistent with natural disasters making the debate around climate change and partisan cleavages on this issue more salient and further polarizing initial beliefs. 
    </p>
    </details>
    <p><span style="text-decoration: underline;">Media Coverage:</span> <i><a href="https://www.lemonde.fr/idees/article/2024/10/30/on-pourrait-s-attendre-a-ce-que-les-citoyens-favorisent-des-partis-qui-prennent-au-serieux-la-realite-du-rechauffement-climatique-c-est-l-inverse-aux-etats-unis_6366807_3232.html" style="text-decoration: none; color: #494e52;">Le Monde</a></i>, <i><a href="https://cepr.org/voxeu/columns/experiencing-natural-disasters-increases-partisan-disagreement-climate-change" style="text-decoration: none; color: #494e52;">VoxEU</a></i></p>
  </li>
</ul>




---
## Work in progress
<ul>
  <li>
    Insult Politics in the Age of Social Media
  </li>
  <li>
    Does jury gender composition affect trial outcomes? Evidence from French criminal courts, with <a href="https://mariebeigelman.github.io/" style="text-decoration: none;">Marie Beigelman</a>
  </li>
</ul>



---
## Publications

<ul>
  <li>
    Media Slant and Public Policy Views, with <a href="https://sites.google.com/site/milenadjourelova/home" style="text-decoration: none;">Milena Djourelova</a>, <a href="https://www.rubendurante.net/" style="text-decoration: none;">Ruben Durante</a> and <a href="https://www.epatacchini.com/" style="text-decoration: none;">Eleonora Patacchini</a> <br />
    <i>American Economic Association Papers and Proceedings</i>. May 2024.<br />
    <a href="https://www.aeaweb.org/articles?id=10.1257/pandp.20241005" style="text-decoration: none; color: #494e52;"><b>Published Version</b></a> | <a href="https://raw.githubusercontent.com/Elliot-Motte/Elliot-Motte.github.io/master/files/01_AEAPP_2024_MediaSlant_PublicPolicyViews/Djourelova_Durante_Motte_Patacchini_AEAPP_2024_Media_Slant_and_Public_Policy_Views.pdf" download style="text-decoration: none; color: #494e52;"><b>Ungated Manuscript</b></a> | <a href="https://github.com/Elliot-Motte/MediaSlant_AEAPP2024" style="text-decoration: none; color: #494e52;"><b>Replication Files</b></a> 
    <details> <summary> Abstract </summary>
    <p>
We study how exposure to partisan news channels (Fox News and MSNBC) affects individual views on four policy issues: climate change, gun rights, abortion, and immigration. First, using GPT to annotate news transcripts, we document large differences in the way the two networks cover these issues. Second, exploiting exogenous variation in viewership due to channels' positions in cable lineups, we show that exposure to Fox News (MSNBC) is associated with more conservative (progressive) views, even when controlling for self-reported ideology and party affiliation. Our findings indicate that partisan media contribute to the rise of political polarization in the United States.
    </p>
    </details>
  </li>
</ul>


---
## Pre-doctoral publications

<ul>
  <li>
    The road to recovery: the role of poverty in the exposure, vulnerability and resilience to floods in Accra, with <a href="https://blogs.worldbank.org/team/alvina-erman" style="text-decoration: none;">Alvina Erman</a>, <a href="https://sites.google.com/view/radhika-goyal/home?authuser=0" style="text-decoration: none;">Radhika Goyal</a>, Akosua Asare, Shinya Takamatsu, Xiaomeng Chen, Silvia Malgioglio, Alexander Skinner, Nobuo Yoshida, and <a href="https://www.worldbank.org/en/about/people/s/stephane-hallegatte" style="text-decoration: none;">Stéphane Hallegatte</a> <br />
    <i>Economics of Disasters and Climate Change</i> (2020), 4: 171-193<br />
    <a href="https://link.springer.com/article/10.1007/s41885-019-00056-w" style="text-decoration: none; color: #494e52;"><b>Published Version</b></a>
  </li>
</ul>



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
