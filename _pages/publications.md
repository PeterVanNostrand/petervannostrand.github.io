---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<style>
  a { color: #494e52; }
</style>

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on my <a href="{{site.author.googlescholar}}">Google Scholar Profile</a>.<br><br>If one of my articles has been paywalled feel free to <a href="mailto:{{ author.email }}">shoot me an email</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
