# The Hire-Assistant Problem.
Imagine that you need to hire a new assistant. Every day an agency sends a new assistant for you to interview. If the assistant is better than your current assistant, then you fire your current assistant and you hire the better assistant. You may assume that assistant quality is uniformly distributed between 0 and 1.

## hire_assistant()
A function that takes applicants (a list of the numbers that represent the level of qualification of the applicants; the higher the number, the better qualified), and returns the number hires if the applicants are presented in the exact same order as the input list applicants.

## experimental_hires()
Assuming the applicants are presented in a random order, a function that receives the number of applicants as input and returns the average number of assistants hired.

## analytical_hires()
A function which returns the analytical expected number of hires, given the number of applicants, along with the experimental_hires() function to create a graph with two curves such that:

- The x-axis shows the total number of applicants (make sure label the x-axis)
- The y-axis shows the average number of hires (make sure label the y-axis)
- The graph contains two curves;
-- Curve 1: the theoretical performance estimates computed calls to the function analytical_hires.
-- Curve 2: the simulated or experimental estimates using the function you created in question 2.

## optimal_stopping()
an optimal stopping rule, ie. at what point should one stop requesting new potential hires from the agency?
