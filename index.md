---
layout: blog-home
title: Blog
---
<h1>Ballerina blog</h1>

<ul class="cBlogList">
  {% for post in site.posts %}
    <li>
      <p class="cDate">{{ post.published-date }}</p>
      <h2><a href="https://madhuramendis.github.io/ballerina-jekyll-blog/{{ post.url }}">{{ post.title }}</a></h2>
      <p class="cAuthor">{{ post.author }}</p>
      <p>{{ post.abstract }}</p>
      <!-- {{ post.excerpt }} -->
    </li>
  {% endfor %}
</ul>