---
layout: default
title: VBlog
---
{{ page.title }}
---------------------
#####Welcome to VBlog...

###My new post

{% for post in site.posts %}

- [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) {{ post.date | date_to_string }}

{% endfor %}
