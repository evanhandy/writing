---
layout: single
title: Stories
permalink: /stories/
---

Here you'll find links to all of my stories. Click on a link to go to a list of that story's scenes.

{% for story in site.data.stories %}
  <h2><a href="{{ story.permalink }}">{{ story.title }}</a></h2>

  {{ story.description }}

  [![{{ story.title }}]({{ story.image }})]({{ story.permalink }})
{% endfor %}
