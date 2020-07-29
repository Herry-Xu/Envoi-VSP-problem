**Description:**
This problems is an optimation problem for finding the least-cost cyclic route for drivers. I am going to assume that the graph is non-weighted as the size of packages or priority of clients is not defined.

This problem can be separated into travelling salesman problems when there's only one vehicle. That problem can be solved using matrices and Branch & Bound.

**Questions:**
1. Should each driver start at the same location? In this case each driver start in the centre of the regions and return to their starting
2. Should each driver deliver to an equal amount of clients or are they just trying to minimize distance?

**Later Considerations:**
1. Each driver will have a certain capacity in their car, this becomes an optimizations that also require constraints (May need to be solved like a Greedy Method Problem)\
2. Time windows for deliveries of customers, which adds more constraints and complexity to the algorithm
3. How does traffic affect the optization problem? Speed limits, time of day, and real-time traffic data may be needed to optimize routes for every driver ( Use Google Maps, Waze, TomTom or MapQuest APIs?)
4. Types of good? Certain vehicles are probably needed depending on the bulkiness of the item with adds more constraints

**Notes:**
- Triangulation can be used to save time which may cut down the amount of drivers (Assuming multiple Drivers start at the same location)

**Resources I Used:**
- https://developers.google.com/optimization/routing/vrp#example_python
- VSP Lecture: https://www.youtube.com/watch?v=A1wsIFDKqBk
- Abdul Bari: https://www.youtube.com/watch?v=1FEP_sNb62k