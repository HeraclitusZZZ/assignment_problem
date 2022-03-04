# Assignment Problem

The assignment problem is a fundamental **combinatorial optimization problem**. In its most general form, the problem is as follows:

The problem instance has a number of *agents* and a number of *tasks*. Any agent can be assigned to perform any task, incurring some *cost* that may vary depending on the agent-task assignment. It is required to perform as many tasks as possible by assigning at most one agent to each task and at most one task to each agent, in such a way that the *total cost* of the assignment is minimized.

If the numbers of agents and tasks are equal, then the problem is called *balanced assignment*. Otherwise, it is called *unbalanced assignment*. If the total cost of the assignment for all tasks is equal to the sum of the costs for each agent (or the sum of the costs for each task, which is the same thing in this case), then the problem is called *linear assignment*. Commonly, when speaking of the *assignment problem* without any additional qualification, then the *linear balanced assignment problem* is meant.

## Formal Definition

The formal definition of the **assignment problem** (or **linear assignment problem**) is

Given two sets, *A* and *T*, of equal size, together with a weight function *C*: *A* x *T* &rightarrow; *R*. Find a bijection *f*: *A* &rightarrow; *T* such that the cost function:

&sum;<sub>a&in;*A*</sub> *C*(*a*,*f*(*a*))

is minimized.

Usually the weight function is viewed as a square real-valued matrix *C*, so that the cost function is written down as:

&sum;<sub>a&in;*A*</sub> *C*<sub>*a*,*f*(*a*)</sub>

The problem is "linear" because the cost function to be optimized as well as all the constraints contain only linear terms.

 
## Reference

[1] https://en.wikipedia.org/wiki/Assignment_problem
