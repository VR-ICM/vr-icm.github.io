---
layout: ../layouts/Layout.astro
title: VR Building Simulation Research
description: Undergraduate research project exploring component-level VR learning environments for CAD/BIM-derived building models.
---

## Project Scope

This project investigates how VR can create focused learning environments for BIM building models. Models are built in Autodesk Revit and visualized in Unreal Engine, where parts of a building can be expanded, inspected, and connected to metadata such as their material properties and fire ratings.

[Meet the team.](/team/)

## Research Questions

- How much model preparation is required to make building components teachable in VR?
- What metadata is useful to show during inspection?
- Can VR support practical construction training at a low cost?
- Do VR visualizations support a student's mental understanding of blueprints?

[Read more about the research areas.](/research/)

## Current Status

We have already implemented the following:

- Prototype VR environment for viewing and interacting with building models
- Expandable, interactive wall and floor elements
- HUD display for metadata information

Next steps include integrating telemetry to understand a student's actions while inspecting a model or completing a task.

## Media and Demos

<style>
figure {
    margin: 1.5rem 0;
    padding: 1rem 1.2rem;
    border: 1px solid var(--rule);
    background: var(--page);
}

figcaption {
    color: var(--faint);
    font-size: 0.9rem;
    font-style: italic;
}

img,
video {
    max-width: 100%;
    height: auto;
}
</style>

<figure>
  <video controls preload="metadata" src="/6-30-26%20wall%20layer%20project%20demo-web.mp4"></video>
  <h3>Simulation prototype</h3>
  <p>Proof-of-concept interactivity demo from early in the project’s transition to Unreal Engine.</p>
</figure>
<figure>
  <img src="/summer%20symposium%20poster.jpg"></img>
  <h3>Symposium Poster</h3>
  <p>Presented at the 2026 Summer-of-Inquiry Symposium at Illinois State University.</p>
</figure>
