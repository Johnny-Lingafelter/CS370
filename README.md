# CS370

Briefly explain the work that you did on this project: What code were you given? What code did you create yourself?
  
  For this project we were tasked with implementing a deep Q-learning algorithm using neural networks to solve a pathfinding problem. We were given a framework of Python code that set up the maze to be used and encapsulated the game experience to be used in the neural network as replays. The code we had to create ourselves was the actual definition of the neural network and the main loop that trained the agent using Q-learning. We saved each move the agent made as an episode, and then replayed the episodes in random order to adjust the Q-values of the network. We also adjusted hyperparameters such as the number of epochs and batch_size.

Connect your learning from throughout this course to the larger field of computer science:
  What do computer scientists do and why does it matter?
    Computer scientists solve problems
  How do I approach a problem as a computer scientist?
  What are my ethical responsibilities to the end user and the organization?
