---
layout: single
title: "Title of Paper"
collection: research
excerpt: "Published in Journal 1, 2020"
permalink: /research/paper-1
# scholar: "..."
author_profile: true
order: 1
---

*{{ page.excerpt }}*

- description...

{% if page.scholar %}
<br>
<a href="{{ page.scholar }}" target="_blank" class="btn btn--primary">
  <i class="fab fa-fw fa-google-scholar"></i> Google Scholar
</a>
{% endif %} 
