---
layout: page
title: Hello World!
tagline: Supporting tagline
---
{% include JB/setup %}

# Offsite

<img src="http://3.bp.blogspot.com/_vY8I5HvOvk8/TR7Ls1Nz-TI/AAAAAAAAOzY/vtZOVG9_APs/s400/a-hungover-owls-5.jpg" />

# Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


