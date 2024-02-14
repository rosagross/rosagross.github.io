---
title:  "Posts"
layout: archive
permalink: /Posts/
author_profile: true
comments: true
entries_layout: grid
---

<!--- change limit from 1 to no limit! -->
{% for post in site.posts limit:1 %} 
  {% include archive-single.html %}
{% endfor %} 

