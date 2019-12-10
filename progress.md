---
layout: default
title: bqmd.org/progress
permalink: /progress
---
<div class="container content">
<h6><a href="http://bqmd.org/">Home</a> / <a href="http://bqmd.org/projects/">Projects</a> / <a href="http://bqmd.org/projects/progress/">Progress Notes</a> / About </h6>
<br><br>

<ul class="posts">

  {% for post in site.posts %}

    <li><span>{{ post.date | date_to_string }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>

  {% endfor %}
</ul>
