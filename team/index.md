---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Meet our growing team:

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/donelly_center2.jpg" dark=false %}

Please [reach out](/recruitment) if you are interested in joining! We are happy to chat about possible projects and fellowships. 

{% include section.html %}

{% capture content %}

{% endcapture %}

{% include grid.html style="square" content=content %}
