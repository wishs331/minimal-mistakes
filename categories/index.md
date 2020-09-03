---
# layout: default
permalink: /categories/
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

<h3>Javascript</h3>
<ul class="posts-list">
    {% for post in site.categories["javascript"] %}
    <li class="posts-list__item">
        <a href="{{ site.baseurl}}{{ post.url }} " class="posts-list__menu-title">
            {{ post.title }}
        </a>
    </li>
    {% endfor %}
</ul> 