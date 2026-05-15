---
layout: page
title: Research
subtitle: Harnessing AI to understand human physiology
---

<div class="row mb-5">
    <div class="col-md-12">
        <div class="p-4 bg-light border-rounded shadow-sm" style="border-radius: 15px; border-top: 5px solid #008080;">
            <h3 class="text-dark mb-4">The key research questions of the lab:</h3>
            <div class="row text-center">
                <div class="col-md-4">
                    <h1 style="color: #008080;"><i class="fas fa-microchip"></i></h1>
                    <p class="small font-weight-bold">How do we engineer wearable sensor systems for the real world?</p>
                </div>
                <div class="col-md-4">
                    <h1 style="color: #008080;"><i class="fas fa-brain"></i></h1>
                    <p class="small font-weight-bold">What new ML/AI models should we build to understand body signals?</p>
                </div>
                <div class="col-md-4">
                    <h1 style="color: #008080;"><i class="fas fa-stethoscope"></i></h1>
                    <p class="small font-weight-bold">Where are the untapped clinical opportunities to understand physiology?</p>
                </div>
            </div>
        </div>
    </div>
</div>

<hr class="my-5">

<div class="row align-items-center mb-5">
    <div class="col-md-7">
        <h2 style="color: #008080;">The Problem</h2>
        <p class="lead">Valuable health information is being lost in the gaps of our current system.</p>
        <p>The vast majority of patients spend a relatively small fraction of their total time in a clinic. Life happens elsewhere—in diet, sleep, and daily stress. Currently, this remains largely out of the purview of healthcare.</p>
        <div class="p-3 mb-2 bg-white border rounded">
            <h5 class="small font-weight-bold text-uppercase">What about...</h5>
            <ul class="mb-0">
                <li>Everything experienced <strong>outside</strong> the clinic?</li>
                <li>Situations where patients <strong>cannot speak</strong> for themselves?</li>
                <li>Functions <strong>outside</strong> of our conscious awareness and control?</li>
            </ul>
        </div>
    </div>
    <div class="col-md-5">
        <img src="/assets/img/life_pie_chart.png" class="img-fluid rounded shadow-sm" alt="Life pie chart">
    </div>
</div>

<div class="row align-items-center mb-5 flex-md-row-reverse">
    <div class="col-md-7">
        <h3 style="color: #008080;">The Autonomic Nervous System</h3>
        <p>The ANS controls all of our <strong>unconscious functions</strong> (heartbeats, digestion, sweating, etc.). Advances in wearable sensing now allow us to track these signals in ways we never could before.</p>
        <p>By monitoring the ANS, we can capture body function:</p>
        <ul>
            <li>Outside of the clinic during daily life</li>
            <li>Even when patients are unconscious or incapacitated</li>
            <li>Beyond a patient's conscious control</li>
        </ul>
    </div>
    <div class="col-md-5">
        <img src="/assets/img/ANS_overview.jpg" class="img-fluid rounded shadow-sm" alt="Autonomic nervous system">
    </div>
</div>

<hr class="my-5">

<div class="text-center mb-5">
    <h2 style="color: #008080;">Our Interdisciplinary Approach</h2>
    <p class="lead text-muted">A synergistic cycle of prototyping, modeling, and algorithm development.</p>
</div>

<div class="row mb-5">
    <div class="col-md-12">
        <h3 class="section-heading mb-4">1. Clinically Immersive Data Collection & Prototyping</h3>
    </div>
    <div class="col-md-4 mb-4">
        <img src="/assets/img/wearables.jpg" class="img-fluid rounded mb-3 shadow-sm w-100" alt="wearables">
        <img src="/assets/img/OR_elayne.jpg" class="img-fluid rounded shadow-sm w-100" alt="picture in the OR">
    </div>
    <div class="col-md-8">
        <p class="lead-text">We collect our own data by running human studies with healthy volunteers and patient populations, both in clinical settings and at home. Our goal is to balance high-quality clinical data with the real-world usability constraints of busy clinics, clinicians, and patients.</p>
        
        <div class="project-card ongoing-card mb-4">
            <span class="status-badge badge-ongoing">Current & Ongoing Focus</span>
            <ul class="mt-3 mb-0 project-text-main">
                <li>Developing new target wearables to track bladder muscle activity at home for Multiple Sclerosis (MS) monitoring.</li>
                <li>Engineering V2 of our full at-home, multi-sensor autonomic platform for high energy efficiency and ease of use.</li>
            </ul>
        </div>

        <div class="project-card historical-card">
            <span class="status-badge badge-past">Established Human Studies</span>
            <ul class="mt-3 mb-0 project-text-main">
                <li>Modulation of autonomic activity in tightly controlled environments with healthy volunteers.</li>
                <li>Multi-sensor baseline tracking for patients undergoing major surgery under general anesthesia.</li>
                <li>Continuous 24-72 hour multi-sensor autonomic mapping at home for chronic migraine cohorts.</li>
            </ul>
        </div>
    </div>
