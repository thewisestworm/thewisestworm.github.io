---
layout: default
title: Bionic Finger
---

<!-- Dark Top Banner with Title and Subtitle -->
<div class="projects-header">
  <h1 class="page-title">Bionic Finger</h1>
</div>

<!-- Main Content Area -->
<div class="project-detail-body">
  <div class="project-content-container">

    <!-- Intro Text Paragraph -->
    <p class="intro-text">
      The Bionic Finger project started in August of 2022 as part of a larger prosthetic hand project. This project has been passed off to students at Worcester Polytechnic Institute to learn how to design bionic limbs. 
    </p>

    <!-- Section 1: Initial Design (T-Belts) -->
    <div class="feature-row">
      <div class="feature-image">
        <img src="{{ '/assets/images/finger-v1.jpg' | relative_url }}" alt="Initial T-Belt Finger Design">
      </div>
      <div class="feature-text">
        <p><strong>Generation 1: T-Belt Concept</strong></p>
        <p>
          The original design used small T-belts (similar to those used on 3D printers) between each finger section so the joints would move in a fluid motion driven by a servo. 
        </p>
        <p>
          While it looked like a natural finger, it had a few mechanical failures. Many of the components in the assembly were quite small and difficult to manufacture and assemble using a basic 3D printer. Because the eventual use-case was an open source hand for people to make at home, this design was not ideal.
        </p>
      </div>
    </div>

    <!-- Section 2: Second Design (Lead Screw & Linkages) -->
    <div class="feature-row reverse">
      <div class="feature-text">
        <p><strong>Generation 2: Lead Screw & Complex Linkages</strong></p>
        <p>
          The second version of the finger was more mechanically intricate, using a small DC motor with a lead screw attached to the "knuckle" to translate linear motion into bending. This design was not meant as a prosthetic, rather I used it as a way to learn how to use linkages in my designs.  
        </p>
      </div>
      <div class="feature-image">
        <img src="{{ '/assets/images/finger-v2.jpg' | relative_url }}" alt="Lead Screw Finger Design">
      </div>
    </div>

    <!-- Section 3: Third Design (Pin Joints & PETG/TPU) -->
    <div class="feature-row">
      <div class="feature-image">
        <img src="{{ '/assets/images/finger-v3.jpg' | relative_url }}" alt="Simplified Pin-Joint Finger">
      </div>
      <div class="feature-text">
        <p><strong>Generation 3: Simplified Pin Joints</strong></p>
        <p>
          In May 2023, I finished the first fully functional design of the bionic finger. I aimed to simplify the complexity of the previous iterations by using fishing line instead of t-belts and a realistic yet simplified aesthetic.
        </p>
        <p>
          The design also utilized a simple pin-insertion joint mechanism for easy assembly and had slip-on TPU covers for padding on the finger pads.
        </p>
      </div>
    </div>

    <!-- Section 4: Fourth & Final Design -->
    <div class="feature-row reverse">
      <div class="feature-text">
        <p><strong>Generation 4: Final Optimized Iteration</strong></p>
        <p>
          In the fourth and final design, I simplified the mechanism even further to maximize reliability and ease of manufacturing. 
        </p>
        <p>
          This version removed the pin-joint and instead replaced the entire finger print with high-infill TPU that thinned out at the bending joints. I kept the fishing line through the finger to allow for bending control with a servo. By creating the finger as one part, there was virtually no assembly time and all fingers for a hand couple be printed on one print bed without supports.
        </p>
      </div>
      <div class="feature-image">
        <img src="{{ '/assets/images/finger-v4.jpg' | relative_url }}" alt="Final Optimized Bionic Finger">
      </div>
    </div>

    <!-- Skills Section at the Bottom -->
    <div class="skills-section">
      <h3 class="skills-heading">MAIN SKILLS</h3>
      <div class="skills-list">
        <span class="skill-pill">RAPID PROTOTYPING</span>
        <span class="skill-pill">COMPUTER AIDED DESIGN (ONSHAPE)</span>
        <span class="skill-pill">3D PRINTING & MATERIAL SELECTION</span>
      </div>
    </div>

  </div>
</div>
