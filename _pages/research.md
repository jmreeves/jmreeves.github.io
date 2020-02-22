---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
## Working Papers

**Gender Differences in Political Career Progression** with Ryan Brown, Hani Mansour, and Stephen D. O'Connell.<br/>
[IZA Discussion Paper No. 12569](https://www.iza.org/publications/dp/12569/gender-differences-in-political-career-progression-evidence-from-us-elections), [CESifo Working Paper No. 7821](https://www.ifo.de/DocDL/cesifo1_wp7821.pdf).

**Does Condominium Development Lead to Gentrification?** with Leah P. Boustan, Robert A. Margo, Matthew M. Miller, and Justin P. Steil.<br/>
[NBER Working Paper No. 26170](https://www.nber.org/papers/w26170).



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
