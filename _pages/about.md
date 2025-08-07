---
layout: about
title: about
permalink: /
subtitle: <a href='#'>National University of Singapore</a>. yiqing[dot]xu[at]u[dot]nus[dot]edu

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>NUS School of Computing, COM1, 13, Computing Dr</p>
    <p>Singapore 117417</p>

news: false  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
selected_papers: true # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page
---

I'm Yiqing Xu, a CS Ph.D. candidate at the National University of Singapore, advised by Prof. [David Hsu](https://www.comp.nus.edu.sg/~dyhsu/). Previously, I obtained double degrees in Computer Science and Applied Mathematics from NUS.

I was a visiting Ph.D. student at MIT CSAIL, advised by Prof. [Leslie Kaelbling](https://people.csail.mit.edu/lpk/) and Prof. [Tomás Lozano-Pérez](https://people.csail.mit.edu/tlp/index.html) from September 2023 to February 2024.


<h2><a href="{{ '/publications/' | relative_url }}" style="color: inherit;">research highlights</a></h2>

My research focuses on *translating* human objectives into signals for robotic optimization. I develop *compositional and hierachical structures as intermediate representations* and design *reward learning algorithms* to better align robotic agents with human goals, especially when expert data is scarce or under-specified.

I've been working on algorithm research and theoretical analysis for inferring reward functions from limited data. My latest work, ["Set It Up!"](https://arxiv.org/abs/2405.11928), tackles the challenge of grounding under-specified instructions, such as "set up a Chinese dining table for two," in tabletop arrangement tasks. We introduce a neuro-symbolic framework that integrates semantic inference from large language models with geometric reasoning from pre-trained diffusion models of basic object relationships.

In my latest works, ["Set It Up" (IJRR)](https://arxiv.org/abs/2405.11928) and ["Stack It Up" (CoRL)](https://arxiv.org/abs/2508.02093), I explore how robots can act on human goals conveyed through ambiguous but intuitive inputs — like language commands or freehand sketches. Both works share a neuro-symbolic architecture that maps these inputs into *abstract relation graphs*, then grounds them into feasible physical configurations via *compositional diffusion models*. This approach preserves task structure, supports generalization, and learns from surprisingly few demonstrations by reusing local relational priors.

I’m excited to extend this framework in two directions. First, toward *flexible skill chaining* from mixed-modality input — combining coarse, abstract instructions with precise but partial demonstrations to infer symbolic task skeletons and modular reward functions that can be composed and optimized jointly. Second, toward *interactive multi-modal goal specification*, where robots engage with users via language, gaze, and motion to resolve ambiguity through active dialogue and inference. Across both directions, the goal remains the same: to make goal specification more expressive, adaptable, and aligned with how humans actually communicate intent.

If you'd like to chat more, feel free to email me!