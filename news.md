---
layout: page
title: News
subtitle: Recent lab happenings
ticker_items:
  - "Welcome to our new graduate students: Vi, Josh, and Shruthi!"
  - "Sandya’s final PhD work on tracking surgical pain is published in PNAS!"
  - "SANDLab presents three papers and an abstract at IEEE EMBC 2025 in Copenhagen!"

# ==============================================================================
# LAB NEWS DATABASE
# Simply add new items at the top of this list.
# 
# Format Options for items:
#   - year: "YYYY" (Only add this line on the newest event of a fresh year)
#   - date: "Month YYYY"
#   - bullets: 
#       - text: "Standard bullet string"
#       - text: "Bullet text with its own picture"
#         bullet_img: "/assets/img/picture.jpg"
#   - images: ["url1.jpg", "url2.jpg"] -> Top multi-photo grid row (1-5 images)
#   - video: "YOUTUBE_VIDEO_ID"
#   - inline_img: "sidebar_image.jpg" -> Side picture format for the whole item
# ==============================================================================
news_items:
  - year: "2026"
    date: "May 2026"
    bullets:
      - text: "<strong>New Lab Members:</strong> We are thrilled to have Vi Nguyen, Josh Everts, and Shruthi Ravichandran join the SANDLab team for their PhDs!"

  - year: "2025"
    date: "Jul 2025"
    images:
      - "/assets/img/EMBC_copenhagen_1.jpg"
      - "/assets/img/EMBC_copenhagen_2.jpg"
      - "/assets/img/EMBC_copenhagen_3.jpg"
      - "/assets/img/EMBC_copenhagen_4.jpg"
      - "/assets/img/EMBC_copenhagen_5.jpg"
    bullets:
      - text: "<strong>Conference:</strong> SANDLab's first international conference! We presented three papers and an abstract at the IEEE Annual Conference on Engineering Medicine and Biology (EMBC) in Copenhagen!"

  - date: "Jun 2025"
    bullets:
      - text: "<strong>New Lab Members:</strong> Welcoming our new CITRIS summer intern, Bhuvana!"

  - date: "May 2025"
    bullets:
      - text: "<strong>Invited Talk:</strong> Sandya gave a guest lecture at the 2025 IEEE-EMBS International Summer School on Advanced Data Analytics in Physiology in Pisa!"
      - text: "<strong>Invited Talk:</strong> Sandya was invited to present at the Women in Data Science Worldwide event organized by Stanford @ Lane Medical Library!"
      - text: "<strong>Award:</strong> Sandya won the Rose Hills Innovators Award to develop the at-home autonomic clinic of tomorrow!"
      - text: "<strong>Lab Farewell:</strong> Bye Reuben! We'll miss you!"

  - date: "Apr 2025"
    images:
      - "/assets/img/frontiers_cph_1.jpg"
      - "/assets/img/frontiers_cph_2.jpg"
      - "/assets/img/frontiers_cph_3.jpg"
    bullets:
      - text: "<strong>Invited Talk:</strong> Sandya was invited to give a talk at the UC Berkeley Comp Bio Graduate Seminar!"
      - text: "<strong>Conference:</strong> SANDLab had a strong showing at the Frontiers of CPH Conference at UC Berkeley, with three posters from lab members and Sandya on a panel!"
      - text: "<strong>Lab event:</strong> Lab hot pot dinner!"
        bullet_img: "/assets/img/labdinner_apr2025.jpg"

  - date: "Jan 2025"
    bullets:
      - text: "<strong>New Lab Members:</strong> Welcome to SANDLab Reuben!"

  - year: "2024"
    date: "Nov 2024"
    bullets:
      - text: "<strong>New Lab Members:</strong> Welcome to SANDLab Jeshu!"
      - text: "<strong>Conference:</strong> Sandya presented her work on unconscious pain during surgery at AMIA in SF!"

  - date: "Oct 2024"
    bullets:
      - text: "<strong>New Lab Members:</strong> Welcome to SANDLab Belinda and Ruhi!"
      - text: "<strong>Invited Talk:</strong> Sandya was invited to share her work on unconscious pain during surgery at a meeting of the MGH/MIT BASCIC Center!"

  - date: "Sep 2024"
    bullets:
      - text: "<strong>New Lab Members:</strong> Welcome Sriram, Sajiv, Abhi, Hannah, and Wei as the first students in SANDLab!"
      - text: "<strong>Publication:</strong> <strong>Tracking unconscious pain during surgery published in PNAS!</strong> Sandya’s final PhD work, involving over 500 hours in the OR, is now out in <a href='https://www.pnas.org/doi/10.1073/pnas.2319316121' target='_blank'>PNAS</a>."
      - text: "<strong>Invited Talk:</strong> Sandya was invited to give a talk at the UC Berkeley Biostat Graduate Seminar!"

  - date: "Jul 2024"
    bullets:
      - text: "<strong>SANDLab is officially here!</strong> We are excited to launch our interdisciplinary research environment at UC Berkeley and UCSF. <a href='https://cdss.berkeley.edu/news/cdss-welcomes-seven-faculty-celebrates-two-new-college-chairs' target='_blank'>Coverage here</a>."

  - date: "Feb 2024"
    inline_img: "/assets/img/Schmidt_THE_piece.png"
    bullets:
      - text: "<strong>Inside the data-driven search for migraine relief:</strong> Sandya sat down with <em>Times Higher Education</em> to talk about interdisciplinary science. <a href='https://www.timeshighereducation.com/campus/inside-datadriven-search-migraine-relief' target='_blank'>Link to article</a>."

  - year: "2023"
    date: "Dec 2023"
    inline_img: "/assets/img/TBME_featured_thumbnail.jpg"
    bullets:
      - text: "<strong>IEEE TBME Featured Article:</strong> Our paper on 24-hour monitoring of patients with gastroparesis was selected as a <a href='https://www.embs.org/tbme/articles/exploring-the-gut-brain-connection-in-gastroparesis-with-autonomic-and-gastric-myoelectric-monitoring/' target='_blank'>Featured Article</a>!"

  - date: "Oct 2023"
    video: "XAV4WkQviOM"
    bullets:
      - text: "<strong>Graduate Diversity Fair:</strong> Sandya presents for CPH at the 2023 UC Berkeley Graduate Diversity Fair (starting at 39:15)."

  - year: "2022"
    date: "Nov 2022"
    video: "KnHq8WW9BoE"
    bullets:
      - text: "<strong>L'Oreal For Women in Science Fellowship:</strong> Sandya wins the prestigious L'Oreal For Women in Science Fellowship!"

  - date: "Jun 2022"
    video: "0xt02t6esig"
    bullets:
      - text: "<strong>Schmidt Science Fellow:</strong> Sandya is named a 2022 Schmidt Science Fellow!"
