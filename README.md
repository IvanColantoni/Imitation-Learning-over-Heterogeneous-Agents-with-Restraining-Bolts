# Imitation-Learning-over-Heterogeneous-Agents-with-Restraining-Bolts
A common problem in Reinforcement Learning (RL) is that
the reward function is hard to express. This can be overcome
by resorting to Inverse Reinforcement Learning (IRL), which
consists in first obtaining a reward function from a set of execution traces generated by an expert agent, and then making
the learning agent learn the expert’s behavior –this is known
as Imitation Learning (IL). Typical IRL solutions rely on a
numerical representation of the reward function, which raises
problems related to the adopted optimization procedures.
We describe an IL method where the execution traces generated by the expert agent, possibly via planning, are used to
produce a logical (as opposed to numerical) specification of
the reward function, to be incorporated into a device known as
Restraining Bolt (RB). The RB can be attached to the learning agent to drive the learning process and ultimately make
it imitate the expert. We show that IL can be applied to heterogeneous agents, with the expert, the learner and the RB
using different representations of the environment’s actions
and states, without specifying mappings among their representations.
