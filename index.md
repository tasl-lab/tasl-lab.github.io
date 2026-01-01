---
---

<!-- # We enhance Robotics and AI -->
##### Welcome to the Trustworthy Autonomous Systems Laboratory at the University of California, Riverside!
{% include section.html %}
## Highlights
{% capture text %}
The ultimate goal of our research is to enable **trustworthy**, **interactive**, and **human-centered** autonomous embodied agents that can perceive, understand, and reason about the physical world; safely interact and collaborate with humans; and efficiently coordinate with other intelligent agents so that they can benefit society in daily lives. To accomplish this goal, our team has been pursuing 
interdisciplinary research that develops <em>fundamental theories</em> and <em>practical algorithms</em> grounded in robotics, machine learning, reinforcement learning, computer vision, control theory, and optimization, which are validated on various <em>robotic hardware platforms</em> such as humanoid mobile manipulators, quadrupeds, autonomous vehicles, manipulators, and drones. 


{%
  include button.html
  link="research"
  text="See our featured topics"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{%
  include button.html
  link="publications"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/research_teaser.png"
  link="research"
  title="Our Research"
  text=text
%}

<div class="gif-grid"
     style="
       display: grid;
       grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
       gap: 15px;
       padding: 15px;
       background: linear-gradient(135deg, rgb(233, 240, 249), #eef2f7);
       border-radius: 5px;
     ">

  <div style="text-align:center;">
    <img src="{{ 'research_gifs/gif1.gif' | relative_url }}" alt="Single-Robot Social Navigation"
         style="width:100%; border-radius:3px; background:white; padding:4px; box-shadow:0 4px 12px rgba(0,0,0,0.08);">
    <div style="margin-top:6px; font-size:0.9rem; font-weight:500; color:#333;">
      Single-Robot Social Navigation
    </div>
  </div>

  <div style="text-align:center;">
    <img src="{{ 'research_gifs/gif2.gif' | relative_url }}" alt="Multi-Robot Cooperative Social Navigation"
         style="width:100%; border-radius:3px; background:white; padding:4px; box-shadow:0 4px 12px rgba(0,0,0,0.08);">
    <div style="margin-top:6px; font-size:0.9rem; font-weight:500; color:#333;">
      Multi-Robot Cooperative Social Navigation
    </div>
  </div>

  <div style="text-align:center;">
    <img src="{{ 'research_gifs/gif3.gif' | relative_url }}" alt="Multi-Robot Cooperative Object Goal Navigation"
         style="width:100%; border-radius:3px; background:white; padding:4px; box-shadow:0 4px 12px rgba(0,0,0,0.08);">
    <div style="margin-top:6px; font-size:0.9rem; font-weight:500; color:#333;">
      Multi-Robot Cooperative Object Goal Navigation
    </div>
  </div>

  <div style="text-align:center;">
    <img src="{{ 'research_gifs/gif4.gif' | relative_url }}" alt="Single-Robot Human Following"
         style="width:100%; border-radius:3px; background:white; padding:4px; box-shadow:0 4px 12px rgba(0,0,0,0.08);">
    <div style="margin-top:6px; font-size:0.9rem; font-weight:500; color:#333;">
      Single-Robot Human Following
    </div>
  </div>

  <div style="text-align:center;">
    <img src="{{ 'research_gifs/gif5.gif' | relative_url }}" alt="Long-Horizon Robotic Manipulation"
         style="width:100%; border-radius:3px; background:white; padding:4px; box-shadow:0 4px 12px rgba(0,0,0,0.08);">
    <div style="margin-top:6px; font-size:0.9rem; font-weight:500; color:#333;">
      Long-Horizon Robotic Manipulation
    </div>
  </div>

  <div style="text-align:center;">
    <img src="{{ 'research_gifs/gif6.gif' | relative_url }}" alt="Personalized Autonomous Driving"
         style="width:100%; border-radius:3px; background:white; padding:4px; box-shadow:0 4px 12px rgba(0,0,0,0.08);">
    <div style="margin-top:6px; font-size:0.9rem; font-weight:500; color:#333;">
      Personalized Autonomous Driving
    </div>
  </div>

</div>


<!-- <div class="gif-grid"
     style="
       display: grid;
       grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
       gap: 15px;
       padding: 15px;
       background: linear-gradient(135deg,rgb(233, 240, 249), #eef2f7);
       border-radius: 5px;
     ">
  <img src="{{ 'research_gifs/gif1.gif' | relative_url }}" alt="Single-Robot Social Navigation"
       style="width:100%; border-radius:3px; background:white; padding:4px; box-shadow:0 4px 12px rgba(0,0,0,0.08);">
  <img src="{{ 'research_gifs/gif2.gif' | relative_url }}" alt="Multi-Robot Social Navigation"
       style="width:100%; border-radius:3px; background:white; padding:4px; box-shadow:0 4px 12px rgba(0,0,0,0.08);">
  <img src="{{ 'research_gifs/gif3.gif' | relative_url }}" alt="Multi-Robot Object Goal Navigation"
       style="width:100%; border-radius:3px; background:white; padding:4px; box-shadow:0 4px 12px rgba(0,0,0,0.08);">
  <img src="{{ 'research_gifs/gif4.gif' | relative_url }}" alt="Human Following"
       style="width:100%; border-radius:3px; background:white; padding:4px; box-shadow:0 4px 12px rgba(0,0,0,0.08);">
  <img src="{{ 'research_gifs/gif5.gif' | relative_url }}" alt="Long-Horizon Manipulation"
       style="width:100%; border-radius:3px; background:white; padding:4px; box-shadow:0 4px 12px rgba(0,0,0,0.08);">
  <img src="{{ 'research_gifs/gif6.gif' | relative_url }}" alt="Personalized Driving"
       style="width:100%; border-radius:3px; background:white; padding:4px; box-shadow:0 4px 12px rgba(0,0,0,0.08);">
</div> -->

{% capture text %}




This lab is directed by [Prof. Jiachen Li](https://profiles.ucr.edu/app/home/profile/jiachenl). Lab members consist of students with backgrounds in engineering, computer science, and mathematics. Our lab is actively seeking multiple highly motivated talents to join us as Ph.D. students (fully funded), master/undergraduate students, onsite/remote research interns (outside of UC Riverside), visiting scholars, or postdoctoral researchers. If you are interested in joining us, please follow the application instructions on the [Join Us](./join/) page.

{%
  include button.html
  link="people"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/ucr.jpg"
  link="team"
  title="Our Team"
  flip=true
  style="bare"
  text=text
%}



{% include section.html %}
###### We gratefully acknowledge the supports from:

<div style="text-align: center;">
  <img src="images/NSF.svg" alt="NSF" width="230px" style="display:inline-block; vertical-align: middle; padding-left: 20px; padding-right: 20px; padding-top: 10px; padding-bottom: 10px;">
  <img src="images/UCR.svg" alt="UCR" width="250px" style="display:inline-block; vertical-align: middle; padding-left: 20px; padding-right: 20px; padding-top: 10px; padding-bottom: 10px;">
  <img src="images/Oasis.svg" alt="OASIS" width="160px" style="display:inline-block; vertical-align: middle; padding-left: 20px; padding-right: 20px; padding-top: 10px; padding-bottom: 10px;">
</div>