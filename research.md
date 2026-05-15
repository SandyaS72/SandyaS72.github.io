---
layout: page
title: Research
subtitle: Harnessing AI to understand human physiology
---

The key research questions of the lab are: 

<div class="row text-center my-4">
    <div class="col-md-4">
        <h1 style="color: #008080;"><i class="fas fa-microchip"></i></h1>
        <p>1. How do we **engineer wearable sensor systems** for the real world?</p>
    </div>
    <div class="col-md-4">
        <h1 style="color: #008080;"><i class="fas fa-brain"></i></h1>
        <p>2. What **new machine learning/AI models** should we build to understand signals from the body?</p>
    </div>
    <div class="col-md-4">
        <h1 style="color: #008080;"><i class="fas fa-stethoscope"></i></h1>
        <p>3. Where are the **untapped opportunities in clinical medicine** to better understand individual physiology?</p>
    </div>
</div>

<hr>

### The Problem

<div class="row align-items-center my-4">
    <div class="col-md-7">
        <p>The vast majority of patients spend a relatively small fraction of their total time in a clinic. Most of our time is spent on the rest of life, which includes factors like diet and sleep that play a huge role in our health, but remain mostly out of the purview of the current healthcare system.</p>
        <p>This excludes a lot of valuable information. What about....</p>
        <ul>
            <li>... everything we experience outside of the clinic?</li>
            <li>... situations where patients cannot speak for themselves? </li>
            <li>... functions outside of our conscious awareness and control?</li>
        </ul>
    </div>
    <div class="col-md-5">
        <img src="/assets/img/life_pie_chart.png" class="img-fluid rounded shadow-sm" alt="Life pie chart">
    </div>
</div>

<div class="row align-items-center my-4 flex-md-row-reverse">
    <div class="col-md-7">
        <h4>The Autonomic Nervous System</h4>
        <p>One answer to addressing these challenges is taking advantage of the autonomic nervous system. The autonomic nervous system controls all of our unconscious function (e.g. heartbeats, breathing, digestion, sweating, hormone production, etc.) Advances in wearable sensing over the last decade allow us to track it in ways we could not before. This means it can be monitored:</p>
        <ul>
            <li>outside of the clinic</li>
            <li>even when people are unconscious or incapacitated</li>
            <li>to capture body function beyond conscious control</li>
        </ul>
    </div>
    <div class="col-md-5">
        <img src="/assets/img/ANS_overview.jpg" class="img-fluid rounded shadow-sm" alt="Autonomic nervous system">
    </div>
</div>

<hr class="my-5">

### Our Interdisciplinary Approach

We take a highly interdisciplinary approach to address the main areas of need: new modalities of information, new models and methods, and new applications. Our work falls into three parallel and synergistic lines of inquiry: clinically immersive data collection and system prototyping, algorithm development, and physiologic modeling. 

#### Clinically immersive data collection and system prototyping

<div class="row my-4">
    <div class="col-md-4 mb-3">
        <img src="/assets/img/wearables.jpg" class="img-fluid rounded mb-3 shadow-sm" alt="wearables">
        <img src="/assets/img/OR_elayne.jpg" class="img-fluid rounded shadow-sm" alt="picture in the OR">
    </div>
    <div class="col-md-8">
        <p>We collect our own data by running human studies with healthy volunteers and patient populations, both in clinical settings and at home. Each of these data collection scenarios presents unique challenges that require creative solutions from the hardware standpoint. Our goal is to balance (1) the need for high-quality clinical-grade data with (2) time and resource constraints of busy clinics and clinicians and (3) usability and convenience for the patient. This is an area we hope to expand with more hardware prototyping in the future!</p>
        
        <p><strong>Previous human studies:</strong></p>
        <ul>
            <li>Modulation of autonomic activity in a controlled setting in healthy volunteers</li>
            <li>Monitoring multi-sensor activity in patients undergoing surgery while under anesthesia</li>
            <li>Tracking 24-72 hours of continuous multi-sensor autonomic activity at home in healthy volunteers and patients with chronic migraine</li>
        </ul>

        <p><strong>Current/ongoing work:</strong></p>
        <ul>
            <li>Developing new wearables for the tracking bladder muscle activity at home in multiple sclerosis</li>
            <li>Developing v2 of our full at-home multi-sensor autonomic platform that is energy-efficient and easy to use</li>
        </ul>
    </div>
</div>

#### Algorithm development

