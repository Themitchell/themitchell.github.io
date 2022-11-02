---
layout: home
---

Software engineering and DevOps Consultant with over 10 years experience working remotely with clients, large and small, to upskill teams and build proven large scale digital products and platforms.

My focus is on delivering maintainable software in an open, transparent fashion, relying on Agile methodologies as a tool to deliver the best solution. I lead, teach and mentor teams in both technical and non technical aspects of the development lifecycle and take pride in being motivated and pragmatic in my approach to engineering.

I am passionate about being human in my interactions and working with others to find the right solutions.

<h2>Blog<h2>
{% for post in site.posts %}
<div class="post">
 <h3 class="title"><a href="{{ post.url }}">{{ post.title }}</a></h3>
 <p class="meta">Date: {{ post.date }}</p>
 <div class="entry">
  {{ post.content | strip_html | truncatewords: 100 }}
 </div>
</div>
{% endfor %}
