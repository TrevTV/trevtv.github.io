---
title: I Expect You To Die - bHaptics Integration
show_ieytd_download: true
---

## Installation
Todo

## Changelogs
{% for version in site.data.ieytd_versions %}
#### {{version[0]}}
    {% for log in version %}
        {% if log != version[0] %}
        
            - {{log}}
        {% endif %}
    {% endfor %}
{% endfor %}