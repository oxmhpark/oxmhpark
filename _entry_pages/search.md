---
title: "#찾아보기"
slug: search
meta: null
---
<script async src="https://cse.google.com/cse.js?cx=b172018a73a4b4b15"></script>
<div class="gcse-searchresults-only"></div>

<div class="archives archives-type-terms archives-type-categories">
    <h1>카테고리</h1>
    <ul class="list-terms list-categories">
        {% for post in site.archive_categories %}
        <li><a href="{{ post.url }}">#{% include parts-title.html %}</a></li>
        {% endfor %}
    </ul>
</div>

<div class="archives archives-type-terms archives-type-tags">
  <h1>태그</h1>
  <ul class="list-terms list-tags">
    {% for post in site.archive_tags %}
    <li><a href="{{ post.url }}">#{% include parts-title.html %}</a></li>
    {% endfor %}
</ul>
</div>

<div class="archives archives-type-terms archives-type-years">
    <h1>연도</h1>
    <ul class="list-terms list-years">
        {% for post in site.archive_years %}
        <li><a href="{{ post.url }}">#{% include parts-title.html %}</a></li>
        {% endfor %}
    </ul>
</div>
