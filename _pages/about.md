---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome to Min's reality! I am a senior software engineer at Google, serving as ARCore tech lead. I also spend 20% time at Google Deepmind Robot team.

I am interested in technical Human-computer interaction and robot learning from diverse sources and multimodal datasets. 

Previously, I completed my M.S. in electrical and computer engineering at Cornell University and my B.S. in electronic science and engineering at Southeast University, China. See my research, projects, youtube, talks and demos for fun! 

<br>

# Research Projects

## Video to Rewards for Robotic Skill Synthesis
<video class="video" playsinline="" muted="" autoplay="" loop=""><source src="assets/video/RewardsForRoboticSkillSynthesis.mov" type="video/mp4"></video>
Our goal is to enable Intuitive robot skill creation through AR and Human Demonstration. Users provide a video demonstration and our system generates the reward functions through large language models (LLMs) to control low level robot actions.
Traditional robot programming is tedious and requires expert knowledge. Defining complex behaviors through low-level commands is time-consuming and inaccessible to non-experts.
We envision a future where anyone can easily teach robots new skills. Imagine instructing a robot simply by showing it what to do, much like we teach each other.
Project completed, in progress of writing paper.

## AI Glasses
<iframe class="ai-glass iframe-video" width="780" height="439" src="https://www.youtube.com/embed/OVbce5iGSQI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe>
<div class="ai-glass-metadata">Glasses appear at 3:00</div>
Our aim was to generate responses based on users' queries and images captured by glasses. I proposed a novel composed retrieval model, LLMs generating responses based on CLIP detected objects, business info from Google Lens, and user query.  As the system evolves, we need a way to benchmark the performance. I defined five innovative rating categories: factuality, readiness, offensiveness, informativeness and responsiveness, and designed the prompts to evaluate the response in each category automatically. The evaluation results correlated highly with human labels. For example, the factuality gets 95% precision and 90% recall on a dataset containing 4000 responses, which was already rated by humans.

## Geospatial Content in Google Maps
<iframe class="iframe-video" width="780" height="439" src="https://www.youtube.com/embed/nnok8ZVQdWM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe>
I led a cross-platform (iOS and Android) system for serving virtual content in Google Maps Street View and Live View, impacting millions of users at landmark locations globally. The virtual contents align accurately with geo coordinates and buildings.

## Geospatial API
<iframe class="iframe-video" width="780" height="439" src="https://www.youtube.com/embed/udoSz_UBUdc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe>
I led the Geospatial API, which was launched at Google I/O 2022. The ARCore Geospatial API enables you to remotely attach content to any area covered by Google Street View and create AR experiences on a global scale. It uses device sensor and GPS data to detect the device's environment, then matches the recognizable parts of that environment to a localization model provided by Google’s Visual Positioning System (VPS) to determine the precise location of a user’s device.
[Project link](https://developers.google.com/ar/develop/geospatial)

## Geospatial API V2
<iframe class="iframe-video" width="780" height="439" src="https://www.youtube.com/embed/BPCuT_5Hv8U" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe>
I led the Streetscape Geometry APIs, which was launched at Google I/O 2023. The Streetscape Geometry APIs provide the geometry of terrain, buildings, or other structures in a scene. The geometry can be used for occlusion, rendering, or placing AR content via hit-test APIs. Streetscape Geometry data is obtained through Google Street View imagery.
[Project link](https://developers.google.com/ar/develop/unity-arf/geospatial/streetscape-geometry)

## Google Maps AR W1alking Navigation 
<iframe class="iframe-video" width="780" height="439" src="https://www.youtube.com/embed/-6JHDmnMB_g" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe>
I worked on improving AR Walking Navigation experience in indoor venues such as TRansit hubs, Airports and Malls (TRAMs). Concretely I aim to improve turn barrier placement in indoor scenarios and multi-floor transition. ARWN allows users within select Malls/Airports/TRansit hubs to use 3D navigation indoors, with multi-floor guidance to lead users to leveling points (stairs / escalators / elevators) so that they can reach their focused location. We provided more active guidance since airports and train stations usually have complex layouts requiring some type of navigation routing (e.g., U-shape buildings, mandatory passage through security checkpoints).

<br>

# Talks
<iframe class="iframe-video" width="780" height="439" src="https://www.youtube.com/embed/UIr6bV4ZCw8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe>
What’ new in Google AR at Google Developer Summit China
Discover how ARCore enables developers to create immersive and interactive AR applications with features focused on realism, perception, and asynchronous interaction.
