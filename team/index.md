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

{% include section.html %}

## Previous members

Andrea Theodorou (Research Assistant, now PhD candidate at European University Cyprus)

Gabriel Gonzalez Parrado (Undergraduate Student)

Pablo Martín Berna (Undergraduate Student, now MSc student in Computer Science and Technologies at UCIII Madrid)

Irene Carrero Castro (MSc Student, University of Seville)

Grace Wang (Undergraduate Researcher, Rice University)

{% include section.html dark=true %}

If you are interested in becoming involved in our research, please [reach out](/contact)!

{% capture content %}

{% endcapture %}

{% include grid.html style="square" content=content %}
