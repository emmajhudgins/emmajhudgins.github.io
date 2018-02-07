---

layout: page
title: "Blog"
permalink: /blog
nav: true
order: 1

---

Welcome to my blog, where I hopefully intend to post about statistical tools, as well as current issues in invasion biogeography, species distribution modelling, and the state of equity in ecology. 

<h1 class="page-heading">Posts</h1>

<ul>
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url }}" title="{{ post.title }}">
      <span class="date">
        <span class="day">{{ post.date | date: '%d' }}</span>
        <span class="month"><abbr>{{ post.date | date: '%b' }}</abbr></span>
        <span class="year">{{ post.date | date: '%Y' }}</span>
      </span>
      <span class="title">{{ post.title }}</span>
    </a>
  </li>
  {% endfor %}
</ul>
