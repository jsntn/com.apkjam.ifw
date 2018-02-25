---
layout: default
---

<h1>{{ site.title }}</h1>
<ul>
{% for post in site.posts %}{% if post.layout == "post" %}<li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>{% endif %}{% endfor %}
</ul>
