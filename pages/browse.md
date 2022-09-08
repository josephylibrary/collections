---
title: Browse
layout: browse
permalink: /browse.html
# see _data/config-browse.csv for display options
# the Browse visualization will be added below the content in this file
collection: all
---
{% capture searchtext %}The search box on this page is very simple. It only searches for strings of text (i.e. words in a row) in the following fields for each item in the collection: 

{% for f in site.data.config-browse %}-{{f.field}}
{% endfor %}. 

You cannot use boolean searching (i.e. `ands` and/or `ors`) or quotation marks to refine your searches -- basically, all searches are searches for phrases that typically would be put in quotation marks in google, etc.

For more advanced searching capability, use the search box in the navbar above, or go to {{'/search.html/' | relative_url }}.
{% endcapture %}
{% include feature/modal.md text=searchtext button="What does this search and how can I use it?" color="outline-dark btn-sm float-right" title="How and What This page Searches" %}

## Browse All Items

*You are searching under the Nez Perce/Josephy Featured Archives database. To search under the Annotated Alvin Josephy Bibliography database, please [click here](https://library.josephy.org/annotated/browse.html). To search under the SAGE Josephy Library of Western History & Culture collection, which can be checked out, please [click here](https://catalog.sage.eou.edu/eg/opac/results?query=*&qtype=keyword&fg%3Amat_format=&locg=175&detail_record_view=1&_adv=1&sort=).*



