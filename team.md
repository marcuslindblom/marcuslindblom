---
layout: page
title: Our team
permalink: /team/
---

## THE FACES OF ENCOM

{% for team_member in site.team %}
  <h2>{{ team_member.name }} - {{ team_member.position }}</h2>
  <p>{{ team_member.content | markdownify }}</p>
{% endfor %}