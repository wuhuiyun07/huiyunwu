---
title: Contact
nav:
  order: 5
  tooltip: Email, phone, and where to find us
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

For prospective students: send a short note about what interests you and a
curriculum vitae. For collaboration, sampling access, or anything about the
published work, email is the fastest route.

{%
  include button.html
  type="email"
  text="huiyun.wu@wsu.edu"
  link="huiyun.wu@wsu.edu"
%}
{%
  include button.html
  type="phone"
  text="+1 509 335 8167"
  link="+1-509-335-8167"
%}
{%
  include button.html
  type="home-page"
  text="Department profile"
  link="https://ce.wsu.edu/faculty/huiyun-wu/"
%}

{% include section.html %}

{% capture col1 %}

**Huiyun Wu, Ph.D.**  
Department of Civil and Environmental Engineering  
Washington State University  
PACCAR Environmental Technology Building  
Pullman, Washington 99164

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/river-band.jpg"
  caption="The Mississippi River at New Orleans, one of our earlier sampling sites"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}
