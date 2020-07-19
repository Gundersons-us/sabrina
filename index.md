---
layout: default
title: The Circus
---

# {{ site.title }}

## {{ site.description }}

### Posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | prepend:site.baseurl }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
