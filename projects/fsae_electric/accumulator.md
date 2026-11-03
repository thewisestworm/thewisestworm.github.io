---
layout: default
title: Accumulator
---

<!-- Dark Top Banner with Title and Subtitle -->
<div class="projects-header">
  <h1 class="page-title">Accumulator</h1>
  <p class="project-subtitle">Formula SAE Electric High-Voltage Energy Storage System</p>
</div>

<!-- Main Content Area -->
<div class="project-detail-body">
  <div class="project-content-container">

    <!-- Intro Text Paragraph -->
    <p class="intro-text">
      I started off my time on the Formula SAE team designing the Accumulator for our 2023-24 competition car. When the 2024-25 season came around, I was the mechanical design lead on the team and, in addition to managing design reviews for all        new components, I also re-designed the high-voltage energy storage system. The design balances Formula SAE structural and safety rules, vibrational loads, and thermal requirements.
    </p>

    <!-- Section 1: Module Design -->
    <div class="feature-row">
      <div class="feature-image">
      <!-- Slideshow Container -->
        <div class="project-slideshow">
          <div class="slide">
            <img src="{{ '/assets/images/module-bottom.jpg' | relative_url }}" alt="Battery module design">
          </div>
          <div class="slide">
            <img src="{{ '/assets/images/module-otherside.jpg' | relative_url }}" alt="Battery module Top">
          </div>
        </div>
      </div>
      <div class="feature-text">
        <p><strong>Module Design</strong></p>
        <p>
          Each module is a 12s5p layout of lithium-ion cells, resulting in a nominal voltage of 43.2 V and a maximum voltage of 50.4 V. Eight modules were connected in series within the accumulator, resulting in a total pack voltage of 345.6 V nominal and 403.2 V at full charge. I used Garolite plates on the top and bottom for rigidity, with machined polycarbonate side panels that located and supported the cells.
        </p>
        <p>
        I integrated custom sensing PCBs on both sides of the module to provide cell voltage sensing and temperature monitoring. I also designed custom copper busbars that were bonded to the PCB surface and spot welded to the cells using nickel strips placed on top of the copper to improve weld consistency.
        </p>
      </div>
    </div>

    <!-- Section 2: Enclosure and Mounting -->
    <div class="feature-row reverse">
      <div class="feature-text">
        <p><strong>Enclosure and Mounting</strong></p>
        <p>
          I designed rails for easy installation of the modules into the accumulator. The rails were made from UHMW because of its low coefficient of friction, allowing the modules to slide in and out easily while maintaining a tight fit. The pack-level busbars were located in the center of the accumulator, and a module only connected to the busbars once it was fully seated. This meant that removing a module for maintenance immediately disconnected it from the rest of the pack.
        </p>
        <p>
          I designed the accumulator around a sheet-bent aluminum enclosure with the GLV box mounted on top. The HV busbars passed directly through the enclosure and into the GLV box, keeping them protected from accidental contact. This also minimized the amount of HV wiring needed between different areas of the vehicle.
        </p>
      </div>
      <div class="feature-image">
      <!-- Slideshow Container -->
        <div class="project-slideshow">
          <div class="slide">
            <img src="{{ '/assets/images/Screenshot 2026-11-02 161000.png' | relative_url }}" alt="Accumulator Enclosure">
          </div>
          <div class="slide">
            <img src="{{ '/assets/images/acc-enclosure.jpg' | relative_url }}" alt="Sheetmetal Enclosure">
          </div>
        </div>
      </div>
    </div>

<!-- Section 3: Manufacturing -->
    <div class="feature-row">
      <div class="feature-image">
      <!-- Slideshow Container -->
        <div class="project-slideshow">
          <div class="slide">
            <img src="{{ '/assets/images/Screenshot 2026-11-02 142757.png' | relative_url }}" alt="Copper Busbar Manufacturing">
          </div>
          <div class="slide">
            <img src="{{ '/assets/images/busbar-mold.jpg' | relative_url }}" alt="Copper Busbar Press">
          </div>
          <div class="slide">
            <img src="{{ '/assets/images/fr4-machine.jpg' | relative_url }}" alt="FR4 Machine">
          </div>
          <div class="slide">
            <img src="{{ '/assets/images/uhmw-machine.jpg' | relative_url }}" alt="UHMW Machine">
          </div>
        </div>
      </div>
      <div class="feature-text">
        <p><strong>Manufacturing</strong></p>
        <p>
          To manufacture the busbars I tested many setups until I found a reliable way to hold and machine the thin copper sheet. I ended on a process where I covered the work surface and copper with blue painter’s tape, then used 3M Super 77 between the tape to hold the copper in place during machining. After machining the busbar shapes, I removed the tape, flattened the copper, and used custom 3D-printed jigs to add thermal relief bends to the busbars.
        </p>
        <p>
          I machined the module rails out of UHMW on a CNC Mill. I found that UHMW deformed from machining heat, which made tight tolerances difficult to achieve. After making these parts, I read up more in DFM and applied what I learned to the polycarbonate module sides, which I machined as a 1-operation part from a single sheet on a CNC Router.
        </p>
      </div>
    </div>

    <!-- Skills Section at the Bottom -->
    <div class="skills-section">
      <h3 class="skills-heading">MAIN SKILLS</h3>
      <div class="skills-list">
        <span class="skill-pill">HIGH-VOLTAGE BATTERY PACKAGING</span>
        <span class="skill-pill">COMPUTER AIDED DESIGN (SOLIDWORKS)</span>
        <span class="skill-pill">RAPID PROTOTYPING</span>
        <span class="skill-pill">MATERIALS SELECTION</span>
      </div>
    </div>

  </div>
</div>
