---
permalink: /news/
title: "News"
description: "News and updates from Yi Liu — paper acceptances, awards, service, and appointments in LLM security, AI agent security, and software engineering."
author_profile: true
---

{% for item in site.data.news -%}
- *{{ item.date }}*: {{ item.text }}
{% endfor %}
