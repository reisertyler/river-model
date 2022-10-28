## Modeling a River

---
### Introduction
Social insects ... moving in a direction with no sense of rules...

#### We want...
1. Create a mathematical model?
    - for a section of a large river
2. Can you tell me what r of t is for some non-zero t value?
    - pick coordinate system, where r is the position vector from the origin to the point on the river

#### Approach
1. Energy
    - no one has come up with a rational
2. Speed
    - get the width and the flow from a website (average for the year)


#### Problems to Think About
1. How do you know when you are close?
    - i.e. who are the neighbors?
    - number of neighbors
    - so, the location of each point depends on the neighbor
    - go down the list to see if any other points are close on a list
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
2. Width
3. Curvature

#### Assumptions 
1. The river width is not changing
    - i.e. the width is fixed
2. Uniform material properties
    - the soil is well-packed
3. River is mostly flat
4. Center will be flowing faster than the sides
    - parabolic flow from looking above
    - parabolic flow from looking from the side
        - ignore this 
    
    example:
        
        ``` 
         ------------------------------ 
                   \        (Any river)
          Water      \
          flow -->     \
                       /
                     /
                   /
         ------------------------------ 
        ``` 

#### First/Last Point
There will be problems with the first and last point.
    - small scale details

---
### 1. Breaking through
- how do you know if they crossed?
- Who get's removed from the list? 
- throw away everyone on the left until you get to the right.
    - first data point is to the left, say location 100
    - from the top of the list, we go through river point locations
    - might be moving neighbors to the left

two bends some closer and closer. How do you reroute the river?


---
#### Navier-Stokes
**Problem:** these are just models and now we have more computing power.

Emperical modeling for flow--it is curve fitting.

Is it science to run numerical simulations (numerical models), take the results, then doing the curve fitting on the simulated data.

- Curve fitting 
- say they will talk about the Physics
- Multiple levels removed from the physics
- "it can get you to the moon and back"

#### Rivers
- drainage of great lakes
- tributary looking for dinosaur tracks
- "g input" utilize "g input" (matlab function) 
    - utilize points 


---
#### Overview
**Stage 1:** 
 - two things come too close
 - once they cross
 - some leakage
 - once it becomes majority of the flow
 - left bank and right bank, acros river: once bank touches another bank
 
**Stage 2:** 

 


