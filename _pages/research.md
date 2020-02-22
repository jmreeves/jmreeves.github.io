---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
## Working Papers

**Gender Differences in Political Career Progression** with Ryan Brown, Hani Mansour, and Stephen D. O'Connell.<br/>
[IZA Discussion Paper No. 12569](https://www.iza.org/publications/dp/12569/gender-differences-in-political-career-progression-evidence-from-us-elections), [CESifo Working Paper No. 7821](https://www.ifo.de/DocDL/cesifo1_wp7821.pdf).
<br/>
<sub>We establish the existence of gender differences in career progression to leadership positions among U.S. politicians and study their underlying causes. Using a close elections strategy, we find that an additional state legislature term increases the probability of ever running for Congress by twice as much for men as it does for women and the effect on winning a Congressional race is five times larger for men than women.  These gaps emerge early in legislators' careers, widen over time, and are seen alongside a higher propensity of female politicians to continue running for the state legislature. The gap cannot be attributed to  differences in experience, career-family tradeoffs, election or constituency characteristics, nor preferences for part-time public service careers.<sub/> 

**Does Condominium Development Lead to Gentrification?** with Leah P. Boustan, Robert A. Margo, Matthew M. Miller, and Justin P. Steil.<br/>
[NBER Working Paper No. 26170](https://www.nber.org/papers/w26170).



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