---

<div class="timeline-container">

  {% for item in page.news_items %}
    
    {% if item.year %}
      <div class="timeline-header">
        <h4>{{ item.year }}</h4>
      </div>
    {% endif %}

    <div class="timeline-item">
      <div class="timeline-marker"></div>
      <div class="timeline-content">
        <span class="news-date">{{ item.date }}</span>
        
        {% if item.images %}
          {% assign img_count = item.images | size %}
          
          {% if img_count == 5 %}
            <div class="row no-gutters mx-n1 mb-3">
              <div class="col-md-6 px-1 mb-2 mb-md-0">
                <img src="{{ item.images[0] }}" class="img-fluid rounded shadow-sm w-100 grid-photo-hero">
              </div>
              <div class="col-md-6 px-1">
                <div class="row no-gutters mx-n1 mb-2">
                  <div class="col-6 px-1"><img src="{{ item.images[1] }}" class="img-fluid rounded shadow-sm w-100 grid-photo-quad"></div>
                  <div class="col-6 px-1"><img src="{{ item.images[2] }}" class="img-fluid rounded shadow-sm w-100 grid-photo-quad"></div>
                </div>
                <div class="row no-gutters mx-n1">
                  <div class="col-6 px-1"><img src="{{ item.images[3] }}" class="img-fluid rounded shadow-sm w-100 grid-photo-quad"></div>
                  <div class="col-6 px-1"><img src="{{ item.images[4] }}" class="img-fluid rounded shadow-sm w-100 grid-photo-quad"></div>
                </div>
              </div>
            </div>

          {% elsif img_count == 3 or img_count == 4 %}
            <div class="row no-gutters mx-n1 mb-3">
              {% for img in item.images %}
                <div class="col-{{ 12 | divided_by: img_count }} px-1">
                  <img src="{{ img }}" class="img-fluid rounded shadow-sm w-100 grid-photo-quad">
                </div>
              {% endfor %}
            </div>

          {% else %}
            <div class="mb-3">
              <img src="{{ item.images[0] }}" class="img-fluid rounded shadow-sm" style="max-height: 300px; object-fit: cover;">
            </div>
          {% endif %}
        {% endif %}

        {% if item.inline_img %}
          <div class="row align-items-start">
            <div class="col-md-3 text-center mb-3 mb-md-0">
              <img src="{{ item.inline_img }}" class="img-fluid rounded shadow-sm w-100 inline-photo">
            </div>
            <div class="col-md-9">
              {% if item.bullets %}
                <ul class="news-bullet-list">
                  {% for bullet in item.bullets %}
                    <li>
                      <div>{{ bullet.text }}</div>
                      {% if bullet.bullet_img %}
                        <img src="{{ bullet.bullet_img }}" class="img-fluid rounded shadow-sm mt-2 mb-1 d-block target-bullet-photo">
                      {% endif %}
                    </li>
                  {% endfor %}
                </ul>
              {% endif %}
            </div>
          </div>

        {% else %}
          {% if item.bullets %}
            <ul class="news-bullet-list">
              {% for bullet in item.bullets %}
                <li>
                  <div>{{ bullet.text }}</div>
                  {% if bullet.bullet_img %}
                    <img src="{{ bullet.bullet_img }}" class="img-fluid rounded shadow-sm mt-2 mb-1 d-block target-bullet-photo">
                  {% endif %}
                </li>
              {% endfor %}
            </ul>
          {% endif %}
        {% endif %}

        {% if item.video %}
          <div class="embed-responsive embed-responsive-16by9 mt-3 video-frame shadow-sm">
            <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/{{ item.video }}" allowfullscreen></iframe>
          </div>
        {% endif %}

      </div>
    </div>
  {% endfor %}

