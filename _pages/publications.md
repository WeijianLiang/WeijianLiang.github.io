---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


{% assign publications = site.data.publications | sort: "year" | reverse %}

<ul>
{% for pub in publications %}
  <li>
    <p><strong>{{ forloop.index }}.</strong> {{ pub.authors }} ({{ pub.year }}). {{ pub.title }}.  
    <i>{{ pub.journal }}</i>, <i>{{ pub.volume }}</i>, {{ pub.pages }}.</p>
    <p><strong>DOI:</strong> <a href="https://doi.org/{{ pub.doi }}" target="_blank">https://doi.org/{{ pub.doi }}</a></p>
  </li>
{% endfor %}
</ul>