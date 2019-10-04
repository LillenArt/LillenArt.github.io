---
layout: page
permalink: /archive/
title: Archive
---

<ul>
  {% for post in site.posts %}
   <li>
        <h3>
          <a href="{{ post.url }}">
            {{ post.title }}
            <small>{{ post.date | date_to_string }}</small>
          </a>
        </h3>
      </li>
  {% endfor %}
</ul>




