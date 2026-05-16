---
layout: default
title: 每日三餐
---

# 每日三餐

> 菲律宾就地取材 · 兼顾大人小孩 · 一天营养均衡

## 历史菜单

{% for post in site.posts %}
- **{{ post.date | date: "%Y-%m-%d" }}** — [{{ post.title }}]({{ post.url | relative_url }})
{%- if post.summary %} — {{ post.summary }}{% endif %}
{% endfor %}

{% if site.posts.size == 0 %}
_还没有菜单。_
{% endif %}
