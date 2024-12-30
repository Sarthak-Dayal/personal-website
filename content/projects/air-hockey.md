+++
title="air-hockey"
+++

## Robot Air Hockey

We built an Air Hockey setup that allowed for the assessment of various RL capabilities and published [a paper](https://arxiv.org/pdf/2405.03113) that was accepted at the ICRA 2024 Manipulation Skills workshop!

<iframe width="560" height="315" src="https://rlairhockey.github.io/static/videos/TeaserRobotAirHockey.mp4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

We built a setup that included:
A tilted Air Hockey table with a puck and paddle held by a UR5e end effector
Many tasks such as location reaching, puck touching, and puck hitting
A computer vision system that allowed training on the robot from state
Multiple teleoperation systems to control the physical robot
Two simulated environments in Robosuite (3D) and Box2D
Reward designs and sim-to-real pipelines for almost all tasks

I worked on many parts of this project, from training RL algorithms to showcase our setup, building a mouse-based teleoperation system, collecting human hitting data, customizing task environments and simulations, and more.

This was a really exciting experience because it was one of my first experiences with robotics and my first experience with Reinforcement Learning, but I was able to both learn as well as contribute a lot to the project.

For more details on our setup, refer to the [project website](https://rlairhockey.github.io)!

