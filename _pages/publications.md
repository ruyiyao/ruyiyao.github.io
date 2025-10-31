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




{% comment %}
First author first, then by date desc
{% endcomment %}

{% assign first_author_pubs = site.publications | where_exp: "post", "post.first_author == true" | sort: "date" | reverse %}
{% assign coauthor_pubs = site.publications | where_exp: "post", "post.first_author != true" | sort: "date" | reverse %}

{% assign pubs = first_author_pubs | concat: coauthor_pubs %}

{% for post in pubs %}
  {% include archive-single.html %}
{% endfor %}
