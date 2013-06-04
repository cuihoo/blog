---
layout: default
title: My Blog
---
# {{ page.title }}
## 最新文章

{% for post in site.posts %}
- {{ post.date | date_to_string }} [{{ post.title }}]({{ site.baseurl }}{{ post.url }})  
{% endfor %}

{% for post in site.cotegories.shaman %}
- {{ post.date | date_to_string }} [{{ post.title }}]({{ site.baseurl }}{{ post.url }})  
{% endfor %}
