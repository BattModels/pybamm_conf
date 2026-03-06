---
layout: default
title: Home
permalink: /
---

# PyBaMM Battery Modelling Conference

A unique event for everyone from the curious to advanced battery model developers and researchers. The conference combines two science-focused days with invited plenaries and student/early-career talks.

<!-- [Register now]({{ site.data.site.register_url }}){: .button } -->

<section class="conference-overview date-block" aria-label="Conference overview">
  <h2 class="date-title">PyBaMM Conference 2026</h2>
  <div class="date-row">
    <div class="date-pill">
      <div class="date-month">Oct</div>
      <div class="date-day">15</div>
    </div>
    <div class="date-pill">
      <div class="date-month">Oct</div>
      <div class="date-day">16</div>
    </div>
  </div>
  <div class="overview-grid">
    <div class="overview-item">
      <div class="overview-label">Venue</div>
      <div class="overview-value">Rogel Ballroom, Michigan Union</div>
    </div>
    <div class="overview-item">
      <div class="overview-label">Location</div>
      <div class="overview-value">Ann Arbor, Michigan, USA</div>
    </div>
  </div>
</section>

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
