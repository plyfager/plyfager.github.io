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
* **Ph.D. in Computer Science**, Singapore Management University (SMU), 2023.08 - Present
  * Advisor: Prof. He Shengfeng
  * Research Interests: Motion Synthesis, World Models, Generation Models
* **M.S. in Mathematics**, Shandong University (SDU), 2018.09 - 2021.06
* **B.S. in Computer Science**, East China Normal University (ECNU), 2014.09 - 2018.06

Work Experience
======
* **Shanghai Artificial Intelligence Lab** — Research Engineer, 2021.07 - 2023.07
  * Led the development of MMGeneration and participated in MMEditing (now MMagic), contributing over 60k lines of code to the OpenMMLab ecosystem.
  * Implemented and optimized large-scale diffusion pipelines, including Stable Diffusion, ControlNet, and customized motion modules.
  * Participated in the design and development of MMEngine, focusing on Config and Data Transform modules.

* **SenseTime** — Research Intern, 2021.01 - 2021.06
  * Developed the MMGeneration framework from scratch, integrating 20+ state-of-the-art GAN algorithms (e.g., StyleGAN, BigGAN).

* **TruthEye** — Research Intern, 2019.09 - 2020.04
  * Researched generative models and unsupervised anomaly detection for industrial vision.

Project & Research Experience
======
* **OpenMMLab Framework: MMGeneration & MMagic**, 2021.01 - 2023.07
  * Managed and developed MMGeneration (2k Stars) from scratch; Participated in MMEditing (7.4k Stars) and its successor MMagic (7.4k Stars).
  * Designed development standards for diffusion models in MMagic. Implemented Guided-Diffusion, DDIM, Disco-Diffusion, and supported Stable-Diffusion.
  * Implemented comprehensive evaluation metrics (IS, FID, PPL, SWD, etc.) for generative tasks.

* **Research on Motion Generation and World Models**, 2023.08 - Present
  * Exploring World Models for interactive motion generation.
  * Researching physical regularity and long-term consistency in generative models to ensure plausible motion and video dynamics.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Honors & Awards
======
* Fancy Idea Award, Alibaba-Tsinghua Security AI Challenger Program Phase IV, 2021
* 8/953, ZhengTu Machine Vision AI Competition (Industrial Defect Detection), 2020

Skills
======
* **Research**: Motion Synthesis, World Models, Generation Models
* **Languages**: English (IELTS 6.5, GRE 314), Mandarin (Native)
