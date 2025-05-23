---
layout: page
title: Research
subtitle: Making valuable information from the human body accessible to healthcare
---

The key research questions of the lab are: 

1. How do we **engineer wearable sensor systems** for the real world?
2. What **new machine learning/AI models** should we build to understand signals from the body?
3. Where are the **untapped opportunities in clinical medicine** to better understand individual physiology?

### The Problem

<img src="/assets/img/life_pie_chart.png"
 style="float: right; margin-left: 1em;"
srcset="/assets/img/life_pie_chart.png 2098w"
sizes="(min-width: 1501px) calc(23vw - 20px), ((min-width: 1101px) and (max-width: 1500px)) calc(33vw - 20px), ((min-width: 651px) and (max-width: 1100px)) calc(65vw - 20px), ((min-width: 300px) and (max-width: 650px)) calc(80vw - 20px), 150px"
alt="Life pie chart">

The vast majority of patients spend a relatively small fraction of their total time in a clinic. Most of our time is spent on the rest of life, which includes factors like diet and sleep that play a huge role in our health, but remain mostly out of the purview of the current healthcare system.

This excludes a lot of valuable information. What about....
- ... everything we experience outside of the clinic?
- ... situations where patients cannot speak for themselves? 
- ... functions outside of our conscious awareness and control?

<img src="/assets/img/ANS_overview.jpg"
style="float: right; margin-left: 2em;"
srcset="/assets/img/ANS_overview.jpg 1083w"
sizes="(min-width: 1501px) calc(10vw - 20px), ((min-width: 1101px) and (max-width: 1500px)) calc(20vw - 20px), ((min-width: 651px) and (max-width: 1100px)) calc(30vw - 20px), ((min-width: 300px) and (max-width: 650px)) calc(45vw - 20px), 150px"
alt="Autonomic nervous system">

#### The Autonomic Nervous System 

One answer to addressing these challenges is taking advantage of the autonomic nervous system. The autonomic nervous system controls all of our unconscious function (e.g. heartbeats, breathing, digestion, sweating, hormone production, etc.) Advances in wearable sensing over the last decade allow us to track it in ways we could not before. This means it can be monitored:
- outside of the clinic
- even when people are unconscious or incapacitated
- to capture body function beyond conscious control

### Our Interdisciplinary Approach

We take a highly interdisciplinary approach to address the main areas of need: new modalities of information, new models and methods, and new applications. Our work falls into three parallel and synergistic lines of inquiry: clinically immersive data collection and system prototyping, algorithm development, and physiologic modeling. 

#### Clinically immersive data collection and system prototyping
<img src="/assets/img/wearables.jpg"
style="float: right; margin-left: 1em;"
srcset="/assets/img/wearables.jpg 970w"
sizes="(min-width: 1501px) calc(7vw - 20px), ((min-width: 1101px) and (max-width: 1500px)) calc(11vw - 20px), ((min-width: 651px) and (max-width: 1100px)) calc(30vw - 20px), ((min-width: 300px) and (max-width: 650px)) calc(37vw - 20px), 150px"
alt="wearables">

<img src="/assets/img/OR_elayne.jpg"
style="float: left; margin-right: 1em;"
srcset="/assets/img/OR_elayne.jpg 1512w"
sizes="(min-width: 1501px) calc(10vw - 20px), ((min-width: 1101px) and (max-width: 1500px)) calc(15vw - 20px), ((min-width: 651px) and (max-width: 1100px)) calc(30vw - 20px), ((min-width: 300px) and (max-width: 650px)) calc(40vw - 20px), 150px"
alt="picture in the OR">

We collect our own data by running human studies with healthy volunteers and patient populations, both in clinical settings and at home. Each of these data collection scenarios presents unique challenges that require creative solutions from the hardware standpoint. Our goal is to balance (1) the need for high-quality clinical-grade data with (2) time and resource constraints of busy clinics and clinicians and (3) usability and convenience for the patient. This is an area we hope to expand with more hardware prototyping in the future!  

**Previous human studies:**
- Modulation of autonomic activity in a controlled setting in healthy volunteers
- Monitoring multi-sensor activity in patients undergoing surgery while under anesthesia
- Tracking 24-72 hours of continuous multi-sensor autonomic activity at home in healthy volunteers and patients with chronic migraine

