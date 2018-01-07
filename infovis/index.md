---
layout: archive
title: "信息可视化作品集"
date: 
modified:
excerpt: ""
tags: []
image: article1.jpg
---
<img src="https://luojihao.github.io/images/infovishomework.png" alt="teaser" itemprop="image">
<br/>信息可视化作品
<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出来-->

