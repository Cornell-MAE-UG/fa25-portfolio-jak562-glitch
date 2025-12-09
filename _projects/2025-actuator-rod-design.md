---
layout: project
title: Actuator Rod Design
description: The design is meant to withstand the most weight attached to the top of the rod.
technologies: [Calculator]
---
<center>
  <img width="800" height="369" alt="image" src="https://github.com/user-attachments/assets/b2f27616-0b8e-402a-af8e-57df1eefeff4" />
</center>

Case 1: Rigid Bar
Using three pins, I connected the rod and actuator to each other using one pin and each object to the ground using two pins, respectively. I chose the high force rod-style actuator because it has a maximum force of 294 kN. My design effectively maximizes the vertical load support by optimizing the angles and lengths of the support rods. The rod on the left is angled at approximately 51.65°, which is close to the ideal angle range (45–60°) for maximizing vertical force components while minimizing horizontal thrust. With this geometry, more of the 294 kN force capacity of the rod is directed upward to counteract the load, rather than being wasted in horizontal force. Choosing an angle that is slightly greater than 45 degrees allows the actuator to provide a sizeable vertical force as well as more effectively oppose moments about the bar. Choosing the rod's length to be 70.71 cm ensures that weight attached to the top will be able to reach the vertical limit for the design space as well. This setup ensures a high vertical force component, which translates to greater weight-bearing capability, and takes advantage of the design space limits.

Case 2: Non-Rigid Bar
Now that the bar is non-rigid, it may be subject to buckling. The material that the rod is made of is structural steel which has a Young's Modulus of 200 GPa. The mass of a rod (a cylinder) of length 70.71 cm and a 6 cm diameter is 0.157 kg, meaning that its inertia is 0.00655 kgm^2. The most force would be on the rod, when the rod is supporting the max weight and the actuator is outputting its maximum force on the rod. However, the load limit was designed such that it would be almost entirely supported by the actuator rather than the rod, or else it would be a better design to simply balance the load on exclusively the rod. Thus, the max load is about 182 kN. That force is then applied at both the top of the rod by the weight and the point of contact by the actuator. In this orientation the actuator would be pressing with 292 kN on the rod. The weight would be torquing the rod with a force of 129 kN. Thus, the moment equation is effectively M = 129(35cm - x) - 182x. Thus, applying it to the elastic curve results in the following equations:
                                                          EIy'' = 129(35cm - x) - 182x
                                                          EIy' = 129(0.35 - 0.5x^2) - 91x^2
                                                          EIy = 129(0.35 - 0.167x^3) - 30.33x^3
The maximum deflection occurs 0.53 m or 18 cm above the actuator-rod contact point. The deflection there is 34.5 nm. This represents a very small deflection, keeping witihn a 2% error. Because the original design was so effective, the only change is the designation of a specific diameter which had previously been unneeded because a rigid bar is not affected by yield strengths or deflection.
