---
title: Team
nav:
  order: 3
  tooltip: About our team
---

## Faculty

{% include portrait.html lookup="saurabh-khanna" %}
{% include portrait.html lookup="olga-eisele" %}
{% include portrait.html lookup="chei-billedo" %}
{% include portrait.html lookup="irene-van-driel" %}
{% include portrait.html lookup="sindy-sumter" %}
{% include portrait.html lookup="lauren-taylor" %}
{% include portrait.html lookup="marina-tulin" %}
{% include portrait.html lookup="sandra-jacobs" %}
{% include portrait.html lookup="britta-brugman" %}
{% include portrait.html lookup="corine-meppelink" %}

{% include section.html %}

## Postdocs

{% include list.html data="members" component="portrait" filter="role == 'postdoc'" %}

{% include section.html %}

## Students

{% include list.html data="members" component="portrait" filter="role == 'master'" %}

{% include section.html %}

## Collaborators

{% capture collab_logos %}
{%
  include figure.html
  image="images/collab-illc.png"
  link="https://illc.uva.nl/"
  caption="Institute for Logic, Language and Computation"
  height="80px"
%}
{%
  include figure.html
  image="images/collab-pembroke.png"
  link="https://www.pmb.ox.ac.uk/"
  caption="Pembroke College, University of Oxford"
  height="80px"
%}
{%
  include figure.html
  image="images/collab-pkp.png"
  link="https://pkp.sfu.ca/"
  caption="Public Knowledge Project"
  height="80px"
%}
{%
  include figure.html
  image="images/collab-respond.png"
  link="https://respondcrisistranslation.org/"
  caption="Respond Crisis Translation"
  height="80px"
%}
{%
  include figure.html
  image="images/collab-wikimedia.png"
  link="https://meta.wikimedia.org/wiki/Research:Lost_Without_Translation:_Estimation_and_Implications_of_Invisible_Languages_on_Wikipedia"
  caption="Wikimedia Foundation"
  height="80px"
%}
{%
  include figure.html
  image="images/collab-deusto.png"
  link="https://www.deusto.es/en/home"
  caption="University of Deusto"
  height="80px"
%}
{%
  include figure.html
  image="images/collab-oslo.png"
  link="https://www.hf.uio.no/imk/english/"
  caption="University of Oslo"
  height="80px"
%}
{% endcapture %}

{% include grid.html content=collab_logos %}

{%
  include button.html
  link="https://www.hf.uio.no/imk/english/"
  text="University of Oslo"
  icon="fa-solid fa-arrow-right"
%}

