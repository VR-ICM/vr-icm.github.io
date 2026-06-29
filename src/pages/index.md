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
- Where is the adoption barrier: hardware, software workflow, or content authoring?

[Read more about the research areas.](/research/)

## Current Status

**Implemented**

- Prototype VR environment for viewing and interacting with building models
- Expandable, interactive wall and floor elements

**Top of mind**

- HUD display for metadata information

**Next steps**

- Loading Datasmith exports at runtime instead of in-editor

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
  <h3>Simulation prototype</h3>
  <p>Short caption for a VR walkthrough, interaction demo, or model inspection clip.</p>
</figure>

<figure>
  <h3>CAD-to-simulation workflow</h3>
  <p>Short caption for a flowchart showing how building data enters the environment.</p>
</figure>
