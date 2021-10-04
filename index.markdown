---
layout: splash
title: "SmartPV - Photovoltaik mit dem gewissen Extra"
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/unsplash-image-1.jpg
hidden: true
excerpt: "Was, wenn deine Photovoltaikanlage mehr könnte als nur Strom erzeugen? "
intro: 
  - excerpt: 'Dieser Blog ist von einem Nerd für Nerds, die sich mit dem Thema SmartHome beschäftigen. Einen besonderen Fokus lege ich auf Energieeffizienz.'
---



{% include feature_row id="intro" type="center" %}

{% if paginator %}
  {% assign posts = paginator.posts %}
{% else %}
  {% assign posts = site.posts %}
{% endif %}

{% assign entries_layout = page.entries_layout | default: 'grid' %}
<div class="entries-{{ entries_layout }}">
  {% for post in posts %}
    {% include archive-single.html type=entries_layout %}
  {% endfor %}
</div>

{% include paginator.html %}
