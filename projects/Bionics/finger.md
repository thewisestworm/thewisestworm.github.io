---
layout: default
title: Bionic Finger
---

<!-- Dark Top Banner with Title and Subtitle -->
<div class="projects-header">
  <h1 class="page-title">Bionic Finger</h1>
  <p class="project-subtitle">SUBTITLE HERE</p>
</div>

<!-- Main Content Area -->
<div class="project-detail-body">
  <div class="project-content-container">

    <!-- Intro Text Paragraph -->
    <p class="intro-text">
      The Bionic Finger project started in August of 2022 as part of an ongoing prosthetic hand initiative. Over four distinct generations of prototyping, I evolved the mechanical linkages, actuation methods, and material choices to balance aesthetic realism with home-printable simplicity and durability.
    </p>

    <!-- Section 1: Initial Design (T-Belts) -->
    <div class="feature-row">
      <div class="feature-image">
        <img src="{{ '/assets/images/finger-v1.jpg' | relative_url }}" alt="Initial T-Belt Finger Design">
      </div>
      <div class="feature-text">
        <p><strong>Generation 1: T-Belt Concept</strong></p>
        <p>
          The original design used small T-belts (similar to those used on 3D printers) between each finger section so the joint would move in a fluid motion driven by a motor or servo. 
        </p>
        <p>
          While it looked like a natural finger, it failed mechanically: components that modeled successfully in Onshape did not translate effectively to real-world physical assembly, prompting a complete redesign.
        </p>
      </div>
    </div>

    <!-- Section 2: Second Design (Lead Screw & Linkages) -->
    <div class="feature-row reverse">
      <div class="feature-text">
        <p><strong>Generation 2: Lead Screw & Complex Linkages</strong></p>
        <p>
          The second version was mechanically intricate, using a small DC motor with a lead screw attached to the "knuckle" to translate linear motion into fluid bending. 
        </p>
        <p>
          Initial prints were brittle, which I solved by testing various materials and ultimately switching to PETG for its balance of flexibility and strength, alongside thickening each structural member.
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
          Finished in May 2023, this design aimed to simplify the complexity of the previous iteration. It combined elements from earlier builds into a home-printable design using basic 3D printing capabilities and a limited budget.
        </p>
        <p>
          It utilized a simple pin-insertion joint mechanism for easy assembly and scaling, constructed from PETG structural segments with slip-on TPU covers for padding and realistic aesthetics.
        </p>
      </div>
    </div>

    <!-- Section 4: Fourth & Final Design -->
    <div class="feature-row reverse">
      <div class="feature-text">
        <p><strong>Generation 4: Final Optimized Iteration</strong></p>
        <p>
          The fourth and final design streamlined the mechanism even further to maximize reliability and ease of fabrication. 
        </p>
        <p>
          This version refined the pin-joint tolerances and integrated tendon/cable routing directly into the structural core, optimizing the finger for seamless integration into a complete prosthetic hand assembly while maintaining low part counts and high durability.
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
        <span class="skill-pill">MECHANICAL POST-PROCESSING</span>
      </div>
    </div>

  </div>
</div>
