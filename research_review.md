In recent years reactive planning, which overcomes classical planning, has been proposed. Classical planning generates a large amount of calculation cost. Especially in the robotics field to which planning is applied, the procedure of observation → modeling environment → planning → execution is necessary.

Furthermore, classical planning has a problem that it is necessary to assume that the generated plan is executed surely in the real world.
In the real world it is rare if the preconditions hold. Therefore, there is a case that execution of the action does not go well from this shift.

Reactive planning is planning aimed at achieving the goal in the real world.

Unlike classical planning, Reactive planning selects an action as follows

Reactive planning selects an action by using a conclusion part composed of directly executable fragmentary actions and a reactive rule described in a condition part directly determinable from the sensor output

In summary, the emergence of reactive planning has significance in increasing the possibility of executing a plan even if a situation change occurs in the problem solved by AI.

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
