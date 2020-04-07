---
layout: about
permalink: /
title: Dylan Van Assche
description: Semantic Web PhD Researcher

profile:
  align: right
  image: avatar.png
news: false
social: true
webid: webid.html
---

My name is Dylan Van Assche, I'm a PhD researcher in Computer Science at IDLab Ghent.
My research focuses on Knowledge Graph generation and Linked Open Data to decentralize the Web once again! 

Besides my research, I spent my free time programming applications and tools, 3D printing and working on my modelrailroad.
I'm also advocating for publishing everything as Open Source since we can always learn from each other by sharing your ideas and tricks.

If you want to follow my latest work, checkout my [blog]({{ site.baseurl }}/blog) {% if site.twitter_username %}or follow me on <a href="https://twitter.com/{{ site.twitter_username }}" target="_blank" title="Twitter">Twitter</a>{% endif %}!

{% if page.webid %}
  {% include {{ page.webid }} %}
{% endif %}
