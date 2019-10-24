---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.journal_papers reversed %}
  {% include archive-single.html %}
{% endfor %}

## Conference Papers
{% for post in site.conference_papers reversed %}
  {% include archive-single.html %}
{% endfor %}

## Other Publications
{% for post in site.other_publications reversed %}
  {% include archive-single.html %}
{% endfor %}
