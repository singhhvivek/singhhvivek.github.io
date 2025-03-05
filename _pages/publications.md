---
title: "Publications"
permalink: /publications/
layout: archive
collection: publications
---
{% for post in site.publications reversed %}
  {% include publication.html %}
{% endfor %}