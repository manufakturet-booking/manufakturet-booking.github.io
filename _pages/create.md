---
layout: category
title: Create
author_profile: true
tags: video-cameras zoom-recorders
sidebar:
  nav: "fyi"
---
# My create pages
stuff

## second heading

stuff

### third heading

{% for post in site.categories.create %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

A test create page.

_This text is in create.md in the _pages folder_

*** This page should have floating boxes displaying sub categories ***
- sub category leads to sub page with list of items in the category
- a side menu not expanded
- advisory text at top

**It uses the category layout**
