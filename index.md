---
layout: default
title: Home
permalink: /
---

# PyBaMM Battery Modelling Conference

A unique event for everyone from the curious to advanced battery model developers and researchers. The conference combines two science-focused days with invited plenaries and student/early-career talks, followed by a dedicated PyBaMM training day.

[Register now]({{ site.data.site.register_url }}){: .button }

<div class="hero-grid">
{% for image in site.data.site.hero_images %}
  <img class="hero-image" src="{{ image }}" alt="PyBaMM conference" />
{% endfor %}
</div>

## Conference Snapshot

<div class="meta-grid">
  <div class="card"><strong>Dates</strong><br />February 5-7, 2025</div>
  <div class="card"><strong>Main Venue</strong><br />Plaisterers' Hall, One London Wall, London, UK</div>
  <div class="card"><strong>Training Day</strong><br />Friday, February 7</div>
</div>

## Keynote Speakers

<div class="speaker-grid">
{% for speaker in site.data.speakers %}
{% if speaker.group == "keynote" %}
<div class="card speaker-card">
  <img class="speaker-image" src="{{ speaker.image }}" alt="{{ speaker.name }}" />
  <h3>{{ speaker.name }}</h3>
  <p><strong>{{ speaker.role }}</strong></p>
  <p>{{ speaker.bio }}</p>
</div>
{% endif %}
{% endfor %}
</div>

## Organizers

<div class="speaker-grid">
{% for speaker in site.data.speakers %}
{% if speaker.group == "organizer" %}
<div class="card speaker-card">
  <img class="speaker-image" src="{{ speaker.image }}" alt="{{ speaker.name }}" />
  <h3>{{ speaker.name }}</h3>
  <p><strong>{{ speaker.role }}</strong></p>
  <p>{{ speaker.bio }}</p>
</div>
{% endif %}
{% endfor %}
</div>

## Associated Institutions

<div class="logo-grid">
{% for institution in site.data.institutions %}
  <div class="logo-card">
    <img class="institution-logo" src="{{ institution.logo }}" alt="{{ institution.name }} logo" />
  </div>
{% endfor %}
</div>
