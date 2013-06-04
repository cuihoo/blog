---
layout: default
title: ==============  Blog of cuihoo  ===============
---
# {{ page.title }}
## 萨満旅程

{% for post in site.cotegories.shaman %}
- {{ post.date | date_to_string }} [{{ post.title }}]({{ site.baseurl }}{{ post.url }})  
{% endfor %}

## 恶魔学识

{% for post in site.cotegories.Demonic_knowledge %}
- {{ post.date | date_to_string }} [{{ post.title }}]({{ site.baseurl }}{{ post.url }})  
{% endfor %}

## 假如没有诗

{% for post in site.cotegories.without_poem %}
- {{ post.date | date_to_string }} [{{ post.title }}]({{ site.baseurl }}{{ post.url }})  
{% endfor %}
