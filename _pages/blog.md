---
layout: archive
permalink: /blog/
title: "Blog posts by tags"
author_profile: true
header:
    # image: "/images/NAME.jpg"

categories: [blog]
# tags: [hot, summer]
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>