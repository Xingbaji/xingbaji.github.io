---
permalink: /
title: ""
excerpt: "About me"
layout: rpg-home
author_profile: false
redirect_from:
  - /about/
  - /about.html
rpg:
  name: "XING SHEN"
  job: "RESEARCHER"
  level: 32                            # current age (2026)
  portrait: "https://github.com/Xingbaji.png"
  hp:  { cur: 100, max: 100, percent: 100 }   # full health, no medical leave
  mp:  { cur:  80, max: 100, percent:  80 }   # mental bandwidth currently in use
  exp: { cur: 142, max: 365, percent:  39 }   # day-of-year progress toward LV 33
  stats:
    - { k: "PUB", v:   9, color: "blue"   }   # publications (count of _publications/)
    - { k: "CIT", v: 173, color: "red"    }   # citations (ResearchGate)
    - { k: "H-I", v:   4, color: "purple" }   # h-index (ResearchGate)
    - { k: "★",   v:  79, color: "gold"   }   # GitHub stars (Xingbaji, owner repos)
  skills:
    - { name: "Physics Simulation",    lv: 7, element: "fire"      }
    - { name: "Physics AI",            lv: 6, element: "lightning" }
    - { name: "Embodied AI",           lv: 3, element: "ice"       }   # new quest, just unlocked
    - { name: "Numerical Analysis",    lv: 5, element: "earth"     }   # PhD topic — mastery
  news:
    - { date: "2026-04", text: "<strong>MAS-PNCG</strong> on arXiv — Multilevel Preconditioned NCG for IPC, up to 5.66× speedup. <em>Preliminary version; an optimized release with substantially better performance is coming soon.</em> <a href='/publication/MAS-PNCG'>Read</a>." }
    - { date: "2026-04", text: "<strong>SIM1</strong> released — Physics-Aligned Simulator as Zero-Shot Data Scaler in Deformable Worlds. <a href='/publication/SIM1'>Project page</a>." }
    - { date: "2026-03", text: "<strong>Tac2Real</strong> on arXiv — reliable GPU visuotactile simulation for online RL & zero-shot real deployment. <a href='/publication/Tac2Real'>Read</a>." }
    - { date: "2025-12", text: "<strong>Sim2Real-CFM</strong> published in <em>Advanced Intelligent Systems</em>. <a href='/publication/Sim2Real-CFM'>Paper</a>." }
  menu:
    - { label: "PUBLICATIONS", url: "/publications/" }
    - { label: "CV",           url: "/cv/" }
    - { label: "CONTACT",      url: "/contact/" }
---

I got my PhD degree at the **Department of Mathematics, Zhejiang University**, advised by Prof. Xiaoliang Cheng in 2022.
Now I am a researcher at **Shanghai AI Lab**.

My main quests:

- Physics Simulation
- Physics AI
- Embodied AI
