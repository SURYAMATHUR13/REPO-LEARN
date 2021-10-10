---
author: SURYA
title: TATA SONS
layout: Template
---

{% include tatasons.txt %}

## Page compiled by {{page.author}}

# JRDTATA- Indian pioneer industrialist who built **INDIA**

## Tata-Air India DEAL

{% for entry in site.data.news %}
-  {{entry.year}}: {{entry.news}}
{% endfor %}

- #syntax rendered output will be H1
- ##syntax rendered output will be H2
- ** ** rendered output will be **BOLD**
- ** rendered output will be *Itallic*
- **>** rendered output will be different font style

|Syntax|Output-style|
|------|------------|
|Example 1|Title 1|
|Example 2|Title 2|
