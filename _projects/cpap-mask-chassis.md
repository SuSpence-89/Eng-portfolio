---
layout: post
permalink: /projects/cpap-mask-chassis/

title: "CPAP Mask Chassis — Reverse Engineering & Additive Manufacturing"

description: "An ongoing reverse-engineering and CAD project exploring a 3D-printable replacement for a frequently damaged CPAP mask strap-retention chassis."

main-image: /assets/images/cpap-mask-chassis/cpap-chassis-original-front.jpg
cover_position: center center
cover_alt: "Original transparent CPAP mask chassis featuring strap-attachment openings and a circular mask interface."
cover_caption: "Original CPAP mask chassis used as the reference component for reverse engineering and CAD development."

portfolio_type: "Personal Reverse Engineering & Prototyping Project"
institution: "Personal Workshop Project"
project_date: "2026 — Ongoing"
show_in_portfolio: true

portfolio_categories:
  - mechanical
  - prototyping

skills:
  - Reverse Engineering
  - CAD Modelling
  - Dimensional Analysis
  - Mechanical Design
  - Design for Additive Manufacturing
  - Prototype Development
  - Component Replacement Design
  - Design Iteration
---

## Project Overview

This ongoing project explores the design of a **3D-printable replacement chassis for a CPAP mask**.

The project originated from a recurring problem: the original plastic chassis is susceptible to breakage, and replacement components are relatively expensive.

Rather than continuing to replace the same component, I decided to investigate whether I could reproduce its geometry using CAD software and eventually manufacture a replacement through 3D printing.

The project involves reverse engineering an existing component, developing dimensioned geometry, constructing a three-dimensional CAD model, and evaluating the feasibility of additive manufacturing.

The chassis acts as a **mechanical support and strap-retention component**. It helps position the mask against the user's face by providing attachment points for the headgear straps.

The component is not intended to contact the user's skin directly or form part of the breathing-air pathway. However, its mechanical integrity is important because failure could affect mask positioning, sealing, and the effectiveness of therapy.

**Project Status:** Initial geometry and CAD development. A finished 3D-printed replacement has not yet been produced or validated.

---

## 1. Problem Identification

The project began with an everyday mechanical problem.

The original CPAP mask chassis experiences recurring breakage during normal ownership, creating the inconvenience and expense of purchasing replacement components.

Although the original part is relatively small, it performs an important mechanical function by connecting the headgear straps to the mask assembly.

The repeated failures prompted me to investigate whether the chassis could be reproduced using a different manufacturing method.

My goal was to develop a replacement geometry that could potentially be manufactured using a personal 3D printer.

The project also offered an opportunity to apply reverse-engineering principles to a real consumer product.

### Initial Design Objectives

- Study the geometry of the original chassis.
- Identify the functional attachment and interface features.
- Develop a dimensioned two-dimensional profile.
- Reproduce the component geometry using CAD software.
- Evaluate whether the geometry is suitable for 3D printing.
- Investigate potential improvements to the component's durability.
- Assess fit and mechanical performance through future prototype testing.

The initial focus was on understanding and recreating the component rather than immediately producing a finished replacement.

---

## 2. Original Component Inspection

The first stage involved examining the existing transparent plastic chassis.

The original component incorporates several distinct geometric features:

- A central circular opening associated with the mask assembly.
- An extended upper section.
- Openings and attachment features associated with the mask headgear.
- Curved transitions between structural sections.
- A relatively thin plastic body.

These features contribute to the component's overall shape and its ability to connect the mask to the supporting straps.

<figure>
  <img src="{{ '/assets/images/cpap-mask-chassis/cpap-chassis-original-front.jpg' | relative_url }}"
       alt="Front view of an original transparent CPAP mask chassis with circular mask opening and strap-retention features."
       loading="lazy">
  <figcaption>
    Original CPAP mask chassis used as the reference component.
    The circular mask interface, extended upper section,
    and strap-attachment features are visible.
  </figcaption>
</figure>

<figure>
  <img src="{{ '/assets/images/cpap-mask-chassis/cpap-chassis-original-angle.jpg' | relative_url }}"
       alt="Angled view of the original CPAP mask chassis showing the depth and shape of its moulded features."
       loading="lazy">
  <figcaption>
    Angled view of the original chassis, illustrating
    the three-dimensional shape and moulded features
    that must be considered during CAD development.
  </figcaption>
</figure>

Examining the physical component provided a starting point for understanding the relationship between its geometry and intended mechanical function.

An important consideration is that reproducing the external appearance alone does not guarantee that a replacement will perform correctly.

The final design will also need to account for attachment geometry, fit, flexibility, and the forces transmitted through the headgear straps.

---

## 3. Dimensional Analysis & Initial Sketch

After inspecting the original component, I began developing a dimensioned profile to establish the basic geometry of the replacement.

This involved identifying major dimensions, reference points, curved transitions, and the overall shape.

The initial sketch provides a basis for constructing the part in three dimensions.

<figure>
  <img src="{{ '/assets/images/cpap-mask-chassis/cpap-chassis-dimensioned-sketch.png' | relative_url }}"
       alt="Dimensioned CAD sketch of a CPAP mask chassis featuring an extended upper section, curved transitions, and a circular opening."
       loading="lazy">
  <figcaption>
    Initial dimensioned sketch used to develop the replacement
    chassis geometry. The sketch establishes the overall profile,
    reference dimensions, and curved transitions.
  </figcaption>
</figure>

### Geometric Considerations

The sketch includes:

- An overall length dimension.
- Width dimensions at selected locations.
- A central circular feature.
- Curved transitions between the upper and lower sections.
- Reference points used to control the part profile.

