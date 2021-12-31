---
title: "Welcome to my blog"
---

Welcome to my blog, I live in Porto, Portugal and work at the Power BI CAT Team at Microsoft.

I'm very passionate about Data & Power BI and this blog purpose is to share my learnings on the amazing Microsoft Data Stack.

{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}
