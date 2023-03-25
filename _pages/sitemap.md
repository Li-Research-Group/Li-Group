---
layout: splash
title: 'Sitemap'
permalink: /sitemap/
---

<br>
A list of all the posts and pages found on the site.

<h1>Pages</h1>
{% for post in site.pages %}
  {% include archive-single.html %}
{% endfor %}