---
layout: about
title: about
permalink: /
subtitle: Postdoctoral Scholar<br><a href='https://www.cs.stanford.edu/'>Stanford University</a><br>yiqingx[at]stanford[dot]edu

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Gates Computer Science Building, Room 234</p>
    <p>353 Jane Stanford Way, Stanford, CA 94305</p>

news: true  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
selected_papers: true # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page
---

I'm Yiqing Xu, a Postdoctoral Scholar in Computer Science at Stanford University, working with Prof. [Jiajun Wu](https://jiajunwu.com/). I received my Ph.D. in Computer Science from the National University of Singapore in 2026, advised by Prof. [David Hsu](https://www.comp.nus.edu.sg/~dyhsu/). Before that, I obtained double degrees in Computer Science and Applied Mathematics from NUS.

During my Ph.D., I was a research intern with the Robotics team at the Allen Institute for Artificial Intelligence (AI2), working with Prof. [Dieter Fox](https://homes.cs.washington.edu/~fox/) (Nov 2025 – May 2026), and a visiting Ph.D. student at MIT CSAIL, advised by Prof. [Leslie Kaelbling](https://people.csail.mit.edu/lpk/) and Prof. [Tomás Lozano-Pérez](https://people.csail.mit.edu/tlp/index.html) (Sep 2023 – Feb 2024).


<h2><a href="{{ '/publications/' | relative_url }}" style="color: inherit;">research highlights</a></h2>

My research focuses on *translating* human objectives into signals robots can reliably act on. I develop *compositional and hierarchical abstractions as intermediate representations* between how people express intent and how robot policies, from specialized models to generalist VLAs, execute it, and design learning and inference methods that align robotic agents with human goals.

My work is organized around a common **abstraction-and-composition** principle: recover task structure implicit in human input, represent it explicitly, and use that structure to guide robot behavior. In ["Set It Up" (IJRR 2025)](https://arxiv.org/abs/2508.02068) and ["Stack It Up" (CoRL 2025 Oral)](https://arxiv.org/abs/2508.02093), I map under-specified language and sketches into relational abstractions, then compose learned local models to generate feasible physical configurations.

My current work extends this idea to generalist robot policies. In ["The Human–VLA Communication Gap"](https://anonymous.4open.science/r/supp-materials-2027-F221/full_paper_appendix.pdf) (under review), we characterize the mismatch between how people naturally express objectives and the executable structure VLAs require: humans increasingly compress task semantics and event structure as tasks grow, while VLAs are especially sensitive to missing semantics, undecomposed events, and how resolved commands are invoked. This motivates my current work on **structured and programmatic interfaces** that recover task structure before execution, together with **explicit concept memory**, **compositional skill chaining**, and **adaptive planning** ([APIVOT, NeurIPS 2026](https://arxiv.org/abs/2607.08024)) and **policy steering** ([VLS, CoRL 2026](https://arxiv.org/abs/2602.03973)).

Looking ahead, I aim to extend this framework in two directions. First, toward **mixed-modality goal specifications**, combining coarse, abstract instructions with precise but partial demonstrations to infer symbolic task skeletons and modular reward functions that can be composed and optimized jointly. Second, toward **interactive goal specification interfaces**, where robots engage with users via language, gaze, and motion to resolve ambiguity through active dialogue and inference, asking about the structure that is genuinely costly to guess rather than what the scene already disambiguates. Across both, the goal remains the same: generalist robots should adapt to how people actually communicate intent, rather than requiring people to adapt to the robot.

If you'd like to chat more, feel free to email me!
