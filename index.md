---
layout: home
title: SANDLab
subtitle: Systemic Autonomic Neuro Dynamics Lab
---

{% assign news_page = site.pages | where: "path", "news.md" | first %}
<div class="ticker-container">
  <div class="ticker-label">LATEST</div>
  <div class="ticker-window">
    <div class="ticker-track">
      {% assign elements = news_page.content | split: '<li class="ticker-news">' %}
      {% for element in elements offset:1 %}
        {% assign item = element | split: '</li>' | first | strip_html %}
        <div class="ticker-item">{{ item }}</div>
      {% endfor %}
      {% for element in elements offset:1 %}
        {% assign item = element | split: '</li>' | first | strip_html %}
        <div class="ticker-item">{{ item }}</div>
      {% endfor %}
    </div>
  </div>
</div>

<div class="jumbotron bg-white shadow-sm mt-4 py-5" style="border-radius: 15px; border-left: 8px solid #003262;">
  <h2 class="text-dark">Welcome to the **Systemic Autonomic Neuro Dynamics (SAND) Lab**</h2>
  <p class="lead mt-3">
    We bridge <strong>computation, engineering, and physiology</strong> to understand disease and build precision solutions. We capture human body data currently inaccessible to the healthcare system.
  </p>
  <div class="d-flex align-items-center mt-4">
    <span class="badge badge-primary p-2 mr-2">UC Berkeley</span>
    <span class="badge badge-info p-2">UCSF</span>
    <span class="ml-3 text-muted"><em>Dual-Institutional Research</em></span>
  </div>
</div>

<div class="row text-center mt-5">
  <div class="col-md-3 col-6 mb-3">
    <a href="/sandya" class="btn btn-outline-primary btn-block py-3 shadow-sm">Prof. Subramanian</a>
  </div>
  <div class="col-md-3 col-6 mb-3">
    <a href="/research" class="btn btn-outline-primary btn-block py-3 shadow-sm">Research</a>
  </div>
  <div class="col-md-3 col-6 mb-3">
    <a href="/publications_page" class="btn btn-outline-primary btn-block py-3 shadow-sm">Publications</a>
  </div>
  <div class="col-md-3 col-6 mb-3">
    <a href="/news" class="btn btn-outline-primary btn-block py-3 shadow-sm">Lab News</a>
  </div>
</div>

<div class="row mt-5 mb-5">
  <div class="col-md-7">
    <h3>Our Values</h3>
    <p>We believe that innovative solutions come from diverse backgrounds working as a team. We are committed to an inclusive environment and high-quality mentorship that empowers trainees to reach their career goals.</p>
  </div>
  <div class="col-md-5 bg-light p-4 shadow-sm border-rounded" style="border-radius: 12px;">
    <h4 class="text-primary">We are recruiting!</h4>
    <p class="small">Interested in joining our interdisciplinary team?</p>
    <a href="https://docs.google.com/document/d/18HSRw8P7dqVkpWCDEW89U1pUrczRmdDNJ0QUJZUHaIk/edit?usp=sharing" class="btn btn-dark btn-sm mr-2">Expectations</a>
    <a href="/join" class="btn btn-primary btn-sm">Join Us</a>
  </div>
</div>

<style>
/* TICKER STYLING */
.ticker-container { display: flex; background: #003262; color: white; border-radius: 4px; overflow: hidden; font-family: sans-serif; }
.ticker-label { background: #FDB515; color: #003262; padding: 10px 20px; font-weight: bold; z-index: 2; }
.ticker-window { overflow: hidden; white-space: nowrap; flex-grow: 1; display: flex; align-items: center; }
.ticker-track { display: inline-block; animation: scroll 35s linear infinite; }
.ticker-track:hover { animation-play-state: paused; }
.ticker-item { display: inline-block; padding: 0 60px; font-weight: 500; font-size: 0.95rem; }

@keyframes scroll {
  0% { transform: translateX(0); }
  100% { transform: translateX(-50%); }
}

/* BUTTON HOVER */
.btn-outline-primary:hover {
  background-color: #003262;
  color: white;
  transform: translateY(-3px);
  transition: all 0.3s;
}
</style>
