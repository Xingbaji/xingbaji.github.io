---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
- **2012-2016** Xiamen University, Computational Mathematics
- **2016-2022** Zhejiang University, Computational Mathematics

Experience
======
- **Jul 2022-2025** **NetEase Fuxi (网易伏羲)**, Game AI / Physics Simulation Algorithm Engineer
  - Developed real-time soft-body simulation for game characters using LBS-subspace skeletons and subspace Projective Dynamics with collision, achieving **over 200 FPS on CPU**; an MLP accelerator reduced per-frame cost to **under 1 ms**.
  - Built controllable, collision-aware motion-generation methods for non-humanoid characters, including modal animation, automatic LBS rigging, and actuation-energy optimization coupled with elastic energy.
  - Implemented GPU-parallel contact solvers for interactive simulation: **PNCG-IPC** in Taichi and NVIDIA Warp (*SIGGRAPH 2024*) and **MAS-PNCG** in C++/CUDA, delivering **over 3× speedup over prior state of the art**.
  - Developed MPM-based excavator-soil/rock interaction simulation and Sim2Real techniques for intelligent excavator control.

Publications
======
{% for post in site.publications %}
  {% include archive-single-cv.html %}
{% endfor %}
