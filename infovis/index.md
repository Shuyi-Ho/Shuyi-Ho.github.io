---
layout: archive
title: "信息可视化作品集"
date: 2018-1-1T14:25:45-04:00
modified:
excerpt: "-.-"
tags: []
image: 
  feature: notes.gif
---
#### 期末作品集
- < a href="https://public.tableau.com/shared/9H623DD2T?:display_count=yes" target="_blank">![数据分析.png](https://i.loli.net/2018/01/07/5a520e66b50f0.png)</ a>



<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出来-->
