---
title: "Course Recommender Model for People with Disabilities"
excerpt: "This project deals with a course recommendation model developed using reinforcement learning to improve the employability of people with disabilities.<br/><img src='/images/project1.jpg' width='50%'>"
collection: portfolio
---

The project invloves the development of an environment in which an agent learns to recommend a course given a person's disability and academic profile. The input (state space) is a multi-discrete value with each term representing some form of an individuals profile (For example, the candidates disability type, qualifications and so on). The action taken is a discrete one chosen from a set of courses that can be taken up by the candidates.

The agent receives a positive reward when it chooses a course (action) for an individual (state) that other candidates with similar profiles have taken up. This environment and reward function is structured using the OpenAI Gyms framework. This is then trained using a PPO algorithm offered by Stable Baselines 3.

The model provides efficient results showing good trends with the episode reward mean, entropy coefficient and the explored variance with a stabilization in the clip fraction and approximated KL divergence.

You can find the GitHub repository to the environment and reward function here: 
