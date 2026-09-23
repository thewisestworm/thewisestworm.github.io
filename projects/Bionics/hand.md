---
layout: default
title: Bionic Hand
---

<!-- Dark Top Banner with Title and Subtitle -->
<div class="projects-header">
  <h1 class="page-title">Bionic Hand</h1>
</div>

<!-- Main Content Area -->
<div class="project-detail-body">
  <div class="project-content-container">

    <!-- Section 1: Initial Design -->
    <div class="feature-row">
      <div class="feature-image">
        <img src="{{ '/assets/images/bionic-hand-v1.jpg' | relative_url }}" alt="Initial Bionic Hand Design">
      </div>
      <div class="feature-text">
        <p><strong>Initial Design (Pin-Joint Fingers) </strong></p>
        <p>
          The first iteration of the hand used the PETG bionic finger with pin joints and integrated it with a palm and thumb design. The base material of the hand was originally PLA but then was swapped to PETG to decrease damage due to heavy use. This design also had low infill TPU (~5%) on all exposed surfaces to allow for softer, better grip.  
        </p>
        <p>
          There were a few main issues with this initial design including the thumb closing at the incorrect angle, finger spring-back put a lot of strain on the servos and fishing line, and the design generally used a lot of parts, making it very complicated to assemble.
        </p>
      </div>
    </div>

    <!-- Section 2: Revision Design -->
    <div class="feature-row reverse">
      <div class="feature-text">
        <p><strong>Revised and Simplified Design</strong></p>
        <p>
          To address the issues from the initial design, I developed a second iteration of the hand using a finger design that used TPU which allowed it to spring back without needing to engage the servos. I also changed the thumb angle and joint, transitioning from a pin joint to a TPU piece that connected to the PETG hand body using dovetail joints. This reduced the amount of hardware needed to assemble the hand and reduced cost. 
        </p>
      </div>
      <div class="feature-image">
        <img src="{{ '/assets/images/bionic-hand-v2.jpg' | relative_url }}" alt="Revised Bionic Hand Design">
      </div>
    </div>

    <!-- Skills Section at the Bottom -->
    <div class="skills-section">
      <h3 class="skills-heading">MAIN SKILLS</h3>
      <div class="skills-list">
        <span class="skill-pill">MECHANICAL DESIGN & CAD</span>
        <span class="skill-pill">MULTI-MATERIAL 3D PRINTING (PLA/TPU)</span>
        <span class="skill-pill">TENDON-DRIVEN ACTUATION</span>
        <span class="skill-pill">PROTOTYPE ITERATION & TESTING</span>
      </div>
    </div>

  </div>
</div>
