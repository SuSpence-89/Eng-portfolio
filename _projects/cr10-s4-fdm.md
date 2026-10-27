---
layout: post
permalink: /projects/cr10-s4-fdm/
title: "Creality CR-10 S4 — Recommissioning & Prototype Development"
description: "Recommissioning a modified large-format FDM printer through mechanical inspection, calibration, troubleshooting, and the development of custom CAD-assisted prototypes."
main-image: /assets/images/3d-printing/cr10-s4-overview.jpg

portfolio_type: "Personal Technical Project"
institution: "Independent Technical Project"
project_date: "October 2026"
show_in_portfolio: true

portfolio_categories:
  - mechanical
  - printing

skills:
  - Equipment Recommissioning
  - Mechanical Troubleshooting
  - FDM 3D Printing
  - Machine Calibration
  - Ultimaker Cura
  - CAD Development
  - Rapid Prototyping
  - Design for Additive Manufacturing
---

## Project Overview

This ongoing personal technical project involved recommissioning a previously operated Creality CR-10 S4 large-format FDM 3D printer following transportation and reassembly.

The printer incorporated several modifications, including a customized toolhead assembly, BLTouch automatic bed-levelling probe, Bowden-style filament delivery system, and removable glass build surface.

My objective was to inspect the equipment, establish a functional printing workflow, troubleshoot operational issues, and develop the machine into a platform for practical prototyping and custom component fabrication.

Following successful recommissioning, I progressed from straightforward functional prints to more complex CAD-assisted prototype development.

## 1. Equipment Inspection & Recommissioning

The initial stage involved examining the printer's mechanical configuration and identifying the components associated with its motion, extrusion, and build-surface systems.

My inspection included:

- Aluminum extrusion frame and mechanical connections.
- Motion assemblies, guide rollers, and travel clearances.
- Customized toolhead and cooling arrangement.
- Bowden filament delivery system.
- BLTouch automatic bed-levelling probe.
- Removable glass build surface.
- Controller operation and machine configuration.

Because the printer had previously been modified, understanding its existing configuration was an important part of establishing a reliable operating baseline.

Rather than immediately changing multiple settings, I approached recommissioning through individual inspections, controlled adjustments, and practical verification.

<figure>
  <img src="{{ '/assets/images/3d-printing/cr10-s4-side-view.jpg' | relative_url }}"
       alt="Side perspective of the Creality CR-10 S4 showing its aluminum extrusion frame, diagonal supports, and glass build platform"
       loading="lazy">
  <figcaption>
    Mechanical configuration of the CR-10 S4, including its large-format frame and supporting components.
  </figcaption>
</figure>

## 2. Bed Levelling & Z-Offset Calibration

An important part of restoring print functionality involved establishing the correct relationship between the nozzle, automatic probing system, and build surface.

Using the BLTouch probe, I performed bed-probing operations and progressively adjusted the nozzle Z-offset.

A paper-drag reference method was used to evaluate the nozzle's position relative to the glass surface.

The tested Z-offset progressed through several adjustments before converging near -3.200 mm, producing gentle paper resistance at the commanded Z=0.0 mm position.

This provided a practical initial calibration reference for subsequent first-layer printing tests.

The procedure reinforced the importance of repeatable measurement, incremental adjustments, and verifying physical equipment behaviour rather than relying exclusively on stored machine parameters.

<figure>
  <img src="{{ '/assets/images/3d-printing/cr10-s4-toolhead.jpg' | relative_url }}"
       alt="Modified CR-10 S4 toolhead assembly with BLTouch probe positioned over the glass build platform"
       loading="lazy">
  <figcaption>
    Customized toolhead assembly, including the BLTouch probe and Bowden filament connection.
  </figcaption>
</figure>

## 3. Slicer Configuration & Print Workflow

Following mechanical inspection and calibration, I configured Ultimaker Cura for the CR-10 S4.

Initial print preparation involved:

- Establishing the printer profile.
- Configuring a nominal 0.4 mm nozzle.
- Using approximately 0.20 mm layer heights.
- Preparing PLA print jobs.
- Evaluating model dimensions and print orientation.
- Reviewing generated toolpaths.
- Configuring support structures where required.
- Exporting Marlin-compatible G-code.

I also investigated an issue preventing the printer from recognizing files on a microSD card.

Following storage-format testing, I established a functional print-selection workflow using a 4 GB FAT32/MBR primary partition.

The experience demonstrated how mechanical equipment, firmware behaviour, digital storage, and slicing software interact within an additive-manufacturing workflow.

## 4. Initial Fabrication — PLA Storage Box

With a functional printing workflow established, I completed a practical fabrication project involving a rectangular storage container and removable handled lid.

This was my first completed multi-component print during the recommissioning period.

The exercise allowed me to evaluate print preparation, model scale, fabrication time, surface quality, and dimensional fit.

Both components were successfully produced and assembled.

