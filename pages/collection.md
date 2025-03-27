---
layout: page
title: Browse the Collection
permalink: /collection/
---

## All Images
{% include gallery.html collection='PUNC' facet_by='angle*, distance*, location*, movement*, lighting*, composition*, duration*' %}

{% comment %}
{% include collection_gallery.html collection='PUNC' %}

## By Angle
{% include collection_gallery.html facet_by='angle' collection='PUNC' %}

## By Distance
{% include collection_gallery.html facet_by='distance' collection='PUNC' %}

## By Location
{% include collection_gallery.html facet_by='location' collection='PUNC' %}

## By Movement
{% include collection_gallery.html facet_by='movement' collection='PUNC' %}

## By Lighting
{% include collection_gallery.html facet_by='lighting' collection='PUNC' %}

## By Composition
{% include collection_gallery.html facet_by='composition' collection='PUNC' %}

## By Duration
{% include collection_gallery.html facet_by='duration' collection='PUNC' %}
{% endcomment %}
{% comment %}
- film
- angle
- distance
- location
- movement
- lighting
- composition
- duration
## By Object Type

### Manuscripts
{% include collection_gallery.html facet_by='object_type' only='manuscript' collection='qatar' %}
### Portraits
{% include collection_gallery.html facet_by='object_type' only='portrait' collection='qatar' %}
### Maps
{% include collection_gallery.html facet_by='object_type' only='map' collection='qatar' %}
### Panels
{% include collection_gallery.html facet_by='object_type' only='panel' collection='qatar' %}
{% endcomment %}