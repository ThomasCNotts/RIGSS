# RIGSS
IGSS algorithms in R


This code implements an Inverse Generative Social Science project in R (see: https://www.jasss.org/26/2/9.html).

The agent model here is a hawk-dove game.

A target reference dataset is supplied to the RIGSS program as a vector which is a distribution of a resource among agents.

The RIGSS program code will then evolve a rule of the form:

IF condition THEN TAKE X resource

that all agents in the agent-based model will follow.

The ABM is implemented as a function. The RIGSS program uses genetic programming to evolve rules. It passes each rule to the Agent Model funtion. That function then returns a resource distribution. This is used to test that rule's fitness.
