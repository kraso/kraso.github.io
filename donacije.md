---
layout: default
---

# Donatorji

Donator | Znesek
--- | ---
{% for vplacilo in site.data.vplacila %}
{{ vplacilo.ime }} | {{ vplacilo.znesek }}
