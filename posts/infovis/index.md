---
layout: archive
title: "信息可视化学习笔记"
date: 2018-1-1T14:25:45-04:00
modified:
excerpt: "更爱学习的证明"
tags: []
image: 
  feature: notes.gif
---


<div class="tiles">
{% for post in site.categories.post-infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 post-infovis 的列出来-->