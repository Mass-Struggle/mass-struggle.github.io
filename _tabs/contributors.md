---
icon: fas fa-users
order: 1
---

{% for author in site.authors %}
  <h3><a href="{{ author.url }}">{{ author.title }}</a></h3>
  <p>{{ author.content | markdownify }}</p>
{% endfor %}