Subsequent fit testing identified insufficient frictional retention between the lid and container, providing an opportunity for further dimensional refinement.

[View the PLA Storage Box Project]({{ '/projects/pla-storage-box/' | relative_url }})

This initial fabrication exercise provided a useful foundation before progressing into more complex prototype geometry.

## 5. CAD Development — Dragon Egg Prototype

Following the successful fabrication of the storage box, I began developing a custom two-piece dragon egg featuring overlapping reptilian scales.

The objective was to explore more complex geometry while incorporating a functional removable lid.

The concept was developed through AI-assisted CAD generation, with my direction guiding the intended geometry, mechanical features, surface appearance, and design revisions.

The design evolved from an initial smooth-shell concept into a hollow, two-piece assembly featuring:

- Large overlapping reptilian scales.
- Separate upper and lower components.
- A modelled two-tab bayonet-style twist-lock mechanism.
- Approximately 35 degrees of nominal rotational engagement.
- STEP and STL exports for design review and fabrication.

The nominal CAD geometry measured approximately 132 mm in height and 116 mm at its maximum exterior diameter.

<figure>
  <img src="{{ '/assets/images/3d-printing/dragon-egg-cad.jpg' | relative_url }}"
       alt="CAD model showing the two-piece dragon egg with overlapping reptilian scales"
       loading="lazy">
  <figcaption>
    CAD development of the two-piece dragon egg with overlapping scale geometry.
  </figcaption>
</figure>

## 6. Physical Prototyping & Print Evaluation

To evaluate the design before committing to full-size fabrication, I prepared and printed a reduced-scale prototype.

The initial physical test consisted of a 40%-scale version of the lower egg component, manufactured using red PLA.

The prototype successfully reproduced the exterior overlapping-scale pattern and general bowl geometry.

<figure>
  <img src="{{ '/assets/images/3d-printing/dragon-egg-base.jpg' | relative_url }}"
       alt="Completed red PLA dragon egg base prototype showing the overlapping scale pattern"
       loading="lazy">
  <figcaption>
    Completed 40%-scale prototype demonstrating the exterior surface geometry.
  </figcaption>
</figure>

During fabrication, I observed loose filament strands developing within the interior of the component.

<figure>
  <img src="{{ '/assets/images/3d-printing/dragon-egg-print.jpg' | relative_url }}"
       alt="Dragon egg base prototype during fabrication on the Creality CR-10 S4"
       loading="lazy">
  <figcaption>
    Reduced-scale prototype during fabrication.
  </figcaption>
</figure>

<figure>
  <img src="{{ '/assets/images/3d-printing/dragon-egg-interior.jpg' | relative_url }}"
       alt="Interior of the completed dragon egg base showing loose filament strands"
       loading="lazy">
  <figcaption>
    Interior inspection identifying areas requiring additional support and toolpath evaluation.
  </figcaption>
</figure>

Cura supports were enabled during the prototype print.

Further investigation is required to determine whether the observed interior material resulted from support-toolpath behaviour, bridging, stringing, or a combination of factors.

The reduced-scale prototype was useful for evaluating the exterior geometry and general printability.

However, scaling the component also altered its intended dimensional clearances. Consequently, this print was not considered a valid functional test of the full-size twist-lock mechanism.

## 7. Technical Outcomes & Lessons Learned

This project demonstrated the progression from equipment recommissioning to functional additive manufacturing and custom prototype development.

Key technical outcomes included:

- Inspecting and recommissioning a modified large-format FDM printer.
- Performing mechanical checks and nozzle-reference calibration.
- Establishing a functional Cura-to-printer workflow.
- Troubleshooting digital storage and material-handling issues.
- Successfully fabricating a practical multi-component storage box.
- Developing complex CAD geometry through an iterative, AI-assisted design process.
- Producing a reduced-scale physical prototype.
- Identifying manufacturing considerations requiring further design and slicer optimization.

The experience reinforced the importance of understanding the relationships between mechanical equipment, software configuration, material behaviour, and component geometry.

It also demonstrated the value of progressing through controlled testing rather than attempting to validate a complex design in a single manufacturing operation.

## 8. Continuing Development

The project remains active, with several opportunities for further technical development.

Planned activities include:

- Reviewing internal support and toolpath behaviour.
- Optimizing print orientation and support configuration.
- Producing mating twist-lock test features at their intended dimensions.
- Evaluating rotational engagement, clearances, and mechanical retention.
- Completing the full-size dragon egg assembly.
- Documenting final dimensions, print duration, and material consumption.

**Project Status:** Ongoing. Functional PLA printing and reduced-scale prototype fabrication have been demonstrated. Full-size twist-lock engagement and final assembly performance remain to be validated.

---

*This project documents my equipment recommissioning, calibration, troubleshooting, fabrication, and prototype evaluation activities. Dragon egg CAD geometry was developed collaboratively using AI-assisted design tools under my direction.*
