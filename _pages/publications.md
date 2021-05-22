---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

  See <a href="{{author.googlescholar}}">Google Scholar</a>
  or <a href="{{author.orcid}}">ORCID</a> profile for my publications.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
