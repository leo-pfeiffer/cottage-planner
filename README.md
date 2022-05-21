# cottage-planner

Optimizer that allocates guests into cottages s.t.

- people who must stay together, stay together
- people who must NOT stay together, do not stay together

minimizing the sum of 

- the number of people staying together that don't like each other and
- the number of people NOT staying together that like each other

# Usage

The solver uses the [Savilerow optimizer](https://savilerow.cs.st-andrews.ac.uk/) and the problem is specified in the [Essence Prime Language](https://www.csplib.org/Languages/EssencePrime/).

Assuming you have savilerow installed, run:

`savilerow opti-planner.eprime planner.param -run-solver`

# Input 

#todo
