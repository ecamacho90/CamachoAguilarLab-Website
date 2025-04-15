---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html dark=true %}

If you are interested in becoming involved in our research, please [reach out](/contact)!

{% include section.html %}

# Previous members

Irene Carrero Castro (MSc Student)
Grace Wang (Undergraduate Researcher)

{% capture content %}

{% endcapture %}

{% include grid.html style="square" content=content %}
