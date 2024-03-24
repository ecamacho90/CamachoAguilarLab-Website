---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab is located at the [Centro Andaluz de Biologia del Desarrollo (CABD)](https://www.cabd.es/), inside the campus of the [Universidad Pablo de Olavide (UPO)](https://www.upo.es/portal/impe/web/portada/index.html). It is a mixed center funded by the [Universidad Pablo de Olavide (UPO)](https://www.upo.es/portal/impe/web/portada/index.html), the [Consejo Superior de Investigaciones Cientificas](https://www.csic.es/en) and the regional government [Junta de Andalucia](https://www.juntadeandalucia.es/).

{%
  include button.html
  type="email"
  text="ecamagu <i>at</i> upo.es"
  link="ecamagu@upo.es"
%}
{%
  include button.html
  type="phone"
  text="+34 954 977‬‬‬ 917"
  link="+34 954 977‬‬‬ 917"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/UhFQZeyyFMNAH2yPA"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/cabd1.jpeg"
  caption="CABD Building (outside)"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/CABD.jpeg"
  caption="CABD Building (inside)"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

