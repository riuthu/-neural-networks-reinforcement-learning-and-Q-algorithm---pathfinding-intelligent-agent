# -neural-networks-reinforcement-learning-and-Q-algorithm---pathfinding-intelligent-agent
 Code for a pathfinding intelligent agent; specifically,  code for a pirate non-player character (NPC) that is part of a larger treasure hunt video game.

What code was I given? What code did I create yourself?
For this project, the course provided two complete python files and a partially completed Jupyter notebook. I created the core training loop inside qtrain(). This included resetting the environment to a random free cell each epoch, observing the initial state, running the episode loop with epsilon greedy action selection, masking invalid actions during exploitation, storing transitions in the replay buffer using experience.remember(), training the neural network at each step using experience.get_data() and train_step(), periodically syncing the target network weights, computing the rolling win rate, and implementing early stopping using completion_check().

What do computer scientists do and why does it matter?
Computer scientists solve problems by designing systems that can process information, make decisions, and automate tasks that would otherwise require significant human time and effort. At the core of the work is algorithmic thinking and breaking a complex problem down into steps a machine can execute reliably. Equipped with the problem solving, computer scientists build the tools and systems that other fields depend on. 

How do I approach a problem as a computer scientist?
My approach starts with understanding the problem before writing any code. For this project, that meant reading through TreasureMaze.py and GameExperience.py carefully to understand how the environment worked, what methods were available, and what inputs and outputs each method expected. Only after that did I start filling in the training loop, because the pseudocode provided made much more sense once I understood the underlying classes.

What are my ethical responsibilities to the end user and the organization?
My ethical responsibilities begin with honesty and transparency. The users relying on that system deserve to understand how it works, what its limitations are, and under what conditions it might fail. As a computer scientist, I have a responsibility to build systems that are reliable, fair, and do not cause unintended harm. This means writing maintainable code, documenting assumptions, and flagging known weaknesses. For the end user, it means not overstating what a system can do and ensuring the system behaves predictably in the conditions it will encounter. 
