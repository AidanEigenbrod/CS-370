# CS-370
## Project Overview

In this project, I created a pirate intelligent agent that learns how to navigate a maze in order to find a hidden treasure. The main artifact for this submission is a Jupyter Notebook that demonstrates how reinforcement learning and neural networks can be applied to a problem where an agent must learn from experience rather than being explicitly told what to do.

Some of the code for this project was provided as a starting point. This included the TreasureMaze class, which defines the maze layout, the available movements, how rewards and penalties are assigned, and how the game determines whether the agent has won or lost. This code handled the environment and ensured that the agent interacted with the maze in a consistent way.

The code I developed focused on the intelligence of the agent itself. I implemented deep Q learning using a neural network to help the agent predict the best action to take in each state. I also worked with experience replay so the agent could learn from past actions, rather than only its most recent move. An epsilon greedy strategy was used to balance exploration and exploitation, allowing the agent to explore the maze early on and gradually rely more on learned behavior as training progressed. A target network was also used to help stabilize learning over time.

## Connection to Computer Science

This project connects closely to the broader field of computer science because it highlights how complex problems can be solved through abstraction, modeling, and iterative improvement. Computer scientists build systems that can make decisions, adapt to new information, and operate effectively even when there is no clear step by step solution. This project is a good example of that approach, since the agent was required to learn how to solve the maze through repeated interaction with its environment.

Throughout this course, I learned to approach problems by breaking them down into manageable components, selecting appropriate algorithms, and testing solutions through experimentation. Reinforcement learning demonstrates how powerful this approach can be, especially in situations where traditional rule based logic would be difficult or inefficient to implement.

Ethical responsibility is also an important consideration when developing intelligent systems. As a computer scientist, it is important to design systems that behave safely, predictably, and in ways that align with user expectations. This includes creating reward structures that do not encourage harmful behavior and ensuring that learning systems can be trusted by both users and organizations. Thoughtful design and testing help reduce unintended consequences and improve reliability.

## Conclusion

Overall, this project helped reinforce my understanding of reinforcement learning and neural networks while giving me hands on experience building an intelligent agent. It serves as a strong portfolio example of my ability to apply computer science concepts to real problems and reflect on both the technical and ethical aspects of system design.
