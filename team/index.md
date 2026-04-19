---
title: Team
nav:
  order: 3
  tooltip: About our team
---

## Faculty

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role == 'faculty'" %}

{% include section.html %}

## Postdocs

{% include list.html data="members" component="portrait" filter="role == 'postdoc'" %}

{% include section.html %}

## Students

{% include list.html data="members" component="portrait" filter="role == 'master'" %}

{% include section.html %}

## Collaborators

{%
  include button.html
  link="https://illc.uva.nl/"
  text="Institute for Logic Language and Computation"
  icon="fa-solid fa-arrow-right"
%}

{%
  include button.html
  link="https://www.pmb.ox.ac.uk/"
  text="Pembroke College, University of Oxford"
  icon="fa-solid fa-arrow-right"
%}

{%
  include button.html
  link="https://pkp.sfu.ca/"
  text="Public Knowledge Project"
  icon="fa-solid fa-arrow-right"
%}

{%
  include button.html
  link="https://respondcrisistranslation.org/"
  text="Respond Crisis Translation"
  icon="fa-solid fa-arrow-right"
%}

{%
  include button.html
  link="https://meta.wikimedia.org/wiki/Research:Lost_Without_Translation:_Estimation_and_Implications_of_Invisible_Languages_on_Wikipedia"
  text="Wikimedia Foundation"
  icon="fa-solid fa-arrow-right"
%}

{%
  include button.html
  link="https://www.deusto.es/en/home"
  text="University of Deusto"
  icon="fa-solid fa-arrow-right"
%}

{%
  include button.html
  link="https://www.hf.uio.no/imk/english/"
  text="University of Oslo"
  icon="fa-solid fa-arrow-right"
%}

