---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <a href="https://www.semanticscholar.org/author/Nadav-Oved/1382650252?sort=pub-date">Semantic Scholar</a>.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
