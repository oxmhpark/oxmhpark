---
title: "아카이브"
permalink: /archives
layout: page
---
<script async src="https://cse.google.com/cse.js?cx=b172018a73a4b4b15"></script>
<div class="gcse-search"></div>

<div class="archives archives-type-terms archives-type-categories">
    <h2>카테고리</h2>
    <ul class="list-terms list-categories">
        {% for post in site.archives_categories %}
        <li><a href="{{ post.url }}">#{{ post.title }}</a></li>
        {% endfor %}
    </ul>
</div>

<div class="archives archives-type-terms archives-type-tags">
  <h2>태그</h2>
  <ul class="list-terms list-tags">
    {% for post in site.archives_tags %}
    <li><a href="{{ post.url }}">#{{ post.title }}</a></li>
    {% endfor %}
</ul>
</div>

<div class="archives archives-type-terms archives-type-years">
    <h2>연도</h2>
    <ul class="list-terms list-years">
        {% for post in site.archives_years %}
        <li><a href="{{ post.url }}">#{{ post.title }}</a></li>
        {% endfor %}
    </ul>
</div>
