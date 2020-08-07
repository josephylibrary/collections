---
title: Browse
layout: browse
permalink: /browse.html
# see _data/config-browse.csv for display options
# the Browse visualization will be added below the content in this file
collection: all
---
{%- assign collections = site.data[site.metadata] | map: 'collection' | compact | uniq -%}
Filter by Collection: {% for collection in collections %}<a class="btn btn-outline-primary m-2 text-wrap" href="/collections/browse.html#{{collection}}">{{collection}}</a>{% endfor %}

## Browse All Items
