# home page of docs

Page content

# Snippets (default)

{% for snippet in site.snippets %}
 {{ snippet.content }}
{% endfor %}

# Snippets (sorted by title)

{% assign snippets = site.snippets | sort: 'title' %}
{% for snippet in snippets %}
 {{ snippet.content }}
{% endfor %}
