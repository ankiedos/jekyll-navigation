---
---
<nav>
{%- for link in site.navbar -%}
{%- unless link == include.current -%}
  <a href="{{ link }}">{{ link | replace site.domain_name, '' | default: site.github.repository_name | replace: '-', ' ' | capitalize }}</a>
{%- endunless -%}
</nav>
