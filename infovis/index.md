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
- 期末作品集
- [这里是tableau public链接](https://public.tableau.com/views/1_5454/1_1?:embed=y&:display_count=yes&publish=yes)![仪表板.png](https://i.loli.net/2018/01/23/5a66121720357.png)


<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出来-->
