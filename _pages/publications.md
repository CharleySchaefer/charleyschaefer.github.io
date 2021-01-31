---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Below a number of selected publications is given.
For the most comprehensive list of publications I refer to my [google scholar](https://scholar.google.co.uk/citations?user=SKHIHrEAAAAJ&hl=nl) account.
Unpublished manuscripts (preprints) and posters are available at my [ResearchGate](https://www.researchgate.net/profile/Charley_Schaefer2) account.


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