</div>

<style>
  .timeline-container { position: relative; padding-left: 25px; margin-top: 2rem; }
  .timeline-container::before { content: ''; position: absolute; top: 10px; bottom: 30px; left: 4px; width: 3px; background: #e0eeee; }
  .timeline-header { position: relative; margin-top: 3rem; margin-bottom: 1.5rem; left: -25px; }
  .timeline-header h4 { d-block; display: inline-block; background: #008080; color: #ffffff !important; font-size: 1.5rem; font-weight: 700; padding: 6px 20px; border-radius: 4px; margin: 0; box-shadow: 0 2px 4px rgba(0,0,0,0.05); }
  .timeline-item { position: relative; margin-bottom: 2rem; }
  .timeline-marker { position: absolute; top: 6px; left: -25px; width: 11px; height: 11px; border-radius: 50%; background: #008080; border: 2px solid #ffffff; box-shadow: 0 0 0 3px #e0eeee; transition: background 0.2s ease; }
  .timeline-item:hover .timeline-marker { background: #4A5D6E; }
  .timeline-content { padding: 20px; background-color: #ffffff; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.04); }
  .news-date { display: inline-block; font-size: 1.15rem; font-weight: 700; color: #008080; letter-spacing: 0.3px; margin-bottom: 8px; }
  .news-bullet-list { padding-left: 18px; margin-bottom: 0; font-size: 1.05rem; color: #222222 !important; }
  .news-bullet-list li { margin-bottom: 0.8rem; line-height: 1.55; }
  .news-bullet-list li:last-child { margin-bottom: 0; }
  .video-frame { border-radius: 8px; overflow: hidden; }
  .inline-photo { max-height: 140px; object-fit: contain; }
  .target-bullet-photo { max-height: 180px; width: auto; object-fit: cover; }
  .grid-photo-hero { height: 278px; object-fit: cover; object-position: center; }
  .grid-photo-quad { height: 135px; object-fit: cover; object-position: center; }
  @media (max-width: 768px) {
    .grid-photo-hero { height: 200px; }
    .grid-photo-quad { height: 95px; }
  }
  .timeline-content a { color: #008080; font-weight: 600; text-decoration: none; }
  .timeline-content a:hover { text-decoration: underline; color: #4A5D6E; }
</style>
