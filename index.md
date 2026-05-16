---
layout: home
title: SANDLab
subtitle: Systemic Autonomic Neuro Dynamics Lab
---

{% assign news_page = site.pages | where: "path", "news.md" | first %}

<div class="row mt-4">
  <div class="col-lg-8">
    <div class="jumbotron bg-white shadow-sm h-100 py-5 px-4" style="border-radius: 15px; border-left: 8px solid #008080;">
      <h2 class="text-dark">Welcome to SANDLab!</h2>
      <p class="lead mt-3" style="color: #008080; font-weight: 600; font-size: 1.3rem;">
        Harnessing AI to understand human physiology
      </p>
      <p class="mt-2">
        We bridge <strong>computation, engineering, and physiology</strong> to understand disease and build precision solutions. We capture human body data currently inaccessible to the healthcare system.
      </p>
      <div class="d-flex align-items-center mt-4">
        <span class="badge badge-info p-2 mr-2" style="background-color: #008080;">UC Berkeley</span>
        <span class="badge badge-secondary p-2" style="background-color: #4A5D6E;">UCSF</span>
      </div>
    </div>
  </div>

  <div class="col-lg-4">
    <div class="card shadow-sm h-100 border-0" style="border-radius: 15px; background-color: #f8fbfb;">
      <div class="card-body">
        <h5 class="card-title" style="color: #008080;">Latest Highlights</h5>
        <hr style="border-top: 1px solid #e0eeee;">
        <ul class="list-unstyled">
          {% if news_page and news_page.ticker_items %}
            {% for item in news_page.ticker_items limit:3 %}
              <li class="mb-3" style="font-size: 0.9rem; line-height: 1.4;">
                <span style="color: #008080; font-weight: bold;">•</span> {{ item }}
              </li>
            {% endfor %}
          {% else %}
             <li class="small text-muted">Check our news page for the latest updates.</li>
          {% endif %}
        </ul>
        <a href="/news" class="btn btn-link btn-sm p-0 mt-2" style="color: #008080; font-weight: 600;">View all news →</a>
      </div>
    </div>
  </div>
</div>

<div class="row text-center mt-5">
  <div class="col-md-3 col-6 mb-3">
    <a href="/sandya" class="btn btn-outline-teal btn-block py-3 shadow-sm">Prof. Subramanian</a>
  </div>
  <div class="col-md-3 col-6 mb-3">
    <a href="/research" class="btn btn-outline-teal btn-block py-3 shadow-sm">Research</a>
  </div>
  <div class="col-md-3 col-6 mb-3">
    <a href="/publications_page" class="btn btn-outline-teal btn-block py-3 shadow-sm">Publications</a>
  </div>
  <div class="col-md-3 col-6 mb-3">
    <a href="/news" class="btn btn-outline-teal btn-block py-3 shadow-sm">Lab News</a>
  </div>
</div>

<div class="row mt-5 mb-5">
  <div class="col-md-7">
    <h3>Our Values</h3>
    <p>We believe that innovative solutions come from diverse backgrounds working as a team. We are committed to an inclusive environment and high-quality mentorship that empowers trainees to reach their career goals.</p>
  </div>
  <div class="col-md-5 bg-light p-4 shadow-sm" style="border-radius: 12px; border-top: 4px solid #008080;">
    <h4 style="color: #008080;">We are recruiting!</h4>
    <p class="small">Interested in joining our interdisciplinary team?</p>
    <div class="mt-3">
        <a href="https://docs.google.com/document/d/18HSRw8P7dqVkpWCDEW89U1pUrczRmdDNJ0QUJZUHaIk/edit?usp=sharing" class="btn btn-dark btn-sm mr-2">Expectations</a>
        <a href="/join" class="btn btn-teal btn-sm">Join Us</a>
    </div>
  </div>
</div>

<style>
/* CUSTOM TEAL THEME */
.btn-outline-teal { color: #008080; border-color: #008080; background-color: transparent; font-weight: 600; }
.btn-outline-teal:hover {
  background-color: #008080;
  color: white;
  border-color: #008080;
  transform: translateY(-3px);
  transition: all 0.3s ease;
}
.btn-teal { background-color: #008080; color: white; font-weight: 600; }
.btn-teal:hover { background-color: #006666; color: white; }

.jumbotron h2 { font-weight: 700; }
</style>
