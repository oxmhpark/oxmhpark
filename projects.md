---
title: "#프로젝트"
permalink: /projects
layout: page
---
<div class="archives archive-type-posts">
    {% for post in site.entry_pages %}
    {% assign content = post.content %}
    {% include post-format-list-item-without-metadata.html %}
    {% endfor %}
</div>
