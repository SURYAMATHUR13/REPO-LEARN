---
Author:surya
layout: Template
---

## This page is written by {{ page.Author }}

# JRDTATA- Indian pioneer industrialist who built **INDIA**

## Tata-Air India DEAL

{% for anything in site.data.news %}
-  {{anything.latest}}: {{anything.old}}
{% endfor %}

{% include text_includes_file.txt %}

- #syntax rendered output will be H1
- ##syntax rendered output will be H2
- ** ** rendered output will be **BOLD**
- ** rendered output will be *Itallic*
- **>** rendered output will be different font style

|Syntax|Output-style|
|------|------------|
|Example 1|Title 1|
|Example 2|Title 2|
