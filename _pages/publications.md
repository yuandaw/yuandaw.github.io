---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% if site.author.googlescholar %}
  You can also find my articles on <a href="{{ site.author.googlescholar }}">my Google Scholar profile</a>.
{% endif %}

{% assign publications_by_year = site.publications | sort: 'date' | reverse | group_by_exp: "item", "item.date | date: '%Y'" %}

{% for year_group in publications_by_year %}
  <h2 style="margin-top:1.8em; margin-bottom:0.6em; font-size:1.5em; font-weight:700; text-transform:uppercase; letter-spacing:0.08em; color:#2563eb;">{{ year_group.name }}</h2>
  {% for post in year_group.items %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}