**Current/ongoing work:**
- Developing new wearables for the tracking bladder muscle activity at home in multiple sclerosis
- Developing v2 of our full at-home multi-sensor autonomic platform that is energy-efficient and easy to use

#### Algorithm development

Collecting data in challenging real-world settings (in and out of the clinic) results in similarly challenging data. These data are noisy, filled with known and unknown artifacts, incomplete, and either lacking ground truth or labeled with annotations that are often inexact or even incorrect due to human error. Algorithm development, especially focused on robust, scalable automation without supervised (labeled datasets) is a major challenge. These methods must learn complex patterns that may be hard to see without losing physiologic integrity of the data (e.g. the point process nature of underlying signals). There are many opportunities to develop neural architectures and differentiable algorithms for biosignals for both single sensor and multimodal data.

**Examples of previous work:**
- Quantifying the physiology of sweat gland activity from first principles and biophysics ([IEEE TBME 2021](https://doi.org/10.1109/TBME.2021.3071366), [PLoS Comp Bio 2021](https://doi.org/10.1371/journal.pcbi.1009099), [PNAS 2020](https://doi.org/10.1073/pnas.2004403117), [Proc IEEE EMBC 2019](https://doi.org/10.1109/EMBC.2019.8857757), [Proc IEEE EMBC 2018](https://doi.org/10.1109/EMBC.2018.8512211))
- Automatic artifact removal from electrodermal activity data in the operating room ([Phys Meas 2022](https://doi.org/10.1088/1361-6579/ac92bd), [Proc IEEE EMBC 2021](https://doi.org/10.1109/EMBC46164.2021.9630535))
- Automated classification of sleep and wake from triaxial accelerometer data ([Proc IEEE EMBC 2022](https://doi.org/10.1109/EMBC48229.2022.9871823))
- Neural temporal point process methods for modeling heartbeat dynamics ([ICLR TS4H Workshop 2024](https://openreview.net/pdf?id=CRTVmL4VBv))

**Current/Ongoing work:**
- Network models of the ANS across the body

#### Physiologic modeling

<img src="/assets/img/ANS_network.jpg"
style="float: left; margin-right: 1em;"
srcset="/assets/img/ANS_network.jpg 502w"
sizes="(min-width: 1501px) calc(9vw - 20px), ((min-width: 1101px) and (max-width: 1500px)) calc(21vw - 20px), ((min-width: 651px) and (max-width: 1100px)) calc(36vw - 20px), ((min-width: 300px) and (max-width: 650px)) calc(46vw - 20px), 150px"
alt="ANS network">

At the core of all of these exciting new applications is finding new and creative ways to mathematically model what we know of underlying physiology, especially at the macroscale/organismal level. For example, how does the ANS act as a dynamic network across different organ systems? We aim to build physiologically and statistically rigorous models that are also interpretable for scientists and clinicians. One of our interests is embedding rich inductive biases drawn from physiological priors into computational models to enhance their performance even on small datasets.
 
**Examples of previous work:**
- Using autonomic responses to monitor general anesthesia ([PLoS ONE 2021](https://doi.org/10.1371/journal.pone.0254053), [Proc IEEE EMBC 2022](https://doi.org/10.1109/EMBC48229.2022.9871080), [Proc IEEE EMBC 2020](https://doi.org/10.1109/EMBC44109.2020.9175366), [Proc IEEE ESGCO 2020](https://doi.org/10.1109/ESGCO49734.2020.9158139), [Proc CinC 2020](https://doi.org/10.22489/CinC.2020.290))
- Tracking 24-hour autonomic activity at home in different types of gastroparesis ([IEEE TBME 2023](https://doi.org/10.1109/TBME.2023.3285491), [Proc IEEE EMBC 2023](https://arinex.com.au/EMBC/pdf/full-paper_709.pdf))
- EEG-based patient stratification in chronic pain ([Proc IEEE EMBS Data Sci](https://doi.org/10.1109/IEEECONF58974.2023.10404287))
- Tracking unconscious pain during surgery ([PNAS](https://www.pnas.org/doi/10.1073/pnas.2319316121))

**Current/Ongoing work:**
- Characterizing multi-system ANS activity in long COVID and chronic fatigue syndrome
- Piloting the at-home autonomic clinic of tomorrow

