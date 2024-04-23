---
layout: archive
title: "Ph.D. Research"
permalink: /publications/
author_profile: true
---

I earned my Ph.D. in 2023 from Princeton University as a part of the [Maravelias Research
Group](https://maravelias.princeton.edu). My research focused on biofuel supply chain optimization.
Specifically, I ... 


### Publications

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


### Conference Papers


### Talks