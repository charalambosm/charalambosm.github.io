---
layout: default
title: Home
---

# Hi, I'm Charalambos 👋

Software Quality Engineer & EEE MEng. I test, break, and improve things.

## Highlights
- 🔧 QA/Test Engineering projects
- 📊 Analytics & automation experiments
- 🧪 Notes and write-ups

## Quick Links
- 🐙 [GitHub Profile](https://github.com/charalambosm)
- ✉️ [Email](mailto:you@example.com)

## Recent Posts
<!-- Jekyll will list posts under /_posts automatically; this is a simple loop -->
<ul>
{%- for post in site.posts limit:5 -%}
  <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> <small>({{ post.date | date: "%b %d, %Y" }})</small></li>
{%- endfor -%}
</ul>
