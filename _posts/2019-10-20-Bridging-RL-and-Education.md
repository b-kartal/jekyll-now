---
layout: post
title: Bridging RL and Education
categories: [blog, AI]
tags: [AI, general, RL]
---

In this post, I would like to brainstorm a few speculative ideas at the intersection of reinforcement learning (RL) and education fields. The plan for the post is as follows: (i) a brief background, (ii) some existing RL approaches that can be categorized at this intersection, and (iii) more open-ended discussion of what else can be done for better RL agents.

RL problem deals with trial-error based learning to maximize rewards for sequential decision making problems. Fundamentally different than supervised learning where training data/label is given, RL agents create their own training data (consisting of agent-environment interactions and rewards signals) as they interact with their environments. Mathematical formulation of RL abstracts away many components as the agent in the end aims to maximize rewards for the task hand.

One the other hand, education is defined as [the process of facilitating learning, or the acquisition of knowledge, skills, values, beliefs, and habits. Educational methods include storytelling, discussion, teaching, training, and directed research. Education frequently takes place under the guidance of educators, however learners may also educate themselves](https://en.wikipedia.org/wiki/Education). We can see that the definition of education provides several components that imply generalization naturally such as the notion of skills and habits.

RL has already borrowed many ideas from Psychology, e.g. consider the Pavlov's dog for classical conditioning. Given that Psychology and Education are fundamentally intertwined, we naturally see many concepts being shared across all these three fields. For example, for more efficient training, Curriculums are widely used in RL. For single-agent domains, the curriculum could be setup so that the agent is initially trained to do well on easier tasks, and then harder ones would be used. For multi-agent domains, an opponent or teammate curriculum could be used for better sample efficiency. Another related approach for RL is [Domain Randomization](https://lilianweng.github.io/lil-log/2019/05/05/domain-randomization.html), which helps agents to learn more robust policies with better generalization. As a father with kids at a daycare, every week I observe that the teachers randomize the game-stations in the classrooms. I think this helps the kids not get bored, but also it provides a diverse environment to explore and interact, and learn more skills without overfitting to static classrooms.

I am not aware of any research groups where RL and Education faculties actively collaborate, but I believe that there could be many concepts/perspectives that computer scientists could borrow from teachers/education experts. I think, quantitative researchers sometimes get lost in the depth of technical challenges and may forget the main goals of the field. More interdisciplinary research could potentially provide bigger breakthroughs.
