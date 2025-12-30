# Joint-Space Trajectory Planning & Control for a Robotic Arm (PyBullet)

### End-to-end Demonstration Project of PD control, feedforward, trajectory planning, and reinforcement learning. 
_Created for use by Stanford Robotics Club onboarding._

This module introduces real-world robotic arm motion control through simulation. This includes planning smooth joint trajectories, tracking them using feedback control, compensating for physical concepts like intertia and gravity, and diagnosing results and performance using logs

------

**1 - Systems overview**
Robotic motion in this project can largely be modeled as a 3 interacting components: 

> **Trajectory Planner:** Where should the joint be at a specific moment of time (t) during motion? Produces desired position q_des(t) and desired velocity qd_des(t)

> **Controller:** Given where I want to be and where I am, what torque should I apply? Uses the error at a given timestep and physics-aware reasoning.

> **Robot Physics:** Simulates movement and handles inertia, gravity, joint limits, dynamics, e.c.t to emulate a real 6 DOF robotic arm.




2. 
