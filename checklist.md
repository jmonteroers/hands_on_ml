# The Checklist
Checklist introduced in Appendix B, consisting of 8 main steps:

1. Frame the problem, look at the big picture
2. Get the data
3. Explore the data to get insights
4. Prepare the data to better expose the underlying data patterns to ML algorithms
5. Explore many different models, shortlist the best ones.
6. Fine-tune models, combine them into a great solution
7. Present your solution
8. Launch, monitor, and maintain your system.

This list should be adapted to your needs.

# Notes on each point

## Frame the Problem, Look at the big picture
You need to keep an eye on:

- Business objectives
  - how will the algorithm be used?
  - current solutions to the same problem

- How to frame the problem
  - Type of algorithm (supervised, unsupervised...)
  - How to measure performance (min. performance?)
  - Comparable problems?
  - How would you solve the problem manually? Is human expertise available?
  - List the assumptions made
    - Verify them if possible

## Get the Data

- Automate as much as possible so you can easily get fresh data
- Sample a test set, and promise not to look at it!

## Explore the data
Always document!

- Try to get as much expert insight as possible
- Study each attribute and its characteristics:
  - Name
  - Type (categorical, bounded/unbounded, text...)
  - % of missing values
  - Noisiness and type of noise (normal, outliers...)
  - Usefulness for the task
  - Distribution
- Identify promising transformations that can be applied
