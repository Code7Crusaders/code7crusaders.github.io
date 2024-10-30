---
layout: default
title: Documentation
---

<h2>Documentation Index</h2>

<ul>
    {% for doc in site.docs %}
        {% if doc.path contains 'Candidatura' %}
            <li>
                <a href="{{ doc.url | relative_url }}">{{ doc.title }}</a>
            </li>
        {% endif %}
    {% endfor %}
</ul>

