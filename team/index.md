---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our team is a diverse and talented group of researchers, including PhD candidates, MPhil students, Research Associates (RAs), and visiting students from around the world. Each member brings unique expertise and perspectives from varied academic and professional backgrounds, creating a dynamic collaborative environment. Together, we are committed to advancing cutting-edge research in AI-driven urban modeling and making meaningful contributions to sustainable city development.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

<!-- {% include section.html background="images/background.jpg" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %} -->

<!-- {% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %} -->

<!-- {% include grid.html style="square" content=content %} -->
