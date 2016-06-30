---
layout: post
title: "Quest Log 2: Exploring Simulation"
description: "Where no Kerbal has gone before"
category: simulation
tags: [programming, physics, simulation]
---
{% include JB/setup %}

I've created a new section on the site for simulation related
information.  I'll be moving a lot of the research text from my
personal notes and my
[Simulation](http://github.com:finger563/simulation) repository.  This
will be a continuation of my endevour to create realistic rendering
and simulation for solar-system level activities, in the vein of a
more realistic [Kerbal Space
Program](http://www.kerbalspaceprogram.com).  I've made some
atmosphere shaders, terrain tesselators, and other rendering programs
before, but I'm more interested now in developing a good interface
subsystem (with focus on extension/replacement/modding) for
interaction between the rendering, simulation, and networking
infrastructures needed for a good simulator.  I'll be continuing my
research into / development of a projective-grid based approach for
rendering to (hopefully) for the rendering side of things, while
learning [FLEX](http://developer.nvidia.com/flex) for integration of
physics simulation.  I'm quite interested to see what the process
looks like for the new asynchronous APIs for GPUs (e.g. DX12) and how
a rendering subsystem can work cooperatively (sharing resources) with
the physics system.