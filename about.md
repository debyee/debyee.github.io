---
layout: page
title: about
image: /assets/img/DebbieYee_profile.jpg
permalink: /about/
---

{% if site.author.bio %}
  {{ site.author.bio | markdownify }}
{% endif %}