</div>

<div class="row mb-5">
    <div class="col-md-12">
        <h3 class="section-heading mb-4">2. Algorithm Development</h3>
    </div>
    <div class="col-md-8">
        <p class="lead-text">Real-world physiological data is messy: highly noisy, full of physical movement artifacts, and typically unlabeled. We develop robust neural architectures and unsupervised, differentiable biosignal algorithms that can automatically map out patterns without stripping away basic physiological integrity.</p>
        
        <div class="project-card pipeline-card mb-4">
            <span class="status-badge badge-ongoing">Active Methodological Focus</span>
            <p class="mt-3 mb-0 project-text-main">
                Developing dynamic structural network models tracking cross-body ANS output dynamics simultaneously.
            </p>
        </div>

        <div class="bg-white p-4 border rounded shadow-sm">
            <h5 class="text-teal font-weight-bold mb-3"><i class="fas fa-book-open"></i> Core Algorithmic Frameworks & Papers</h5>
            <ul class="list-unstyled mb-0" style="line-height: 1.8; font-size: 1.05rem;">
                <li class="mb-3"><strong>Sweat Gland Biophysics:</strong> Ground-up physiological quantization (
                    <a href="https://doi.org/10.1109/TBME.2021.3071366" target="_blank">IEEE TBME 2021</a>, 
                    <a href="https://doi.org/10.1371/journal.pcbi.1009099" target="_blank">PLoS Comp Bio 2021</a>, 
                    <a href="https://doi.org/10.1073/pnas.2004403117" target="_blank">PNAS 2020</a>, 
                    <a href="https://doi.org/10.1109/EMBC.2019.8857757" target="_blank">Proc IEEE EMBC 2019</a>)
                </li>
                <li class="mb-3"><strong>Artifact Mitigation:</strong> Automated real-time EDA correction arrays inside clinical ORs (
                    <a href="https://doi.org/10.1088/1361-6579/ac92bd" target="_blank">Phys Meas 2022</a>, 
                    <a href="https://doi.org/10.1109/EMBC46164.2021.9630535" target="_blank">Proc IEEE EMBC 2021</a>)
                </li>
                <li class="mb-3"><strong>State Classification:</strong> Parsing clean sleep vs. wake metrics from raw accelerometer dynamics (
                    <a href="https://doi.org/10.1109/EMBC48229.2022.9871823" target="_blank">Proc IEEE EMBC 2022</a>)
                </li>
                <li class="mb-0"><strong>Heartbeat Stochastics:</strong> Neural temporal point process mapping frameworks (
                    <a href="https://openreview.net/pdf?id=CRTVmL4VBv" target="_blank">ICLR TS4H 2024</a>)
                </li>
            </ul>
        </div>
    </div>
    <div class="col-md-4 d-flex align-items-stretch">
        <div class="p-4 bg-teal text-white rounded shadow-sm w-100 d-flex flex-column justify-content-center text-center">
            <i class="fas fa-network-wired fa-3x mb-3"></i>
            <h5>Differentiable Architectures</h5>
            <p class="small mb-0 opacity-75 mt-2">Embedding system biophysics cleanly inside ML loss-functions.</p>
        </div>
    </div>
</div>

