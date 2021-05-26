---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<u><a href="{https://scholar.google.com/citations?user=5vBe0IUAAAAJ&hl=en}">Google Scholar profile</a>.</u>
  
 (Most articles are open-access; please contact me if you have difficulty accessing any of my work and I will be happy to send you articles.)


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


