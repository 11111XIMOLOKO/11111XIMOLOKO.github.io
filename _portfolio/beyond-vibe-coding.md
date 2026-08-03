---
title: "Beyond Vibe Coding: A Controlled Experiment in AI-Assisted Development"
excerpt: "After running into the unpredictability of AI-generated code in my research project, I followed the industry debate and came across SDD (Spec-Driven Development). I picked a self-contained web system as a sandbox — same spec, two runs: one by AI alone, one with human-AI collaboration. I just wanted to see if this approach could help me regain control over the code I was shipping."
collection: portfolio
link: "https://github.com/11111XIMOLOKO/beyond-vibe-coding"
---

Vibe Coding — prompting AI in natural language to generate code — comes with a hidden cost: fast builds, expensive maintenance. I designed a controlled experiment: the same SDD spec (Specs → Design → Tasks), two implementations — one by AI alone, one with human-AI collaboration. The only variable: **whether a human participated in iteration**.

**Result:** SDD solved the correctness problem, but experiential judgment still required human input. The methodology has since transferred to my diffusion model research.

**Tech stack:** Vue 3 + Spring Boot + MyBatis-Plus + Redis

**Key insights:**
- Writing clear requirements is itself a capability — the 60-task breakdown wasn't for the AI, it was for me
- AI is a copilot, not autopilot — the architecture, standards, and every round of UX judgment were mine
- The SDD workflow transferred directly to my diffusion model research project
