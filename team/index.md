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
