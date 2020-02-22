---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
## Working Papers
<br/>
**[Gender Differences in Political Career Progression](https://jmreeves.github.io/files/CareerPathGenderGap.pdf)** with Ryan Brown, Hani Mansour, and Stephen D. O'Connell,
<br/>IZA Discussion Paper No. 12569, CESifo Working Paper No. 7821.
<br/>
<sub>We establish the existence of gender differences in career progression to leadership positions among U.S. politicians and study their underlying causes. Using a close elections strategy, we find that an additional state legislature term increases the probability of ever running for Congress by twice as much for men as it does for women and the effect on winning a Congressional race is five times larger for men than women.  These gaps emerge early in legislators' careers, widen over time, and are seen alongside a higher propensity of female politicians to continue running for the state legislature. The gap cannot be attributed to  differences in experience, career-family tradeoffs, election or constituency characteristics, nor preferences for part-time public service careers.<sub/> 
<br/>
<br/>  
  
**[Does Condominium Development Lead to Gentrification?](https://jmreeves.github.io/files/CondoGentrification.pdf)** with Leah P. Boustan, Robert A. Margo, Matthew M. Miller, and Justin P. Steil, NBER Working Paper No. 26170.
<br/>
<sub>The condominium structure, which facilitates ownership of units in multi-family buildings, was only introduced to the US in the 1960s. We ask whether the subsequent development of condominiums encouraged high-income households to move to central cities. Although we document a strong positive correlation between condominium density and resident income across locations, this association is driven by the decision of developers to build condos in areas otherwise attractive to high-income households. When we use the passage of municipal regulations limiting condo conversions as an instrument for condo density, we find little association between condo development and resident income, education or race.<sub/>


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
