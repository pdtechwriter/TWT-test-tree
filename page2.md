---
layout: template_file
---

# How We Make Theatre

Our mission is to make the finest theatre productions of Shakespeare's plays, as well as other plays written when Shakespeare was alive or soon after and plays being written right now.

## Titanic's Passenger Details

{% for item in site.data.titanic %} 
- {{item.Name}}, {{item.Age}}
{% endfor %}
