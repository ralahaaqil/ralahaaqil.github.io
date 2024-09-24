---
title: "Course Recommender Model for People with Disabilities"
excerpt: "This project deals with a course recommendation model developed using reinforcement learning to improve the employability of people with disabilities.<br/><img src='/images/project1.jpg' width='50%'>"
collection: portfolio
---

The project entails the development of an environment in which an agent learns to recommend a course given a person's disability and academic profile. The input (state space) is a multi-discrete value with each term representing some form of an individuals profile (For example, it could be a disability type, the candidates qualifications and so on). The actions taken are a set of discrete courses that can be taken up by the individuals.

The agent receives a positive reward when it chooses a course (action) for an individual (state) that other candidates with similar profiles have taken up. This environment and reward function is structured using the OpenAI Gyms framework. This is then trained using a PPO algorithm offered by Stable Baselines 3.

The model provides pretty efficient results with the reward rising to a good high value before plateauing indicating sufficient learning from the agent's part. The explained variance trends towards 1 and the entropy coefficient towards 0 indicating that the model is not overfitting and works well. 

You can find the GitHub repository to the environment and reward function here: 
