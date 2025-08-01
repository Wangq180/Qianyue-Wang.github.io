---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

## Pacemaker UI Interface

**Date:** Nov 2023  

This project involved the design and simulation of a **cardiac pacemaker user interface**, aimed at facilitating seamless interaction between users and pacemaker hardware. The primary goal was to create a medically reliable, accessible, and intuitive interface suitable for both patients and clinicians.

- Developed the UI front-end using Python (Tkinter + custom logic) for real-time control and visualization of pacemaker parameters such as pacing rate, amplitude, and sensing thresholds.
- Simulated pacemaker logic and response using **MATLAB**, including atrial and ventricular pacing signals under various heart conditions.
- Incorporated real-world constraints and compliance requirements drawn from medical standards such as ISO 14708 and FDA guidance.
- Collaborated with healthcare professionals and biomedical engineers to ensure the interface design met the practical needs in a clinical environment.
- The system includes adjustable pacing modes (AOO, VVI, DDD), alert systems, and waveform visualizations for educational and prototyping use.

The following video demonstrates one of the simulated pacing effects from the UI interface:

<iframe width="560" height="315"
  src="https://www.youtube.com/embed/pcIr2zrzdNA"
  title="Pacemaker UI Simulation"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
  allowfullscreen>
</iframe>

---
## 🎥 Object Tracking System (Jul 2024)

<p><strong>Institution:</strong> McMaster University<br>
<strong>Tools:</strong> Python (OpenCV), NumPy</p>

<p>This project involved building a <strong>real-time object tracking system</strong> that enables users to manually select a region of interest (ROI) on video frames and track the chosen object dynamically over time.</p>

<ul>
  <li>🖱️ Implemented a user-friendly interface using OpenCV to <strong>manually draw a bounding box</strong> around the object to be tracked in a live video feed or pre-recorded footage.</li>
  <li>🔍 Integrated multiple tracking algorithms such as <strong>CSRT</strong>, <strong>KCF</strong>, and <strong>MOSSE</strong>, with switchable backends for performance benchmarking.</li>
  <li>⚡ Achieved real-time tracking speeds on standard hardware, with frame-by-frame object localization and bounding box updates.</li>
  <li>🔁 Included a fallback mechanism for lost tracking, prompting user re-selection or automatic reinitialization.</li>
  <li>📊 Evaluated tracking accuracy under various conditions including occlusion, motion blur, and lighting changes.</li>
</ul>

<p><em>The tool can be extended for gesture recognition, surveillance systems, robotics, and human-computer interaction.</em></p>

<p><strong>Video Demo:</strong><br>
The following video demonstrates how the system tracks a user-selected object in real time:</p>



