---
layout: default
title: Blog
---


<div id="home">
  Nothing there... many ideas of posts (see my various one page discussion on https://github.com/MatthieuStigler/Misconometrics), but I should focus on my dissertation for now. 
  
  <h1>Blog Posts</h1>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
</div>