<div class="row mb-5">
    <div class="col-md-12">
        <h3 class="section-heading mb-4">3. Physiologic Modeling</h3>
    </div>
    <div class="col-md-4 mb-3">
        <img src="/assets/img/ANS_network.jpg" class="img-fluid rounded shadow-sm w-100" alt="ANS network">
    </div>
    <div class="col-md-8">
        <p class="lead-text">Computational models scale beautifully when they understand structural limits. We build physiologically and statistically rigorous models by embedding macroscale organ priors as mathematical inductive biases, achieving high validation stability even on sparse data fields.</p>

        <div class="project-card future-card mb-4">
            <span class="status-badge badge-future">Future Horizons & Clinical Vision</span>
            <ul class="mt-3 mb-0 project-text-main" style="color: #003333;">
                <li>Deep multi-system ANS profiling across complex syndromic cohorts, including Long COVID and Chronic Fatigue Syndrome (CFS).</li>
                <li>Prototyping and piloting validation infrastructure for the distributed "At-Home Autonomic Clinic of Tomorrow."</li>
            </ul>
        </div>

        <div class="bg-white p-4 border rounded shadow-sm">
            <h5 class="text-teal font-weight-bold mb-3"><i class="fas fa-heartbeat"></i> Clinical Translation References</h5>
            <ul class="list-unstyled mb-0" style="line-height: 1.8; font-size: 1.05rem;">
                <li class="mb-3"><strong>General Anesthesia:</strong> Mapping deep autonomic responses directly to depth states (
                    <a href="https://doi.org/10.1371/journal.pone.0254053" target="_blank">PLoS ONE 2021</a>, 
                    <a href="https://doi.org/10.1109/EMBC48229.2022.9871080" target="_blank">Proc IEEE EMBC 2022</a>)
                </li>
                <li class="mb-3"><strong>Gastroparesis Variances:</strong> Tracking ambulatory variance across specific functional subtypes (
                    <a href="https://doi.org/10.1109/TBME.2023.3285491" target="_blank">IEEE TBME 2023</a>)
                </li>
                <li class="mb-3"><strong>Pain Stratification:</strong> Sorting chronic clinical pain markers via EEG data clustering models (
                    <a href="https://doi.org/10.1109/IEEECONF58974.2023.10404287" target="_blank">Proc IEEE EMBS</a>)
                </li>
                <li class="mb-0"><strong>Surgical Nociception:</strong> Mapping multi-hour unconscious surgical pain trajectories (
                    <a href="https://www.pnas.org/doi/10.1073/pnas.2319316121" target="_blank">PNAS 2024</a>)
                </li>
            </ul>
        </div>
    </div>
</div>

<style>
/* TEXT TYPOGRAPHY */
.text-teal { color: #008080; }
.bg-teal { background-color: #008080; }
.border-rounded { border-radius: 15px; }
.section-heading { color: #4A5D6E; border-bottom: 2px solid #e0eeee; padding-bottom: 8px; font-weight: 700; }
.lead-text { font-size: 1.1rem; line-height: 1.6; color: #222; margin-bottom: 1.5rem; }

/* ENHANCED CORE TEXT SIZE FOR LAB FOCUS BLOCKS */
.project-text-main { font-size: 1.1rem; line-height: 1.6; color: #111111; font-weight: 500; }

/* PROJECT CARDS */
.project-card { position: relative; padding: 22px 24px 18px 24px; border-radius: 8px; border-left: 6px solid #ccc; margin-top: 15px; shadow: 0 4px 6px rgba(0,0,0,0.02); }
.ongoing-card { background-color: #f2fafa; border-left-color: #008080; }
.pipeline-card { background-color: #f2fafa; border-left-color: #008080; }
.historical-card { background-color: #f8fafc; border-left-color: #64748b; }
.future-card { background-color: #f0fdfa; border-left-color: #0d9488; }

/* STATUS BADGES */
.status-badge { font-size: 0.8rem; font-weight: 700; text-transform: uppercase; letter-spacing: 1px; padding: 5px 12px; border-radius: 4px; display: inline-block; }
.badge-ongoing { background-color: #008080; color: white; }
.badge-past { background-color: #64748b; color: white; }
.badge-future { background-color: #0d9488; color: white; }

/* LINK BEHAVIOR */
.bg-white a { color: #008080; font-weight: 600; text-decoration: none; }
.bg-white a:hover { text-decoration: underline; color: #005353; }
.opacity-75 { opacity: 0.75; }
ul li { margin-bottom: 0.6rem; }
</style>
