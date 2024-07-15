---
layout: archive
title: "Publications"
permalink: /publication/
author_profile: true
---

<style>
  .publication-section {
    margin-bottom: 2em;
  }

  .publication-title {
    font-size: 1.5em;
    font-weight: bold;
    color: #2c3e50;
    margin-top: 1em;
  }

  .publication-meta {
    font-size: 1em;
    color: #7f8c8d;
    margin-top: 0.5em;
    margin-bottom: 0.5em;
  }

  .publication-keywords {
    margin-top: 0.5em;
    font-style: italic;
    color: #34495e;
  }

  .publication-excerpt {
    margin-top: 1em;
    margin-bottom: 1em;
  }

  .keyword {
    background-color: #f1f1f1;
    padding: 0.2em 0.4em;
    border-radius: 0.2em;
    margin-right: 0.3em;
  }

  .download-links a {
    margin-right: 1em;
  }
</style>

{% if site.author.googlescholar %}
<div class="wordwrap">
  You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.
</div>
{% endif %}

<div class="publication-section">
  <h2 class="publication-title">First-Author Papers</h2>
  {% include base_path %}

  {% for post in site.publication reversed %}
    {% if post.authorship == "first" %}
      {% include archive-single.html %}
    {% endif %}
  {% endfor %}
</div>

<div class="publication-section">
  <h2 class="publication-title">Highlighted Co-author Papers</h2>
  {% include base_path %}

  {% for post in site.publication reversed %}
    {% if post.authorship == "coauthor" %}
      {% include archive-single.html %}
    {% endif %}
  {% endfor %}
</div>

<div class="publication-section">
  <h2 class="publication-title">Book Chapters</h2>
  {% include base_path %}

  {% for post in site.publication reversed %}
    {% if post.title contains "Book" %}
      {% include archive-single.html %}
    {% endif %}
  {% endfor %}
</div>
