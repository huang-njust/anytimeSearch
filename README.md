# An Anytime A* search algorithm in reachability graphs of place-timed Petri nets

This codes deal with the scheduling problem of resource allocation systems (RASs). It proposes a new anytime search method that combines the A$^*$ search with the depth-first search based on place-timed Petri nets (PNs).
Within a place-timed PN's reachability graph, the method iteratively search for transition firing sequences from a start state to a goal one.
It usually finds a near-optimal solution quickly and continuously improves the solution until obtaining an optimal one if given more time. More importantly, it needs only one parameter and no deadlock control policy, and it can handle the PNs with flexible routes and the generalized PNs with weighted arcs, both of which are common in the PN models of RASs. 

They are developed via C#. 

For more information about its procedures, please refer to:
[1] Bo Huang, MengChu Zhou, XiaoYu Sean Lu, and Abdullah Abusorrah. Scheduling of Resource Allocation Systems with Timed Petri Nets: A Survey. ACM Computing Surveys, pp. 1-28, 2022, DOI: 10.1145/3570326.
[2] A Petri Net-based Anytime A∗ Search for Scheduling Resource Allocation Systems. Submitted.

If you have any question about it, please feel free to contact me.

Bo Huang, email: huangbo@njust.edu.cn
Feb. 1, 2023.
