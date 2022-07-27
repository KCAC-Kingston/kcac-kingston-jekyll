---
layout: default
---
  {% for pages in site.pages %}
   {{ pages.title }}
<br>
{{ pages.url | absolute_url }}
 {% endfor %}