---
layout: archive
title: "Art"
permalink: /art/
author_profile: true
---

{% include base_path %}

{% for post in site.art %}
  {% include archive-single.html %}
{% endfor %}
