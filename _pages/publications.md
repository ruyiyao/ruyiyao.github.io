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


{% assign pubs = site.publications | sort: "priority" %}
{% for post in pubs %}
  {% include archive-single.html %}
{% endfor %}

{% comment %}
Original sort rule (by date reversed)
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
{% endcomment %}
