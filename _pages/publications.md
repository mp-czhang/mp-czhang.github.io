---
layout: archive
title: "Publications"
permalink: /publication/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

First-Author Paper
======
{% include base_path %}

{% for post in site.publication reversed %}
  {% include archive-single.html %}
{% endfor %}

Highlighted Co-author Paper
======