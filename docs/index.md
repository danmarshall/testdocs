---
title: home
---
# home page of docs

Page content

# Snippets

{% for snippet in site.snippets %}
Title: {{ snippet.title }}
 {{ snippet.content }}
{% endfor %}

# Layouts
{% for layout in site.layouts %}
 layout found
{% endfor %}
