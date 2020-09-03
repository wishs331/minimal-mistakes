---
# 카테고리 : javascript.md 
# layout: category
title : javascript
category : javascript
permalink: '/category/javascript'
---

<ul class="posts-list">
    {% assign category = page.category | default: page.title %}
    {% for post in site.categories[categories] %}
    <li class="posts-list__item">
        <a href="{{ site.baseurl}}{{ post.url }} " class="posts-list__menu-title">
            {{ post.title }}
        </a>
        <small>{{ post.date | date_to_string }} </small>
    </li>
    {% endfor %}
</ul>