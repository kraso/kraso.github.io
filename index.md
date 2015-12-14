---
layout: default
---

[yes]: {{ site.url }}pictures/yes_small.png "Yes"
[no]: {{ site.url }}pictures/no_small.png "No"

## Billiards!

{{ site.welcome_text }}

## Trenutno zbran denar
{{ site.zbran_denar }}

{% page.zbranDenar=0 %}
{% for vplacilo in site.data.vplacila %}
{%   page.zbranDenar = page.zbranDenar + vplacilo.znesek %}
{% endfor %}
{{ page.zbranDenar }}

## Milestones:

|Completed | Znesek | Miza |
| :---: | :---: | :---: |
| ![][yes] | 500 | Miza 1 |
| ![][yes] | 1000 | Miza 2 |
| ![][no] | 2000 | Miza 3 |

[Donacije](../donacije)
