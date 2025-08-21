# CS-370

**Pirate Intelligent Agent (Reinforcement Learning Project)**

  **Project Overview**
    This project implements a reinforcement learning agent designed to solve a pathfinding problem in a maze environment. The intelligent agent is modeled as a pirate searching for treasure, and it uses Q-learning with neural networks to learn an optimal policy for reaching the goal. 
    The repository includes a Jupyter Notebook that demonstrates the development and training of this agent. The notebook walks through defining the environment, building the model, training the agent with experience replay, and evaluating the results. 

  **Code Contributions**
    - **Provided Code:** I was given starter code that set up the maze environment, basic agent structure, and some initial scaffolding for reinforcement learning. This included definitions for the maze and utilities to visualize the environment.
    - **My Code:** I created the Q-learning training loop, integrated experience replay, implemented epsilon-greedy exploration vs. exploitatiom, and designed the neural network model for approximating Q-values. I also corrected technical issues such as training frequency, invalid action masking, and logging progress for evaluation.


  **Connecting Learning to Computer Science**

  **What Do Computer Scientists Do and Why Does It Matter?**
    Computer scientists develop algorithms, models, and systems that solve real-world problems. This matters because their work underpins modern technology - from recommendation systems to autonomous navigation. By applying reinforcement learning to a maze, I gained hands-on experience in how algorithms allow agents to "learn" optimal behaviors, which mirrors real-world applications like robotics, self-driving cars, and logistics optimization.

  **How Do I Approach a Problem as a Computer Scientist?**
    I approached this project by breaking the problem into smaller steps:
      1. Understand the environment (maze structure, rules, rewards).
      2. Define a learning algorithm suitable for the task (Q-learning with function approximation).
      3. Incrementally build and test components (model, replay memory, training loop).
      4. Refine the implementation based on feedback and observed performance. 
    This systematic approach mirros how computer scientists tackle complex problems - decomposing them into manageable parts and iteratively improving solutions.

  **Ethical Responsibilities**
    As a computer scientist, I have ethical responsibilities to both the end user and the organization. That includes:
      - **Transparency:** Making sure users understand how AI systems make decisions.
      - **Reliability:** Ensuring the system functions correctly and avoids harmful mistakes. 
      - **Fairneds and Privacy:** Protecting user data and avoiding bias in AI decision-making.
    In this project, while the stakes were low (a pirate finding treasure), the principles carry over to real-world applications where reinforcement learning agents could affect safety, privacy, and trust. 
