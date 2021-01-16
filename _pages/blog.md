---
title: Blog
layout: post
permalink: /blog/
---

<ul class="post-list">
{%- for post in site.posts -%}
  {% include post_list_item.html %}
{%- endfor -%}
</ul>