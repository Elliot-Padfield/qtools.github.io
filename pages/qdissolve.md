---
title: QDissolve
layout: default
parent: QTools
nav_order: 1
---


# QDissolve

![QDissolve header]({{ site.baseurl }}/assets/qdissolve/qdissolveheader.svg)

A lightweight dissolve shader for Unity with clear controls and no setup overhead.

QDissolve provides a simple, production-ready dissolve effect designed for VFX, gameplay feedback, and prototyping. It focuses on predictable behaviour and clean parameters rather than feature bloat.

## What it does

- Dissolve meshes using noise or masks  
- Supports 2D and 3D  
- Works across Unity render pipelines  
- Designed to be driven from shaders or simple scripts  

## Key features

- Single dissolve control value  
- Directional or position-based dissolves  
- Optional edge glow  
- No custom scripts required  
- Sensible defaults out of the box  

## Typical use cases

- Enemy spawn and despawn  
- Object destruction  
- Teleport effects  
- Gameplay feedback  
- Prototyping VFX without VFX Graph  

## How to use

1. Assign the QDissolve material to your object  
2. Adjust the dissolve value from 0 → 1  
3. Optional: tweak direction, noise, and edge settings  

That’s it.

## Parameters

- **Dissolve**  
  Controls how much of the object is dissolved

- **Noise / Mask**  
  Defines the dissolve pattern

- **Direction / Position**  
  Controls how the dissolve progresses through space

- **Edge Width / Colour**  
  Optional visual highlight on the dissolve boundary

## Compatibility

- Built-in Render Pipeline  
- URP  
- HDRP  

## Links

- Unity Asset Store  
- GitHub  

---

Minimal by design.
