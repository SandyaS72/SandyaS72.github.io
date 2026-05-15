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
        <p>We collect our own data by running human studies with healthy volunteers and patient populations, both in clinical settings and at home. Each of these data collection scenarios presents unique challenges that require creative solutions from the hardware standpoint. Our goal is to balance the need for high-quality clinical-grade data with the usability and resource constraints of busy clinics, clinicians, and patients. This is an area we hope to expand with more hardware prototyping in the future!</p>
        
        <div class="row mt-3">
            <div class="col-md-6">
                <h6 class="text-teal font-weight-bold text-uppercase small">Previous Studies</h6>
                <ul class="small">
                    <li>Modulation of autonomic activity in a controlled setting in healthy volunteers</li>
                    <li>Monitoring multi-sensor activity in patients undergoing surgery while under anesthesia</li>
                    <li>Tracking 24-72 hours of continuous multi-sensor autonomic activity at home in healthy volunteers and patients with chronic migraine</li>
                </ul>
            </div>
            <div class="col-md-6">
                <h6 class="text-teal font-weight-bold text-uppercase small">Ongoing Work</h6>
                <ul class="small">
                    <li>Developing new wearables for tracking bladder muscle activity at home in multiple sclerosis</li>
                    <li>Developing v2 of our full at-home multi-sensor autonomic platform that is energy-efficient and easy to use</li>
                </ul>
            </div>
        </div>
    </div>
</div>

<div class="row mb-5">
    <div class="col-md-8">
        <h4 class="border-bottom pb-2" style="color: #4A5D6E;">2. Algorithm Development</h4>
        <p>Collecting data in challenging real-world settings results in similarly challenging data: noisy, incomplete, and filled with artifacts. We focus on developing robust neural architectures and differentiable algorithms for biosignals that automate discovery without relying on heavy supervised labeling—all while maintaining the strict physiologic point-process nature of underlying physiological data.</p>
        
        <div class="bg-light p-3 rounded" style="font-size: 0.9rem;">
            <strong class="d-block mb-2">Key Publications:</strong>
            <ul class="list-unstyled mb-0" style="line-height: 1.6;">
                <li class="mb-2">• <strong>Sweat Gland Biophysics:</strong> Quantifying physiology from first principles (
                    <a href="https://doi.org/10.1109/TBME.2021.3071366" target="_blank">IEEE TBME 2021</a>, 
                    <a href="https://doi.org/10.1371/journal.pcbi.1009099" target="_blank">PLoS Comp Bio 2021</a>, 
                    <a href="https://doi.org/10.1073/pnas.2004403117" target="_blank">PNAS 2020</a>, 
                    <a href="https://doi.org/10.1109/EMBC.2019.8857757" target="_blank">Proc IEEE EMBC 2019</a>, 
                    <a href="https://doi.org/10.1109/EMBC.2018.8512211" target="_blank">Proc IEEE EMBC 2018</a>)
                </li>
                <li class="mb-2">• <strong>Artifact Removal:</strong> Automated electrodermal artifact correction in operating rooms (
                    <a href="https://doi.org/10.1088/1361-6579/ac92bd" target="_blank">Phys Meas 2022</a>, 
                    <a href="https://doi.org/10.1109/EMBC46164.2021.9630535" target="_blank">Proc IEEE EMBC 2021</a>)
                </li>
                <li class="mb-2">• <strong>Activity Tracking:</strong> Classifying sleep and wake states automatically from triaxial accelerometer data (
                    <a href="https://doi.org/10.1109/EMBC48229.2022.9871823" target="_blank">Proc IEEE EMBC 2022</a>)
                </li>
                <li class="mb-1">• <strong>Heartbeat Dynamics:</strong> Neural temporal point process modeling methods for cardiac variance (
                    <a href="https://openreview.net/pdf?id=CRTVmL4VBv" target="_blank">ICLR TS4H Workshop 2024</a>)
                </li>
            </ul>
        </div>
    </div>
    <div class="col-md-4 d-flex align-items-center">
        <div class="p-4 bg-teal text-white rounded shadow-sm w-100 text-center">
            <i class="fas fa-code fa-3x mb-3"></i>
            <h5>Differentiable Algorithms</h5>
            <p class="small mb-0 opacity-75 mt-2">Network models of the ANS across the human body</p>
        </div>
    </div>
