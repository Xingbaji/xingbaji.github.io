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
- **2025-Present** **RealSim2Real**, Researcher — Physics Simulation / Embodied AI / Sim2Real
  - Developed **SIM1**, a physics-aligned simulator for deformable manipulation that scales 200 human demonstrations into over 10,000 synthetic trajectories; policies trained entirely on synthetic data achieve **90% zero-shot success** on real robots.
  - Developed **Tac2Real**, a reliable multi-GPU visuotactile simulation framework with **TacAlign** for online reinforcement learning, enabling zero-shot Sim2Real transfer on robotic peg insertion.
  - Researched soft-robotic **Sim2Real via conditional flow matching**, reducing the simulation-to-reality gap on tensile and fin-ray gripping benchmarks.

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
