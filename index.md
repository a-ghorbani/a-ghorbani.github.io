---
layout: page
title: Scientia Data!
tagline: "A new blog of a Data Scientificus"  
---
{% include JB/setup %}

<div class="note blue rounded">
This is my new blog to dump my thoughts, once in a while,
about anything goes around data science, big data, small data,
clean data, naughty data etc.
</div>

<div class="note rounded">
<h2> Previous Posts</h2>
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
</div>
