---
layout: single
author_profile: true
---      

---
### Safe Motion Planning with Control Barrier Functions

Motivated by the difficulty of designing controllers with safety and stability guarantees, here we combine these controllers with sampling-based motion planning algorithms, 
which provide high-level motion plans that the low-level CBF-based controllers follow.

---
### Uncertainty Quantification for Safe Control

In this line of work we leverage different techniques such as Distributionally Robust Optimization or Gaussian Process Regression to quantify the model uncertainty often encountered in real-world applications of safety critical control. 
We also develop ways to integrate such uncertainty quantifiers in the control design pipeline while still retaining the safety and computational efficiency guarantees.

---
### Distributed Safe Control Design

Here we propose a distributed controller synthesis framework for safe navigation of multi-agent systems.
We leverage control barrier functions to formulate collision avoidance with obstacles and teammates as constraints on the
control input for a state-dependent network optimization problem
that encodes team formation and the navigation task.

---

### Fundamental Theoretical Properties of Control Barrier Functions

Safety refers to the ability to ensure by design that the evolution of the dynamics stays within a desired set. Control Barrier Functions (CBFs) are a popular tool to design safe controllers in a computationally efficient manner. 
We have studied a variety of different fundamental theoretical properties of CBF-based controllers, such as:

-Converse and Existence results for Safety and Stability

-Integration of CBFs with stable controllers

-Regularity Properties of CBF-based controllers

-Independence of Dynamical Properties on the Choice of CBF

---

### Mathematical Modelling of Epidemics

The COVID-19 pandemic has stressed out the importance of having accurate, interpretable and robust models for the spread of an infectious disease in a population. In this work we build on well-established compartmental models for epidemic spread and include some of the features of the COVID-19 pandemic, like the existence of massive testing capabilities or the presence of wastewater detection plants. The result is a model which is partially tractable analytically and with interpretable parameters which can be used to design control policies to mitigate the spread of the disease. 

---

### Event-triggered Discretizations of Optimization Flows

Recent interest in first-order optimization algorithms has lead to the formulation of so-called high-resolution differential equations, continuous surrogates for some of the classical discrete-time optimization algorithms exhibiting acceleration. The continuous setting allows the use of some powerful and well-established tools, like Lyapunov functions. This framework can be used to gain some intuition into the still somewhat mysterious phenomenon of acceleration. In this work we study these high-resolution differential equations and the crucial problem of re-discretizing them while maintaining their rate of convergence. We also review a recent paper that proposes a discretization technique by using ideas borrowed from event-triggered control and suggest some improvements on those algorithms in terms of their rate of convergence. 

---

