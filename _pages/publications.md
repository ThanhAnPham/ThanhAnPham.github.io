---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


{% if author.googlescholar %}
  You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?user=_ZJ9X0QAAAAJ&hl=fr&authuser=1) 
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
