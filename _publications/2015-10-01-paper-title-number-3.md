---
title: "A Multi-Objective Reinforcement Learning Framework for UAV Path Planning Automation in Complex Fire and Rescue Environments"
collection: publications
category: manuscripts
permalink: /publication/2024-01-20-uav-path-planning
excerpt: '**Yanming Chen**, Saeid Pourroostaei Ardakani'
date: 2024-8-20
venue: 'IEEE Transactions on Vehicular Technology (Under Review)'
paperurl: '/files/FAR-UAV-2024.pdf'
---

### **Abstract**
Fire and rescue UAVs employ AI methods to automate navigation over fire zones to detect and extinguish fire flames and/or rescue fire-trapped lives through low-cost and collision-free flight routes. This paper introduces a reinforcement learning framework that allows UAVs to detect and prioritize fire-trapped targets based on their risk levels. It establishes three simultaneous objectives including maximized power conservation, rescue success rate, and flight safety to plan fire and rescue operations in complex environments where field size, the number of trapped targets, and fire source count vary. An extensive empirical evaluation is conducted to test and evaluate the performance of the proposal against three well-known benchmarks including Double Deep Q-network, Advantage Actor-Critic, and Genetic Algorithm. The results demonstrate that the proposed solution outperforms the benchmarks in most circumstances especially when the fire and rescue environment is large and complex.

### **Key Contributions**
- Propose a novel reinforcement learning framework that enables UAVs to dynamically adjust their routes in response to the risk levels of fire-trapped targets within complex fire environments where the number of targets, fire sources, and field dimensions vary.
- Develop a Q-learning route planning solution that simultaneously targets multiple fire and rescue objectives, including maximizing flight energy efficiency, minimizing the risk of fire/obstacle collisions, and maximizing rescue success rates while managing the inherent trade-offs among them.
- Conduct a rigorous approach to experiment design and an extensive empirical analysis to evaluate the performance of the proposed solution against three well-known AI benchmarks, including Double Deep Q-network (DDQN), Advantage Actor-Critic (A2C), and Genetic Algorithm (GA).

For more details, download the [paper here](UAVPathPlanning.pdf).