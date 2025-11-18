---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

Here is a selection of my publications and manuscripts.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
