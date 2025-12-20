<p align="center">
  <img src="../assets/images/mini-fridge.jpg" alt="Schematic" width="300" height="450">
  <p></p>
  <em>Figure 1.</em> A Danby DAR044A6BSLDBO mini-fridge.
</p>
<p align="center">
  <img src="../assets/images/Schematic-diagram-of-domestic-refrigerator-1972434544.jpg" alt="Schematic" width="300" height="450">
  <p></p>
  <em>Figure 2.</em> Schematic Design sourced from https://ecircuitdiagrams.blogspot.com/2024/11/circuit-diagram-refrigerator-fridge.html.
</p>

<p>
  The mini fridge, as shown in Fig. 1, functions by rejecting heat from its interior to the outside environment, thereby keeping the interior cool. Inside, the fridge is a refrigerant which travels through a closed loop and is capable of easily switching between liquid and gaseous states. The process begins when the refrigerant passes through the evaporator coils, pictured in Fig. 2, and absorbs heat from the inside of the refrigerator, transforming the refrigerant into vapor. Next, the compressor uses electric power in order to compress the vapor. This process increases the temperature and pressure of the refrigerant. Then, as the refrigerant goes through the condenser coils, it loses heat and turns back into a liquid. The capillary tube, pictured in the diagram, decreases the pressure of the liquid, further lowering its temperature.
</p>

<p align="center">
  <img width="671" height="446" alt="image" src="https://github.com/user-attachments/assets/5bb459ee-f75d-488d-857c-a7297b8438d4" />
  <p></p>
  <em>Figure 3.</em> A control volume diagram of the closed loop cycle.
</p>

<p>
  The refrigerator shown above uses 90 W of power to its compressor, per its specifications sheet, and 22g of R600A refrigerant. It also operates between a maximum pressure of 1.1 MPa and a minimum pressure of 0.47 MPa and temperatures of 0° C and room temperature (22° C). State 2 is a saturated vapor at 0° C with an enthalpy of 554.34 kJ/kg. State 4 is a saturated liquid mixture at 22° C with an enthalpy of 251.70 kJ/kg. There are still many unknown values, but information about state 3 can be determined based on a few assumptions and some known information. The first major assumption is that the mass flow rate is 0.08 kg/s, done for the sake of computability. Now, using the control volume equation, the enthalpy at state 3 is equal to 1679.34 kJ/kg. Then, the amount of heat rejected in the condenser is 114.211 W. Lastly, the amount of heat inputted can be computed by assuming that the system as a whole represents a closed loop cycle. Thus, the change in internal energy for the whole cycle is 0. The heat input is 24.211 W. Hence, the efficiency of the refrigeration cycle is 1.27.
</p>

<p>
  In order to improve the cycle efficiency, the refrigerator could be changed to have a dual cycle setup for which the two cycles are connected by a heat exchanger that replaced one of the cycle's evaporator and the other cycle's condenser. In this setup, each cycle would operate under a different temperature range. Thus, the refrigerants would be chosen based upon that information, and more specific choices of refrigerants can allow for lower minimum temperatures. In addition, by breaking up the cycle into two cycles, the compressors also do not need to do as much work as the single compressor in the original setup resulting in less work input. Thus, the efficiency can be improved. Lower pressures will also result in less mechanical stress which can improve the durability of the refrigerator.
</p>
