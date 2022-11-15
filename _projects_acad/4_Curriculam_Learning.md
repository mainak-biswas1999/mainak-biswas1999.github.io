---
title: "Safe RL with Curriculam Learning"
collection: projects_acad
type: "Safe Reinforcement Learning, student-teacher based RL"
permalink: /projects_acad/4_Curriculum_Learning
venue: "E1-277, RL, IISc"
date: 2022-04-01
location: None
---

Traditional reinforcement learning algorithms learn about a dangerous states only after the agent has been in such states enough to impact the value function. But learning for such algorithms become dangerous. For example, we don't want cars to learn to drive safely, only after it has met an accident. 

This introduces the idea of safe reinforcement learning. This is a student-teacher setting where, the teacher can guide the student, and prevent it from visiting potentially dangerous states. In this algorith the teacher can restore the student to a safe state when it goes to a potentially dangerous state. 
Soft penalties incurred in such cases help the student learn a good policy without the learning being dangerous.

This has been implemented in a dangerous gridworld setting [here](https://github.com/mainak-biswas1999/Academic_Projects/tree/main/Safe%20RL%20Curriculam%20Learning).