---
title: "Collections 2024"
excerpt: "<img src='https://joyxr.github.io/images/2024/2024_h1.jpg'>"
collection: portfolio
---

{%- for file in site.static_files -%}
  {%- if file.path contains '/images/2024/' and file.extname == '.jpg' or file.extname == '.JPG' -%}
    <img src="https://joyxr.github.io{{ file.path }}">
  {%- endif -%}
{%- endfor -%}
