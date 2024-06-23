---
layout: archive
title: "Publications"
permalink: /publication/
author_profile: true
---

{% if site.author.googlescholar %}
<div class="wordwrap">
  You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.
</div>
{% endif %}

# Publications

## First-Author Papers
---
{% include base_path %}

{% for post in site.publication reversed %}
  {% if post.authorship == "first" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Highlighted Co-author Papers
---
{% include base_path %}

{% for post in site.publication reversed %}
  {% if post.authorship == "coauthor" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Book Chapters
---
{% include base_path %}

{% for post in site.publication reversed %}
  {% if post.venue contains "Book" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
