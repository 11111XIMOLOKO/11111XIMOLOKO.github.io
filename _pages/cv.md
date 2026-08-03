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
* B.S. in Computer Science and Technology, Jiangxi Normal University, 2023–2027 (expected)
  * Ranking: 2/91 (comprehensive) · 4/91 (GPA)
  * CET-6: 479

Research Projects
======
* **Diffusion-based Industrial Defect Detection & Repair Pipeline** (Ongoing)
  * Five-module full-stack pipeline: anomaly detection → fake defect generation → ControlNet training → DDIM-Blending inference → evaluation
  * ~2000 lines of self-written Python, all modules built from scratch

* **Beyond Vibe Coding: AI-Assisted Development Controlled Experiment** (Completed)
  * Designed and executed a controlled experiment comparing pure SDD generation vs. human-AI collaboration
  * Full-stack implementation: Vue 3 + Spring Boot + MyBatis-Plus + Redis
  * 55+ tasks implemented across both experiment arms, with documented comparative results

Honors & Awards
======
* **Competitions (5 National + 4 Provincial)**
  * iCAN Innovation Contest — National 1st Prize
  * CUMCM — National 2nd Prize
  * MCM/ICM — Meritorious Winner (Top 7%)
  * Global Campus AI Algorithm Competition — National 3rd Prize
  * Digital Media Technology Competition — National 3rd Prize
  * Computer System Capability Competition — Provincial 1st Prize
  * Computer Design Competition — Provincial 2nd Prize
  * NCDA — Provincial 2nd Prize
  * Datang Cup — Provincial 2nd Prize

* **Scholarships & Campus Honors**
  * First-class Comprehensive Scholarship (2023–2024, 2024–2025)
  * University-level Merit Student (2023–2024, 2024–2025)
  * Civilized University Student (2024)
  * Outstanding Student Leader (2025)
  * Outstanding Communist Youth League Member (2025)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Skills
======
* **Languages:** Python (primary), C++, Java, TypeScript
* **DL Frameworks:** PyTorch, Diffusers, HuggingFace
* **Web:** Vue 3, Spring Boot, MySQL, Redis
* **Tools:** Git, LaTeX, Linux, Docker
