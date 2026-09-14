---
layout: default
title: Steering Wheel
---

<!-- Dark Top Banner with Title and Subtitle -->
<div class="projects-header">
  <h1 class="page-title">Steering Wheel</h1>
  <p class="project-subtitle">"This is an ongoing project"</p>
</div>

<!-- Main Content Area -->
<div class="project-detail-body">
  <div class="project-content-container">

    <!-- Intro Text Paragraph -->
    <p class="intro-text">
      My most recent project with the Formula SAE Electric team has been the design, manufacturing, and testing of the steering wheel. In the 2023-24 school year, a steering wheel was designed for the car but was never fully built and had many design flaws. Because of this, I decided to completely re-design the steering wheel from scratch.
    </p>

    <!-- Row 1: Image Left, Text Right -->
    <div class="feature-row">
      <div class="feature-image">
        <img src="{{ '/assets/images/steering-front.jpg' | relative_url }}" alt="Steering Wheel Front Face">
      </div>
      <div class="feature-text">
        <p>
          The main body of the steering wheel has two main parts: the front face that houses all electrical components, and the back face that has an integrated aluminum plate to connect to the steering hub and paddles.
        </p>
        <p>
          The finger and thumb holes use variable fillets to create optimal grip on the wheel for the driver. The thumb hole specifically is designed to be large enough for the members of the team with the largest thumbs to be able to comfortably remove their thumbs as needed while still holding smaller thumbs in place.
        </p>
      </div>
    </div>

    <!-- Row 2: Text Left, Image Right -->
    <div class="feature-row reverse">
      <div class="feature-text">
        <p>
          The paddles for the steering wheel went through many iterations before I finally landed on the final design. I originally designed the paddle using bearings, an aluminum shaft, and retaining snap rings. This design was expensive and worked just as well as the final design which uses two M4 screws to hold the paddle on the base.
        </p>
        <p>
          The original design also had the paddle split into two which would allow it to mount inside of the base property. After mechanical testing, I determined that this decreased the strength of the paddle enough that it would not be viable on the final design. Because of this, I split the base into two parts on the top where there are little to no forces to cause breakage.
        </p>
        <p>
          The design uses a limit switch to know when it is being engaged and magnets to counteract the force of engagement.
        </p>
      </div>
      <div class="feature-image">
        <img src="{{ '/assets/images/steering-paddles.jpg' | relative_url }}" alt="Paddle Assembly">
      </div>
    </div>

    <!-- Row 3: Image Left, Text Right -->
    <div class="feature-row">
      <div class="feature-image">
        <img src="{{ '/assets/images/steering-gasket.jpg' | relative_url }}" alt="Ingress Protection and Gasket">
      </div>
      <div class="feature-text">
        <p>
          A very important aspect of the Steering Wheel is the ingress protection. The PCB and other electrical components within the Steering Wheel are not waterproof, which means that when the front and back face of the Steering Wheel come together, no water can get in. To prevent this, gasketing is added around the circumference of the wheel and around each of the finger and thumb holes.
        </p>
        <p>
          Additionally, to be in compliance with FSAE rules, all exposed metal components, including fasteners, must be grounded. To achieve this, 28 gauge grounding wires are wrapped around the heat-set inserts and travel along small paths to a central grounding point on the Steering Wheel PCB.
        </p>
      </div>
    </div>

    <!-- Skills Section at the Bottom -->
    <div class="skills-section">
      <h3 class="skills-heading">MAIN SKILLS</h3>
      <div class="skills-list">
        <span class="skill-pill">COMPUTER AIDED DESIGN</span>
        <span class="skill-pill">RAPID PROTOTYPING</span>
        <span class="skill-pill">MECHANICAL TESTING</span>
        <span class="skill-pill">MECHANICAL PCB ARRANGEMENT</span>
      </div>
    </div>

  </div>
</div>
