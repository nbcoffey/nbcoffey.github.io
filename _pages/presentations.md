---
permalink: /presentations/
title: "Presentations"
classes: wide
# excerpt: "Here are some presentations."
header:
  overlay_image: /assets/images/presentation-agu2022.jpg
  overlay_filter: 0.2  # Darkens the image (0.0 = no darkening, 1.0 = completely black)
  caption: "AGU22 in Chicago's McCormick Place, December 2022"
---
<style>
.page__hero--overlay {
  min-height: 450px !important;
  background-position: 70% 30% !important;
}
</style>

### Presenter in Bold
### Presentations

<ul style="list-style: none; padding-left: 0; margin-left: 0;">
  {% assign count = site.data.presentations | size %}
  {% for pres in site.data.presentations %}
    <li style="margin-bottom: 1.5em; text-indent: -2.5em; padding-left: 2.5em; list-style-type: none;">
      <strong>[{{ count }}]</strong> <em>{{ pres.type }}</em>, {{ pres.pre_authors }}<strong>{{ pres.my_name }}</strong>{{ pres.co_authors }}, "{{ pres.title }}," {{ pres.venue }}.
    </li>
    {% assign count = count | minus: 1 %}
  {% endfor %}
</ul>

