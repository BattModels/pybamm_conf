---
layout: default
title: Home
permalink: /
---

# PyBaMM Battery Modelling Conference

A unique event for everyone from the curious to advanced battery model developers and researchers. The conference combines two science-focused days with invited plenaries and student/early-career talks.

<!-- [Register now]({{ site.data.site.register_url }}){: .button } -->

<section class="date-block" aria-label="Conference dates">
  <h2 class="date-title">PyBaMM Conference 2026</h2>
  <div class="header_dates-wrap date-row">
    <div class="header_dates-item date-tile">
      <div class="date-month">Oct</div>
      <div class="header_dates-day"><div class="date-day">15</div></div>
    </div>
    <div class="header_dates-item date-tile">
      <div class="date-month">Oct</div>
      <div class="header_dates-day"><div class="date-day">16</div></div>
    </div>
  </div>
</section>

<!-- <div class="hero-grid"> -->
<!-- {% for image in site.data.site.hero_images %} -->
<!--   <img class="hero-image" src="{{ image }}" alt="PyBaMM conference" /> -->
<!-- {% endfor %} -->
<!-- </div> -->

## Conference Snapshot

<div class="meta-grid">
  <div class="card"><strong>Dates</strong><br />October 15-16, 2026</div>
  <div class="card"><strong>Venue</strong><br />Rogel Ballroom, Michigan Union, Ann Arbor, Michigan, USA</div>
</div>

<!-- ## Keynote Speakers -->

<!-- <div class="speaker-grid"> -->
<!-- {% for speaker in site.data.speakers %} -->
<!-- {% if speaker.group == "keynote" %} -->
<!-- <div class="card speaker-card"> -->
<!--   <img class="speaker-image" src="{{ speaker.image }}" alt="{{ speaker.name }}" /> -->
<!--   <h3>{{ speaker.name }}</h3> -->
<!--   <p><strong>{{ speaker.role }}</strong></p> -->
<!--   <p>{{ speaker.bio }}</p> -->
<!-- </div> -->
<!-- {% endif %} -->
<!-- {% endfor %} -->
<!-- </div> -->

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
  <a class="logo-card{% if institution.name == 'MIDAS' %} is-midas{% endif %}" href="{{ institution.url }}" target="_blank" rel="noopener noreferrer" aria-label="Visit {{ institution.name }}">
    <img class="institution-logo" src="{{ institution.logo }}" alt="{{ institution.name }} logo" />
  </a>
{% endfor %}
</div>
