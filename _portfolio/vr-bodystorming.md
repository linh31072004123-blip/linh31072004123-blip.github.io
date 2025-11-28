---
title: "VR Bodystorming"
excerpt: >
  A VR tool for spatial ideation, choreography, room composition, lighting design,
  and embodied sketching — built to explore how immersive tools shape participation
  and creativity.
  <br /><img src="/images/thumbnail.PNG" />

collection: portfolio
permalink: /portfolio/vr-bodystorming/
date: 2025-11
image:
  path: /images/vr-bodystormingthumbnail.jpg
  alt: "VR Bodystorming in VR"
---

## Overview  
**VR Bodystorming** is an immersive ideation tool designed to help teams explore, prototype, and communicate design ideas using their bodies inside a shared virtual environment. Inspired by **TiltBrush**, this project enables users to **move, sketch, choreograph, manipulate space, and experiment with lighting** inside VR.

The system supports two major modes:

- **Choreographer Mode** — capture, visualize, and replay full-body motion trajectories over time.  
- **Room Composition Mode** — design spaces by placing props, shaping light, and sketching in 3D.

This project was developed using **Unity (OpenXR)**, custom tool systems, gesture-based interactions, and a VR-specific UI designed from scratch.

---

## 🎥 Project Demo  

**Watch a short introduction video:**  

<video width="100%" controls>
  <source src="/files/vrbodystorming-demo.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

---

## 📸 Setup and Experiment  

<div style="display: flex; flex-wrap: wrap; gap: 12px; margin-top: 16px;">
  <img src="/images/vrb_1.jpg" alt="VR Bodystorming Screenshot 1" style="width: 48%; border-radius: 10px;" />
  <img src="/images/vrb_2.jpg" alt="VR Bodystorming Screenshot 2" style="width: 48%; border-radius: 10px;" />
  <img src="/images/vrb_3.jpg" alt="VR Bodystorming Screenshot 3" style="width: 48%; border-radius: 10px;" />
  <img src="/images/vr-bodystormingthumbnail.jpg" alt="VR Bodystorming Screenshot 4" style="width: 48%; border-radius: 10px;" />
</div>

---

## ⭐ Key Features

- **Full-Body Motion Capture & Playback**  
  Hierarchical skeleton tracking that records body movement with timestamps, enabling accurate, time-aligned playback for choreography, motion studies, and spatial ideation.

- **Embodied Sketching & Brush System**  
  VR sketching tools with stroke constraints (freehand, line, circle, sinus), smoothing, collision-based erasing, and automatic LineRenderer generation.

- **Room Composition Toolkit**  
  Place, rotate, scale, and preview VR-ready props; resize room dimensions; switch wall materials; experiment with layouts in real time.

- **Lighting Design Studio**  
  Interactive lighting tools including point lights, spotlights, and line lights with adjustable brightness, color, range, and dynamic behaviors.

- **Modular Tool Management System**  
  ScriptableObject-based architecture for switching tools (brush, eraser, material picker, color picker) seamlessly and scalable for future extensions.

- **VR-Native UI & Icon System**  
  Wrist-rotation menu switching, large icons with state indicators, hover effects, simplified navigation inspired by Tilt Brush ergonomics.

- **AI-Assisted Prop Modeling Pipeline**  
  Hybrid workflow combining Gemini, Google Whisk, Tripo, Meshy, and Blender refinement to generate consistent, stylized 3D assets.

- **Multi-Layer Spatial Grid System**  
  Grid snapping, multi-layer detail grids, ghost previews, and dynamic feedback layers for precise object placement and spatial planning.

---

## 🎯 Impact

This project deepened my understanding of **how immersive tools shape participation, agency, and collaborative creativity**:

- Showed how **embodied interaction** and full-body motion tracing help users generate more intuitive spatial ideas.  
- Highlighted the importance of **VR ergonomics**—menu placement, icon size, interaction timing—in supporting equitable participation.  
- Strengthened my ability to design **scalable VR systems**, from motion pipelines to tool managers and UI frameworks.  
- Demonstrated the potential of **AI-assisted 3D modeling** to accelerate early creative iteration while still requiring human refinement.  

Overall, VR Bodystorming taught me how technical interaction design—motion capture, spatial UI, and tool switching—directly affects **who contributes, how ideas evolve, and what creativity looks like** inside immersive environments.
