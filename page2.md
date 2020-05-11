---
layout: my-test
title: Page 2
---

# Hello from Page 2

## And a sub-section of page 2
Some sub-section text.

## Data test
{% for item in site.data.summary %}
{{item.thing}} : {{item.dataX}} , {{item.dataY}}
{% endfor %}

