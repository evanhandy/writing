---
layout: single
title: Stories
toc: true
toc_label: "Story List"
permalink: /stories/
---

Here you'll find links to all of my stories. Click on a link to go to a list of that story's scenes.

{% for story in site.data.stories %}

## {{ story.title }}
  
  {{ story.description }}
  
  [**Read story**]({{ story.permalink }})

  [![{{ story.title }}]({{ story.image }})]({{ story.permalink }})

  _________________
{% endfor %}
