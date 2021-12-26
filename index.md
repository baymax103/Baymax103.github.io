---
layout: home
---

{% if site.theme_config.show_projects == true %}
  <h2>{{ site.theme_config.home.title_projects }}</h2>
  {% include card_list.html collection=site.data.home.project_entries %}
{% endif %}