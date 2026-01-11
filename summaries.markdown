---
layout: page
title: Summaries
permalink: /summaries/
---

(Last updated on 1st January 2026)

A compilation of texts highlighted from the books I have read. They don't summarize the book, I found these sections of the book quite interesting.

<ul>
{% for book in site.summaries %}
  <li>
    <a href="{{ book.url | relative_url }}">
      {{ book.title }}
    </a>
  </li>
{% endfor %}
</ul>