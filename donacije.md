---
layout: default
---

# Donatorji

Donator | Znesek
--- | ---
Oseba 4 | 5000
{% for vplacilo in site.data.vplacila %}
{{ vplacilo.ime }} | {{ vplacilo.znesek }}
{% endfor %}
