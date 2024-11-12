---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find a list of my publications on my <a href="https://scholar.google.com/citations?user=rwID4_AAAAAJ&hl=en">Google Scholar profile</a>.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}