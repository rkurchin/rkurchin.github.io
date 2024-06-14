---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

**Note:** This list is no longer updated. You can find my articles on <a href="https://scholar.google.ch/citations?user=CSHe53oAAAAJ&hl=en&oi=ao">my Google Scholar profile</a>.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
