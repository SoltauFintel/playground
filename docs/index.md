---
layout: default
---

# Hello Playground

## Second

bli blu blo

<a href="/playground/another-file.html">another file</a>

[another file](another-file.html)

## Blog

<ul>
  {% for post in site.posts %}
    <li>
      <a href="/playground{{post.url}}">{{post.title}}</a>
    </li>
  {% endfor %}
</ul>

## Text

Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
