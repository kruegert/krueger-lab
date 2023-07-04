---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We are part of the School of Engineering at NYU Tandon at Brooklyn, NY 11201, USA. The lab is located on the Brooklyn campus on the 3rd floor of the  370 Jay St. Building Card access is required for entry to lab spaces.

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSd_P_k6ev8tNdR1qB6DskcWV_WfpsgOm5_YKFDHgZKAPXHAvg/viewform?embedded=true" width="900" height="800" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>

{%
  include button.html
  type="email"
  text="krueger@g.harvard.edu"
  link="krueger@g.harvard.edu"
%}
{%
  include button.html
  type="phone"
  text="(---) -------"
  link="+------------"
%}
{%
  include button.html
  type="address"
  tooltip="6 MetroTech Center, Brooklyn, NY 11201, United States"
  link="https://goo.gl/maps/4S153idC4Ubt9u8V6"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
