# CS-370-Project-Two
Project Overview

In this project, I implemented a Deep Q-Learning agent that learns to navigate an 8×8 maze to retrieve a treasure. The pirate begins in the top-left corner and must learn an optimal path while avoiding penalties for invalid or inefficient moves.

Code Provided

The starter code included:

The TreasureMaze environment with maze layout, reward system, and game logic

The GameExperience class for experience replay

A neural network model built with Keras

Utility functions for validation and visualization

These components defined the environment and infrastructure but did not include the training algorithm.

Code I Developed

I implemented the Q-training algorithm in the Jupyter Notebook. My work included:

Creating the Deep Q-Learning training loop

Implementing epsilon-greedy exploration

Using experience replay to train the model

Updating a target network for stability

Tracking win rate and stopping training once the agent consistently won

The final agent reliably learned to reach the treasure.

What Do Computer Scientists Do and Why Does It Matter?

Computer scientists design algorithms and systems that solve complex problems efficiently. This project demonstrated how reinforcement learning can enable systems to learn optimal behavior through experience. Applications of similar techniques include robotics, automation, and intelligent decision-making systems.

How I Approach Problems as a Computer Scientist

I approached this problem by:

Understanding the environment and constraints

Breaking the task into smaller components (state, action, reward, learning)

Implementing and testing iteratively

Debugging and refining the solution

This structured, iterative approach is essential when working with complex systems.

Ethical Responsibilities

As a developer of intelligent systems, I have responsibilities to:

Ensure systems are reliable and thoroughly tested

Design reward structures carefully to avoid unintended behaviors

Maintain transparency and accountability

Consider the impact of AI systems on users and organizations

Careful validation and responsible design are critical when deploying learning systems.

Reflection

This project strengthened my understanding of reinforcement learning, neural networks, and experience replay. It demonstrated how theoretical concepts can be applied to create an intelligent, functioning system. Watching the pirate consistently reach the treasure showed how learning from interaction can produce optimal behavior over time.
