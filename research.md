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
        <h4 class="border-bottom pb-2" style="color: #4A5D6E;">1. Clinically Immersive Data Collection & Prototyping</h4>
    </div>
    <div class="col-md-4">
        <img src="/assets/img/wearables.jpg" class="img-fluid rounded mb-2 shadow-sm" alt="wearables">
        <img src="/assets/img/OR_elayne.jpg" class="img-fluid rounded shadow-sm" alt="picture in the OR">
    </div>
    <div class="col-md-8">
        <p>We run human studies with healthy volunteers and patient populations, both in clinical settings and at home. Our goal is to balance clinical-grade data quality with usability and clinician resource constraints.</p>
        
        <div class="row">
            <div class="col-md-6">
                <h6 class="text-teal font-weight-bold text-uppercase small">Previous Studies</h6>
                <ul class="small">
                    <li>Autonomic modulation in healthy volunteers</li>
                    <li>Surgical anesthesia monitoring</li>
                    <li>At-home tracking for chronic migraine</li>
                </ul>
            </div>
            <div class="col-md-6">
                <h6 class="text-teal font-weight-bold text-uppercase small">Ongoing Work</h6>
                <ul class="small">
                    <li>MS bladder muscle tracking wearables</li>
                    <li>V2 Energy-efficient multi-sensor platform</li>
                </ul>
            </div>
        </div>
    </div>
</div>

<div class="row mb-5">
    <div class="col-md-8">
        <h4 class="border-bottom pb-2" style="color: #4A5D6E;">2. Algorithm Development</h4>
        <p>Real-world data is noisy and often lacks "ground truth." We develop <strong>robust, scalable, and automated</strong> algorithms that learn complex patterns without losing physiological integrity.</p>
        
        <div class="bg-light p-3 rounded" style="font-size: 0.9rem;">
            <strong class="d-block mb-2">Key Work:</strong>
            <ul class="list-unstyled mb-0">
                <li class="mb-1">• <strong>Sweat Gland Physiology:</strong> PNAS 2020, PLoS Comp Bio 2021</li>
                <li class="mb-1">• <strong>Artifact Removal:</strong> Operating room EDA automation (Phys Meas 2022)</li>
                <li class="mb-1">• <strong>Neural Point Processes:</strong> Modeling heartbeat dynamics (ICLR 2024)</li>
            </ul>
        </div>
    </div>
    <div class="col-md-4 d-flex align-items-center">
        <div class="p-4 bg-teal text-white rounded shadow-sm w-100 text-center">
            <i class="fas fa-code fa-3x mb-3"></i>
            <h5>Differentiable Algorithms</h5>
        </div>
    </div>
</div>

<div class="row mb-5">
    <div class="col-md-4">
        <img src="/assets/img/ANS_network.jpg" class="img-fluid rounded shadow-sm" alt="ANS network">
    </div>
    <div class="col-md-8">
        <h4 class="border-bottom pb-2" style="color: #4A5D6E;">3. Physiologic Modeling</h4>
        <p>We aim to find creative ways to mathematically model physiology at the organismal level. By embedding <strong>physiological priors</strong> into computational models, we enhance performance even on small, sparse clinical datasets.</p>
        
        <div class="row small mt-3">
            <div class="col-md-6">
                <h6 class="text-teal font-weight-bold text-uppercase x-small">Clinical Applications</h6>
                <ul class="list-unstyled">
                    <li>• General Anesthesia (PLoS ONE 2021)</li>
                    <li>• Gastroparesis (IEEE TBME 2023)</li>
                    <li>• Chronic Pain (IEEE EMBS)</li>
                    <li>• Unconscious Pain Tracking (PNAS)</li>
                </ul>
            </div>
            <div class="col-md-6">
                <h6 class="text-teal font-weight-bold text-uppercase x-small">Future Directions</h6>
                <ul class="list-unstyled">
                    <li>• Multi-system ANS in Long COVID</li>
                    <li>• Chronic Fatigue Syndrome (CFS)</li>
                    <li>• At-home "Autonomic Clinic" pilots</li>
                </ul>
            </div>
        </div>
    </div>
</div>

<style>
.text-teal { color: #008080; }
.bg-teal { background-color: #008080; }
.x-small { font-size: 0.75rem; letter-spacing: 1px; }
.border-rounded { border-radius: 15px; }
li { margin-bottom: 0.5rem; }
</style>