</div>

<div class="row mb-5">
    <div class="col-md-4">
        <img src="/assets/img/ANS_network.jpg" class="img-fluid rounded shadow-sm" alt="ANS network">
    </div>
    <div class="col-md-8">
        <h4 class="border-bottom pb-2" style="color: #4A5D6E;">3. Physiologic Modeling</h4>
        <p>At the core of our lab is finding creative ways to mathematically model macroscale physiology. We embed structural inductive biases from physiological priors straight into computational engines. This enhances their accuracy even on sparse datasets, resulting in robust models that remain clinically interpretable.</p>
        
        <div class="bg-light p-3 rounded" style="font-size: 0.9rem;">
            <strong class="d-block mb-2">Key Publications & Milestones:</strong>
            <ul class="list-unstyled mb-0" style="line-height: 1.6;">
                <li class="mb-1">• <strong>General Anesthesia:</strong> Using autonomic responses for patient health tracking (
                    <a href="https://doi.org/10.1371/journal.pone.0254053" target="_blank">PLoS ONE 2021</a>, 
                    <a href="https://doi.org/10.1109/EMBC48229.2022.9871080" target="_blank">Proc IEEE EMBC 2022</a>, 
                    <a href="https://doi.org/10.1109/EMBC44109.2020.9175366" target="_blank">Proc IEEE EMBC 2020</a>, 
                    <a href="https://doi.org/10.1109/ESGCO49734.2020.9158139" target="_blank">Proc IEEE ESGCO 2020</a>, 
                    <a href="https://doi.org/10.22489/CinC.2020.290" target="_blank">Proc CinC 2020</a>)
                </li>
                <li class="mb-1">• <strong>Gastroparesis Subtypes:</strong> Continuous 24-hour ambulatory monitoring profiles (
                    <a href="https://doi.org/10.1109/TBME.2023.3285491" target="_blank">IEEE TBME 2023</a>, 
                    <a href="https://arinex.com.au/EMBC/pdf/full-paper_709.pdf" target="_blank">Proc IEEE EMBC 2023</a>)
                </li>
                <li class="mb-1">• <strong>Chronic Pain Stratification:</strong> EEG data-driven patient clustering profiles (
                    <a href="https://doi.org/10.1109/IEEECONF58974.2023.10404287" target="_blank">Proc IEEE EMBS Data Sci</a>)
                </li>
                <li class="mb-1">• <strong>Surgical Nociception:</strong> 7-year study tracking unconscious pain signatures under anesthesia (
                    <a href="https://www.pnas.org/doi/10.1073/pnas.2319316121" target="_blank">PNAS 2024</a>)
                </li>
            </ul>
        </div>

        <div class="mt-3 p-2 border-left" style="border-left: 3px solid #008080 !important;">
            <span class="font-weight-bold text-teal small text-uppercase d-block mb-1">Current & Future Horizons:</span>
            <p class="small text-muted mb-0">Characterizing multi-system ANS activity profiles in long COVID / Chronic Fatigue Syndrome (CFS), and prototyping the at-home autonomic clinic of tomorrow.</p>
        </div>
    </div>
</div>

<style>
.text-teal { color: #008080; }
.bg-teal { background-color: #008080; }
.border-rounded { border-radius: 15px; }
li { margin-bottom: 0.3rem; }
.opacity-75 { opacity: 0.75; }
.bg-light a { color: #008080; font-weight: 600; text-decoration: none; }
.bg-light a:hover { text-decoration: underline; color: #005353; }
</style>
