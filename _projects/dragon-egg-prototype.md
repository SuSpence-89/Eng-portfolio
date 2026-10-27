---
layout: post
permalink: /projects/dragon-egg-prototype/
title: "Dragon Egg — CAD Design & FDM Prototyping"
description: "Development of a custom two-piece dragon egg using AI-assisted CAD modelling, overlapping scale geometry, a bayonet-style locking mechanism, and iterative FDM prototyping."
main-image: /assets/images/3d-printing/dragon-egg-base.jpg

portfolio_type: "Personal Design & Prototyping Project"
institution: "Independent Technical Project"
project_date: "October 2026"
show_in_portfolio: true

portfolio_categories:
  - printing

skills:
  - CAD Development
  - FDM 3D Printing
  - Design for Additive Manufacturing
  - Mechanical Design
  - Ultimaker Cura
  - Rapid Prototyping
  - Design Iteration
---

## Project Overview

Following the successful fabrication of a two-piece PLA storage box, I wanted to explore more complex geometry and mechanical functionality using my Creality CR-10 S4 large-format FDM printer.

The objective was to develop a custom dragon egg featuring overlapping reptilian scales, a hollow interior, and a removable lid secured through a mechanical twist-lock connection.

The project combined AI-assisted CAD generation, iterative design development, slicing configuration, and physical prototype evaluation.

## 1. Concept Development & Design Requirements

The initial concept was inspired by decorative dragon egg designs.

Rather than reproduce an existing model, I worked through an AI-assisted CAD development process, providing design direction and requesting modifications to the geometry and functional features.

The design requirements included:

- A hollow, two-piece egg construction.
- A removable upper lid and lower base.
- Large, overlapping reptilian scales.
- A mechanical twist-lock connection.
- Geometry suitable for FDM manufacturing.
- Exportable STEP and STL files.

The initial smooth-shell concept was revised to incorporate a more distinctive overlapping-scale pattern.

## 2. CAD Modelling & Mechanical Features

The resulting digital model incorporated a two-tab bayonet-style locking mechanism intended to secure the upper and lower components through rotational engagement.

The modelled mechanism provided approximately 35 degrees of nominal rotational travel.

The intended full-size geometry measured approximately:

- Overall height: 132 mm.
- Maximum exterior diameter: 116 mm.
- Construction: Hollow, two-piece assembly.
- Connection: Two-tab bayonet-style twist lock.

These values represent nominal CAD geometry rather than verified dimensions of a completed full-size assembly.

<figure>
  <img src="{{ '/assets/images/3d-printing/dragon-egg-cad.jpg' | relative_url }}"
       alt="CAD model showing the two-piece dragon egg and overlapping scale geometry"
       loading="lazy">
  <figcaption>
    CAD model of the proposed two-piece dragon egg with overlapping reptilian scales.
  </figcaption>
</figure>

STEP and STL files were generated to support further design review, modification, and fabrication.

## 3. Prototype Preparation & FDM Printing

Before committing to a full-size print, I prepared a reduced-scale prototype using Ultimaker Cura.

The lower egg component was scaled to 40% of its nominal dimensions to evaluate the exterior geometry and general printability while reducing material consumption and print duration.

The prototype was manufactured using red PLA on my Creality CR-10 S4.

Cura support structures were enabled during print preparation.

<figure>
  <img src="{{ '/assets/images/3d-printing/dragon-egg-print.jpg' | relative_url }}"
       alt="Dragon egg base prototype during FDM printing"
       loading="lazy">
  <figcaption>
    Reduced-scale dragon egg prototype during fabrication.
  </figcaption>
</figure>

## 4. Physical Prototype & Quality Evaluation

The completed 40%-scale base successfully reproduced the intended overlapping-scale exterior and general hollow shell geometry.

The physical prototype demonstrated that the complex surface geometry could be reproduced using the FDM process.

However, the print also revealed loose filament strands within the interior.

<figure>
  <img src="{{ '/assets/images/3d-printing/dragon-egg-interior.jpg' | relative_url }}"
       alt="Interior of the printed dragon egg base showing loose filament strands"
       loading="lazy">
  <figcaption>
    Interior inspection showing filament strands requiring further support and toolpath investigation.
  </figcaption>
</figure>

Because supports were enabled, additional Cura layer-preview inspection is required to determine whether the observed material resulted from support-toolpath behaviour, bridging, stringing, or a combination of factors.

The reduced-scale prototype was considered a preliminary manufacturing evaluation rather than a functional validation of the locking mechanism.

Scaling the model to 40% also altered its nominal dimensional clearances, making it unsuitable for accurately evaluating the full-size bayonet connection.

## 5. Technical Outcomes & Lessons Learned

This project provided practical experience transitioning from a digital design concept to a physical manufactured prototype.

Key outcomes included:

- Developing custom geometry through an iterative, AI-assisted CAD workflow.
- Translating functional requirements into a two-piece mechanical design.
- Incorporating a modelled rotational locking mechanism.
- Preparing STEP and STL files for manufacturing.
- Configuring and producing a reduced-scale FDM prototype.
- Evaluating complex exterior geometry.
- Identifying internal support and toolpath issues.
- Establishing priorities for further design iteration.

The completed prototype demonstrated promising exterior print quality while identifying manufacturing considerations requiring additional investigation.

## 6. Continuing Development

The next stage will focus on improving printability and validating the mechanical functionality of the design.

Planned activities include:

- Reviewing support structures and internal toolpaths.
- Optimizing print orientation and support settings.
- Producing mating twist-lock test features at their intended dimensions.
- Evaluating rotational engagement and mechanical retention.
- Refining dimensional clearances where necessary.
- Completing and testing the full-size lid and base assembly.

**Project Status:** Ongoing. The 40%-scale lower component has been successfully printed and evaluated. Full-size fabrication and functional testing of the bayonet-style locking mechanism remain outstanding.

---

*CAD geometry was developed collaboratively using AI-assisted design tools under my direction. Physical fabrication, inspection, and prototype evaluation were performed independently.*
