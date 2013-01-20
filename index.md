---
layout: default
---

<section class="list">
<ul>
{% for post in site.posts %}
<li>
<h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
<h3 class="article-date">{{ post.date | date: "%B %Y" }}</h3>
</li>{% endfor %} 
</ul>
</section>
