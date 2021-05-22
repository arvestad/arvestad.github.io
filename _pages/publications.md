---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  See <u><a href="{{author.googlescholar}}">my Google Scholar</a>
  or <u> <a href="{{author.orcid}}">ORCID</a> profile for my publications.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
