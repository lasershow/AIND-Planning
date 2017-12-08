The planning we have learned so far is called classical planning.
Classical planning aims to generate a complete plan on the environmental model.

In recent years reactive planning, which overcomes classical planning, has been proposed. Classical planning generates a large amount of calculation cost. Especially in the robotics field to which planning is applied, the procedure of observation → modeling environment → planning → execution is necessary.

Furthermore, classical planning has a problem that it is necessary to assume that the generated plan is executed surely in the real world.
In the real world it is rare if the preconditions hold. Therefore, there is a case that execution of the action does not go well from this shift.

In other words, when classical planning is performed in a dynamic environment, it means that the execution of the action is not successful due to the difference between the assumed initial state and the actual initial state, or from the failure of the act itself .

Reactive planning is planning strongly aimed at achieving the objective in dynamic environment, real world.

Basically, the idea is that the agent does not need to conduct a huge search in the past in order to behave intelligently in the real world, and it is only necessary to perform fragment actions according to the environment of the place.

Reactive planning selects an action by using a conclusion part composed of directly executable fragmentary actions and a reactive rule described in a condition part directly determinable from the sensor output.

As a system for integrating these, subsumption architecture is conceivable. In this architecture, upper level suppresses lower level behavior. That is, lower hierarchies are more reflexive behavior. Tasks at each level are superior to conventional methods in terms of multiple purpose, robustness, and scalability, because they directly receive information from sensors and process in parallel.

In summary, this time I introduced classical planning, reactive planning, subsumption architecture. Taking these into the movement of a robot, it can be said that it is possible to solve the problem that requires a lot of time to construct an environmental model through classical planning, by reactive planning and to integrate quick response and contemplation by the inclusion architecture.

#### Sources
An investigation into reactive planning in complex domains.
RJ Firby - AAAI, 1987
https://ocs.aaai.org/Papers/AAAI/1987/AAAI87-036.pdf

Reactive reasoning and planning.
MP Georgeff, AL Lansky - AAAI, 1987
https://ocs.aaai.org/Papers/AAAI/1987/AAAI87-121.pdf

Real-time randomized path planning for robot navigation
J Bruce, M Veloso - Intelligent Robots and Systems, 2002. IEEE …, 2002 - ieeexplore.ieee.org
http://ieeexplore.ieee.org/abstract/document/1041624/
