---
# Mr. Green Jekyll Theme - v1.0.1 (https://github.com/MrGreensWorkshop/MrGreen-JekyllTheme)
# Copyright (c) 2022 Mr. Green's Workshop https://www.MrGreensWorkshop.com
# Licensed under MIT

layout: default
# Links page
---
{%- include multi_lng/get-lng-by-url.liquid -%}
{%- assign lng = get_lng -%}

{%- assign links_data = page.page_data | default: site.data.content.links[lng].page_data -%}

<div class="multipurpose-container links-heading-container">
  <h1>Schedule</h1>
  <p>{{ links_data.main.info | default: "No data, check page_data in [language]/tabs/links.md front matter or _data/content/links/[language].yml" }}</p>
</div>

{%- if site.data.conf.others.links.use_rows_as_link -%}{%- assign hover_class = "table-hover" -%}{%- endif -%}
{%- for category in links_data.category %}
<div class="multipurpose-container link-container" id="{{ category.type }}" style="border-left-color:{{ category.color }};">
  <h2>{{ category.title }}</h2>
  <table class="table {{ hover_class }}">
    <tbody>
      {%- for list in links_data.list %}
        {%- if list.type != category.type %}{% continue %}{% endif -%}
        {%- if site.data.conf.others.links.use_rows_as_link -%}
          {%- capture link_onclick -%} onclick="openURL('{{ list.url }}');" style="cursor: pointer;" {%- endcapture -%}
          {%- capture link_url -%} <b>{{ list.title }}</b> {%- endcapture -%}
        {% else %}
          {%- assign link_onclick = nil -%}
          {%- capture link_url -%} <a href="{{ list.url }}" target="_blank" rel="noopener noreferrer"><b>{{ list.title }}</b></a> {%- endcapture -%}
        {%- endif %}



        <tr class="link-item" {{ link_onclick }}>
          <td>
            <p><b>Lecture</b></p>
          </td>
          <td>
            <p>{{ list.lecture }}</p>
          </td>
        </tr>

        <tr class="link-item" {{ link_onclick }}>
          <td>
            <p><b>Lab</b></p>
          </td>
          <td>
            <p>{{ list.lab }}</p>
          </td>
        </tr>

        <tr class="link-item" {{ link_onclick }}>
          <td>
            <p><b>Machine Problem</b></p>
          </td>
          <td>
            <p>{{ list.mp }}</p>
          </td>
        </tr>
      {%- endfor %}
    </tbody>
  </table>
</div>
{% endfor %}
