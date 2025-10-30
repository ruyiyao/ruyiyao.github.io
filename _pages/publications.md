---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}


{% assign pubs = site.publications | sort: "date" | reverse | sort: "priority" %}
{% for post in pubs %}
  {% include archive-single.html %}
{% endfor %}
