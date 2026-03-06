---
layout: default
title: Speakers
permalink: /speakers/
---

## Keynote Speakers

<div class="speaker-grid">
{% for speaker in site.data.speakers %}
<div class="card speaker-card">
  <img class="speaker-image" src="{{ speaker.image | relative_url }}" alt="{{ speaker.name }}" />
  <h3>{{ speaker.name }}</h3>
  <p><strong>{{ speaker.role }}</strong></p>
  <p>{{ speaker.bio }}</p>
</div>
{% endfor %}
</div>
