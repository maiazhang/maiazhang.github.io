---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: single
author_profile: true
title: ""
---

<div class="posts">
  {% for post in site.posts %}
    <article class="post">
      <h2>{{ post.title }}</h2>
      {{ post.content }}
    </article>
  {% endfor %}
</div>