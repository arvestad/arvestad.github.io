---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

  See <a href="https://scholar.google.se/citations?user=t3xciDsAAAAJ&hl=en">Google Scholar</a>
  or <a href="https://orcid.org/0000-0001-5341-1733">ORCID</a> profile for my publications.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
