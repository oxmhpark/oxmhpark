---
layout: page
---
<!-- 자유형식 -->

<!-- 최근 글 -->
{% assign posts = site.entry_posts | sort_natural: "date" | limit:7 %}
{% include list-posts-recent-simple.html %}
