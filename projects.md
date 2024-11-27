---
layout: default

---

Hi! This is where I will post about my current projects!

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}
