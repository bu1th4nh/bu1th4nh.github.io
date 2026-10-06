---
layout: archive
title: "Blog"
permalink: /blog/
description: "Notes on machine learning, research, engineering, and the occasional subject that refuses to fit neatly into those boxes."
section_label: "Writing"
---

{% if site.posts.size > 0 %}
<div class="archive-list">
  {% for post in site.posts %}
    {% include archive-single.html %}
  {% endfor %}
</div>
{% else %}
<div class="empty-state">No posts published yet. The infrastructure is ready; the opinions are still undergoing peer review.</div>
{% endif %}
