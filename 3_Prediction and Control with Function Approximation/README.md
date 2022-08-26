# [Prediction and Control with Function Approximation](https://www.coursera.org/learn/prediction-control-function-approximation)

## About this Course
In this course, you will learn how to solve problems with large, high-dimensional, and potentially infinite state spaces. You will see that estimating value functions can be cast as a supervised learning problem---function approximation---allowing you to build agents that carefully balance generalization and discrimination in order to maximize reward. We will begin this journey by investigating how our policy evaluation or prediction methods like Monte Carlo and TD can be extended to the function approximation setting. You will learn about feature construction techniques for RL, and representation learning via neural networks and backprop. We conclude this course with a deep-dive into policy gradient methods; a way to learn policies directly without learning a value function. In this course you will solve two continuous-state control tasks and investigate the benefits of policy gradient methods in a continuous-action environment. 

Prerequisites: This course strongly builds on the fundamentals of Courses 1 and 2, and learners should have completed these before starting this course.  Learners should also be comfortable with probabilities & expectations, basic linear algebra, basic calculus, Python 3.0 (at least 1 year), and  implementing algorithms from pseudocode.

By the end of this course, you will be able to: 

-Understand how to use supervised learning approaches to approximate value functions
-Understand objectives for prediction (value estimation) under function approximation
-Implement TD with function approximation (state aggregation), on an environment with an infinite state space (continuous state space)
-Understand fixed basis and neural network approaches to feature construction 
-Implement TD with neural network function approximation in a continuous state environment
-Understand new difficulties in exploration when moving to function approximation
-Contrast discounted problem formulations for control versus an average reward problem formulation
-Implement expected Sarsa and Q-learning with function approximation on a continuous state control task
-Understand objectives for directly estimating policies (policy gradient objectives)
-Implement a policy gradient method (called Actor-Critic) on a discrete state environment
