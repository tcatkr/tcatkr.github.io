---
layout: page
title: Galleries
subtitle: My art and photo galleries
---

{% for gallery in site.data.galleries %}
- [{{ gallery.description }}]({{ gallery.id }})
{% endfor %}