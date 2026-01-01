---
title: Research

nav:
  order: 2
---

# {% include icon.html icon="fa-solid fa-robot" %}Featured Research

The ultimate goal of our research is to enable **trustworthy**, **interactive**, and **human-centered** autonomous embodied agents that can perceive, understand, and reason about the physical world; safely interact and collaborate with humans; and efficiently coordinate with other intelligent agents so that they can benefit society in daily lives. To accomplish this goal, our team has been pursuing 
interdisciplinary research that develops <em>fundamental theories</em> and <em>practical algorithms</em> grounded in robotics, machine learning, reinforcement learning, computer vision, control theory, and optimization, which are validated on various <em>robotic hardware platforms</em> such as humanoid mobile manipulators, quadrupeds, autonomous vehicles, manipulators, and drones. 

<!-- <div class="gif-grid">
  <img src="{{ 'research_gifs/gif1.gif' | relative_url }}" alt="Single-Robot Social Navigation">
  <img src="{{ 'research_gifs/gif2.gif' | relative_url }}" alt="Multi-Robot Social Navigation">
  <img src="{{ 'research_gifs/gif3.gif' | relative_url }}" alt="Multi-Robot Object Goal Navigation">
  <img src="{{ 'research_gifs/gif4.gif' | relative_url }}" alt="Human Following">
  <img src="{{ 'research_gifs/gif5.gif' | relative_url }}" alt="Long-Horizon Manipulation">
  <img src="{{ 'research_gifs/gif6.gif' | relative_url }}" alt="Personalized Driving">
</div> -->

<div class="gif-grid">
  <div class="gif-item">
    <img src="{{ 'research_gifs/gif1.gif' | relative_url }}" alt="Single-Robot Social Navigation">
    <div class="gif-caption">Single-Robot Social Navigation</div>
  </div>

  <div class="gif-item">
    <img src="{{ 'research_gifs/gif2.gif' | relative_url }}" alt="Multi-Robot Cooperative Social Navigation">
    <div class="gif-caption">Multi-Robot Cooperative Social Navigation</div>
  </div>

  <div class="gif-item">
    <img src="{{ 'research_gifs/gif3.gif' | relative_url }}" alt="Multi-Robot Object Goal Navigation">
    <div class="gif-caption">Multi-Robot Object Goal Navigation</div>
  </div>

  <div class="gif-item">
    <img src="{{ 'research_gifs/gif4.gif' | relative_url }}" alt="Human Following">
    <div class="gif-caption">Single-Robot Human Following</div>
  </div>

  <div class="gif-item">
    <img src="{{ 'research_gifs/gif5.gif' | relative_url }}" alt="Long-Horizon Robotic Manipulation">
    <div class="gif-caption">Long-Horizon Robotic Manipulation</div>
  </div>

  <div class="gif-item">
    <img src="{{ 'research_gifs/gif6.gif' | relative_url }}" alt="Personalized Driving">
    <div class="gif-caption">Personalized Autonomous Driving</div>
  </div>
</div>

<!-- {% include list_research.html component="card" data="projects" filters="group: featured" %} -->
{% include list_research.html component="card_research" data="research"%}