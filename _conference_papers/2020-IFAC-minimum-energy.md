---
title: "A Minimum Energy Filter for Distributed Multirobot Localisation"
collection: conference_papers
permalink: /publication/2020-IFAC-Minimum-Energy-Multirobot
excerpt: ''
published: 'in_review'
date: 2020-7-12
venue: '21st IFAC World Congress'
paperurl: '#'
citation: # 'Henderson, J., Trumpf J., Zamani, M. (2020). &quot;A Minimum Energy Filter for Distributed Multirobot Localisation&quot; <i>21st IFAC World Congress</i>.'
abstract: 'We present a new approach to the cooperative localisation problem by applying the theory of minimum energy filtering. We consider the problem of estimating the pose of a group of mobile robots in an environment where robots can perceive fixed landmark and neighbouring robots as well as share information with others over a communications channel. Whereas the vast majority of the existing literature applies some variant of a Kalman Filter, we derive a set of filter equations for the global state estimate based on the principle of minimum energy. We show how the filter equations can be decoupled and the calculations distributed among the robots in the network without requiring a central processing node. Finally, we provide a demonstration of the filter in simulation.'
---
Currently under review.

## Simulation Code
The code used to run the simulations presented in the paper is available [here](/files/filtering-testbench-2019-10-25.zip).
Follow the instructions in the README file to get started. The exact simulation from the paper is located at ``/src/tests/simulations/IFAC2020/ascc_comparison.py``.
