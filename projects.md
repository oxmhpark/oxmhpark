---
title: "#프로젝트"
permalink: /projects
layout: page
---
<div class="archives archive-type-posts">
    {% for post in site.pages %}
    {% assign content = post.content %}
    {% include post-format-excerpt.html %}
    {% endfor %}
</div>
