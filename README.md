# Text-Based-Game-with-Markov-Decision-Process
MITx - MicroMasters Program on Statistics and Data Science - Machine Learning with Python

Fifth Project - Tex-Based Game with Markov Decision Processes

The fifth and final project of the MIT MicroMasters Program course on Machine Learning with Python was to create
a game based on Reinforcement Learning (RL), Neural Networks (NN) and Markov Decision Processes (MDP).

The aim was to create a RL based model where the agent of the game learns by conducting certain actions in an environment mimicing
that of a typical house that consists four rooms - a living room, a bed room, a kitchen and a garden with connecting path ways.
Inside each room there are different quests and the goal of the game is to navigate through the different rooms and
complete each quest in order to finish the game.

In a MDP an agent earns rewards or points by taking the right action in order to complete a quest and looses them by taking the wrong one.
Each navigation step from a room to another and taking an action consume points. The agent thus gets feedback from its actions from which
it learns the right policy (i.e. set of steps and actions) in order to complete the game with the maximum amount of rewards.

The project first required to implement a tabular Q-learning algorithm for a simple setting where each text description is associated with
a unique index. The next task was to implement the Q-learning algorithm with linear approximation architecture by using bag-of-words
representation for textual state description. Finally, the last task was to implement a deep Q-work based on NN and use the Q-learning
algorithms inside the game.

Additional helper functions were given to complete the project in two weeks of time.
