---
nav_order: 6
icon: people
title: AI Steering Team
permalink: /team/
---


{% for p in site.data.team %}
- {{p.name}}
{% endfor %}