<div class="row my-4">
    <div class="col-md-12">
        <p>Collecting data in challenging real-world settings (in and out of the clinic) results in similarly challenging data. These data are noisy, filled with known and unknown artifacts, incomplete, and either lacking ground truth or labeled with annotations that are often inexact or even incorrect due to human error. Algorithm development, especially focused on robust, scalable automation without supervised (labeled datasets) is a major challenge. These methods must learn complex patterns that may be hard to see without losing physiologic integrity of the data (e.g. the point process nature of underlying signals). There are many opportunities to develop neural architectures and differentiable algorithms for biosignals for both single sensor and multimodal data.</p>
        
        <p><strong>Examples of previous work:</strong></p>
        <ul>
            <li>Quantifying the physiology of sweat gland activity from first principles and biophysics (
                <a href="https://doi.org/10.1109/TBME.2021.3071366" target="_blank">IEEE TBME 2021</a>, 
                <a href="https://doi.org/10.1371/journal.pcbi.1009099" target="_blank">PLoS Comp Bio 2021</a>, 
                <a href="https://doi.org/10.1073/pnas.2004403117" target="_blank">PNAS 2020</a>, 
                <a href="https://doi.org/10.1109/EMBC.2019.8857757" target="_blank">Proc IEEE EMBC 2019</a>, 
                <a href="https://doi.org/10.1109/EMBC.2018.8512211" target="_blank">Proc IEEE EMBC 2018</a>)
            </li>
            <li>Automatic artifact removal from electrodermal activity data in the operating room (
                <a href="https://doi.org/10.1088/1361-6579/ac92bd" target="_blank">Phys Meas 2022</a>, 
                <a href="https://doi.org/10.1109/EMBC46164.2021.9630535" target="_blank">Proc IEEE EMBC 2021</a>)
            </li>
            <li>Automated classification of sleep and wake from triaxial accelerometer data (
                <a href="https://doi.org/10.1109/EMBC48229.2022.9871823" target="_blank">Proc IEEE EMBC 2022</a>)
            </li>
            <li>Neural temporal point process methods for modeling heartbeat dynamics (
                <a href="https://openreview.net/pdf?id=CRTVmL4VBv" target="_blank">ICLR TS4H Workshop 2024</a>)
            </li>
        </ul>

        <p><strong>Current/Ongoing work:</strong></p>
        <ul>
            <li>Network models of the ANS across the body</li>
        </ul>
    </div>
</div>

#### Physiologic modeling

<div class="row my-4">
    <div class="col-md-4 mb-3">
        <img src="/assets/img/ANS_network.jpg" class="img-fluid rounded shadow-sm w-100" alt="ANS network">
    </div>
    <div class="col-md-8">
        <p>At the core of all of these exciting new applications is finding new and creative ways to mathematically model what we know of underlying physiology, especially at the macroscale/organismal level. For example, how does the ANS act as a dynamic network across different organ systems? We aim to build physiologically and statistically rigorous models that are also interpretable for scientists and clinicians. One of our interests is embedding rich inductive biases drawn from physiological priors into computational models to enhance their performance even on small datasets.</p>
        
        <p><strong>Examples of previous work:</strong></p>
        <ul>
            <li>Using autonomic responses to monitor general anesthesia (
                <a href="https://doi.org/10.1371/journal.pone.0254053" target="_blank">PLoS ONE 2021</a>, 
                <a href="https://doi.org/10.1109/EMBC48229.2022.9871080" target="_blank">Proc IEEE EMBC 2022</a>, 
                <a href="https://doi.org/10.1109/EMBC44109.2020.9175366" target="_blank">Proc IEEE EMBC 2020</a>, 
                <a href="https://doi.org/10.1109/ESGCO49734.2020.9158139" target="_blank">Proc IEEE ESGCO 2020</a>, 
                <a href="https://doi.org/10.22489/CinC.2020.290" target="_blank">Proc CinC 2020</a>)
            </li>
            <li>Tracking 24-hour autonomic activity at home in different types of gastroparesis (
                <a href="https://doi.org/10.1109/TBME.2023.3285491" target="_blank">IEEE TBME 2023</a>, 
                <a href="https://arinex.com.au/EMBC/pdf/full-paper_709.pdf" target="_blank">Proc IEEE EMBC 2023</a>)
            </li>
            <li>EEG-based patient stratification in chronic pain (
                <a href="https://doi.org/10.1109/IEEECONF58974.2023.10404287" target="_blank">Proc IEEE EMBS Data Sci</a>)
            </li>
            <li>Tracking unconscious pain during surgery (
                <a href="https://www.pnas.org/doi/10.1073/pnas.2319316121" target="_blank">PNAS</a>)
            </li>
        </ul>

        <p><strong>Current/Ongoing work:</strong></p>
        <ul>
            <li>Characterizing multi-system ANS activity in long COVID and chronic fatigue syndrome</li>
            <li>Piloting the at-home autonomic clinic of tomorrow</li>
        </ul>
    </div>
</div>

<style>
h3 { color: #008080 !important; font-weight: 700; }
h4 { color: #4A5D6E !important; font-weight: 600; }
a { color: #008080; font-weight: 600; text-decoration: none; }
a:hover { text-decoration: underline; color: #005353; }
li { margin-bottom: 0.4rem; }
</style>
