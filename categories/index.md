---
# layout: default
permalink: /category/
---
<h3>HTML</h3>
<ul class="posts-list">
    {% for post in site.categories["html"] %}
    <li class="posts-list__item">
        <a href="{{ site.baseurl}}{{ post.url }} " class="posts-list__menu-title">
            {{ post.title }}
        </a>
    </li>
    {% endfor %}
</ul>