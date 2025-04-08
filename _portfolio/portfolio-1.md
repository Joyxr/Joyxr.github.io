---
layout: archive
title: "Collections 2025"
excerpt: "<img src='https://joyxr.github.io/images/2025/2025_5.JPG'>"
collection: portfolio
---

{%- for file in site.static_files -%}
  {%- if file.path contains '/images/2025/' and file.extname == '.jpg' or file.extname == '.JPG' -%}
    <img src="https://joyxr.github.io{{ file.path }}">
  {%- endif -%}
{%- endfor -%}