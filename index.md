---
layout: default
---

## Billiards!

{{ site.welcome_text }}

## Trenutno zbran denar
{% assign zbranDenar = 0 %}
{% for vplacilo in site.data.vplacila %}
{% assign zbranDenar = zbranDenar + Number(vplacilo.znesek) %}
{% endfor %}
{{ zbranDenar }}

## Milestones:

| Completed | Znesek | Miza |
| :---: | :---: | :---: |

[Donacije](../donacije)
