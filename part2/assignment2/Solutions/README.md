# Analysis of the algorithms

Both the Policy Iteration and the Value Iteration yield satisfactory results. However, upon examination of the solution text file, the Policy Iteration performs better than the Value Iteration.

This is evident from the fact that the error in solutions of the MDPs is larger for the Value Iteration algorithm than the Policy Iteration Algorithm.

This difference can be explained by the concepts founding both algorithms. Value Iteration only involves evaluating a policy and optimising it. However, Policy Iteration involves the additional step of improving the evaluated policy iteratively, by selecting a greedy action based on a true state value function.

This in turn improves the performance of the Policy Iteration algorithm.