Using dimensioned geometry provides a more repeatable modelling approach than attempting to reproduce the original component entirely by eye.

This stage also provides an opportunity to evaluate the proportions of the original design and identify areas that may require refinement.

The dimensions shown represent the initial CAD development stage and remain subject to verification against the physical component.

---

## 4. CAD Development — Initial Extrusion

Once the initial two-dimensional profile was established, I began converting the sketch into a three-dimensional model.

The first modelling stage involved creating an extrusion from the developed profile.

This established the initial solid geometry and provided a foundation for subsequent modelling operations.

<figure>
  <img src="{{ '/assets/images/cpap-mask-chassis/cpap-chassis-initial-cad.png' | relative_url }}"
       alt="Initial three-dimensional CAD extrusion of the replacement CPAP mask chassis showing the curved body profile."
       loading="lazy">
  <figcaption>
    Initial CAD extrusion showing the preliminary
    three-dimensional chassis body. Additional attachment
    features and interface geometry remain to be developed.
  </figcaption>
</figure>

At this stage, the model represents an initial development step rather than a completed replacement.

Further modelling will be required to reproduce the component's functional openings, attachment features, and mask interface.

The CAD model will also need to account for the differences between the original manufacturing process and the proposed 3D-printing process.

---

## 5. Design for Additive Manufacturing

The original chassis is a moulded plastic component.

Producing a replacement through 3D printing introduces a different set of manufacturing considerations.

Features suitable for injection moulding may not necessarily perform the same way when reproduced using fused-filament fabrication.

### Areas Requiring Evaluation

**Material selection**

The printed material will need to provide suitable strength, toughness, flexibility, and dimensional stability for the intended application.

No final material selection has been established at this stage.

**Layer orientation**

The orientation of the part during printing may affect the strength of thin sections and attachment features.

This will need to be considered when evaluating the finished geometry.

**Attachment features**

The strap-connection areas may experience repeated loading and handling.

These features will require particular attention during prototype development.

**Dimensional accuracy**

The chassis must interface with the existing mask assembly and headgear.

Print tolerances and dimensional variation will therefore be important considerations.

**Surface finish**

Printed surfaces may differ from the original moulded component, particularly at edges and attachment points.

The final design will need to account for these differences.

---

## 6. Planned Prototype Development

The next stage will involve refining the CAD model and preparing it for an initial 3D print.

The planned development sequence includes:

1. Completing the required openings and attachment geometry.
2. Comparing the CAD model against the original physical component.
3. Reviewing material options for prototype fabrication.
4. Preparing the model in slicing software.
5. Evaluating print orientation and support requirements.
6. Producing an initial prototype.
7. Inspecting the printed component for dimensional accuracy and visible defects.
8. Performing appropriate fit and mechanical evaluations before considering any functional use.
9. Revising the model based on test results.

At present, these activities represent planned development rather than completed testing.

### Safety & Functional Validation

Although the chassis is not intended to contact the skin or breathing air, it contributes to retaining the CPAP mask in position.

A replacement must therefore be evaluated for appropriate fit, structural integrity, fatigue resistance, and retention performance.

A visually similar 3D-printed part should not be assumed to be equivalent to the original component.

Any future consideration of use during CPAP therapy would require appropriate validation and review with the relevant equipment manufacturer or qualified healthcare professional.

---

## 7. Engineering Value of the Project

This project demonstrates how reverse engineering and CAD modelling can be applied to a practical mechanical problem.

Rather than beginning with an original product concept, the work starts with an existing component whose geometry and function must be understood.

The process involves several distinct engineering activities.

### Reverse Engineering

Studying an existing component to understand its physical features, interfaces, and intended mechanical function.

### Dimensional Modelling

Translating physical geometry into a dimensioned sketch that can be used to construct a repeatable CAD model.

### Design Development

Converting the two-dimensional profile into a three-dimensional solid and identifying additional features required for the finished component.

### Manufacturing Considerations

Evaluating whether a component originally produced through moulding can be adapted for additive manufacturing.

### Practical Problem-Solving

Investigating a possible alternative to repeatedly replacing an expensive, failure-prone component.

---

## Project Status & Next Steps

**Current Status: CAD development in progress.**

The project has progressed through:

- Identification of the recurring component failure problem.
- Examination of the original chassis.
- Initial dimensional sketch development.
- Creation of an initial three-dimensional CAD extrusion.

Future work will focus on completing the geometry, evaluating material options, printing a prototype, and assessing its fit and mechanical performance.

No claims of functional equivalence or suitability for medical use are made at this stage.

As the design progresses, this portfolio page will be updated with additional CAD models, slicing previews, prototype photographs, and documented results.

---

## Skills Demonstrated

- Reverse engineering of an existing plastic component.
- Identification of mechanical interfaces and functional features.
- Dimensional sketch development.
- CAD modelling and initial solid creation.
- Geometric analysis of curved profiles.
- Design for additive manufacturing.
- Mechanical component prototyping.
- Consideration of manufacturing constraints.
- Design iteration and problem-solving.
- Planning for fit and functional verification.

---

## Project Summary

This ongoing project demonstrates my interest in applying **mechanical design, reverse engineering, and additive manufacturing** to solve practical problems.

The objective is to investigate whether a frequently damaged CPAP mask chassis can be reproduced through CAD modelling and 3D printing.

The work completed so far establishes the initial component geometry and provides a foundation for further prototype development.

The project also reinforces an important engineering principle:

**A successful replacement component must reproduce not only the geometry of the original part, but also the mechanical functionality required for its intended application.**
