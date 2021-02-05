---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


<script src="https://bibbase.org/show?bib=https%3A%2F%2Fgithub.com%2Fvvandewa%2Fvvandewa.github.io%2Fraw%2Fmaster%2F_pages%2Freferences.bib&jsonp=1"></script>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
