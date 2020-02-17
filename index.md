---
layout: blog-home
title: Blog
---
<h1>Latest Posts</h1>

<ul class="cBlogList">
  {% for post in site.posts %}
    <li>
      <p class="cDate">{{ post.published-date }}</p>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p class="cAuthor">{{ post.author }}</p>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>