---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

This page shows my main research publications. The full list of publications is available on <u><a href="https://scholar.google.com/citations?user=26yB7xkAAAAJ&hl=en&oi=ao" target="_blank">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
