---
layout: archive
title: "信息可视化作品集"
date: 
modified:
excerpt: ""
tags: []
image: article1.jpg
---
[信息可视化期末专案详细版](https://luojihao.github.io/infovis/%E4%BF%A1%E6%81%AF%E5%8F%AF%E8%A7%86%E5%8C%96%E6%9C%9F%E6%9C%AB%E4%B8%93%E6%A1%88/）
<img src="https://luojihao.github.io/images/infovishomework.png" alt="teaser" itemprop="image">
<br/>信息可视化作品
<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出来-->

