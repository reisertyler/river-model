## Modeling a River

---
### Introduction
Social insects ... moving in a direction with no sense of rules...

#### We want...
1. Create a mathematical model?
    - for a section of a large river
2. Can you tell me what r of t is for some non-zero t value?
    - pick coordinate system, where r is the position vector from the origin to the point on the river


#### Problems to Think About
1. How do you know when you are close?
    - i.e. who are the neighbors?
    - number of neighbors
    - so, the location of each point depends on the neighbor
2. What direction am I moving?
3. What rate am I moving out?
4. Width of river
    - when the rivers interact with eachother the widths becoming
5. Who are my new neighbors?
    - one circle will "eclipse" another
    - think of a grid, how many points of river are flowing over?
        - if there are two, what does that mean?
- every point will move radial outward based on the normal


#### Important Objects
1. Location


#### Important Attributes
For any point,

1. Who are your neighbors?
    - each point should have an idea of local river width
    - property associated with each point


#### Assumptions 
1. The river width is not changing
    - i.e. the width is fixed
2. Uniform material properties
    - the soil is well-packed

---
### 1. Breaking through
- how do you know if they crossed?
- Who get's removed from the list? 
- throw away everyone on the left until you get to the right.
    - first data point is to the left, say location 100
    - from the top of the list, we go through river point locations
    - might be moving neighbors to the left

two bends some closer and closer. How do you reroute the river?

