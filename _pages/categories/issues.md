---
title: "issue"
permalink: /categories/issue/
layout: archive
author_profile: true
---

{% assign posts = site.tags['issue'] %}
{% for post in posts %} 
    {% if post.url contains "%EB%85%BC%EB%AC%B8%EB%A6%AC%EB%B7%B0" %}
        {% include archive-single.html type=page.entries_layout %}
    {% endif %}
{% endfor %}