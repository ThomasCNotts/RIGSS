# RIGSS
IGSS algorithms in R


This code implements an Inverse Generative Social Science project in R.

A target reference dataset is supplied as a vector--target--which is a distribution of a resource among agents.

The code will evolve a rule of the form:

IF condition THEN TAKE X resource

that all agents in an agent-based model will follow.

The ABM is implemented as a function. The code passes a rule to the funtions (a rule constructed to include a value for X).

The function returns a resource distribution. This is used to test that rule's fitness.
