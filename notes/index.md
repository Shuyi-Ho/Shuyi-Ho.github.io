---
layout: archive
title: "学习笔记"
date: 2018-1-1T14:25:45-04:00
modified:
excerpt: "分为web学习笔记和信息可视化学习笔记"
tags: []
image: 
  feature: notes.gif
  teaser:
---


<div class="tiles">
{% for post in site.categories.notes %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 notes 的列出来-->