# Simulating a Volcanic Island Evacuation with Emotions and Social Structure:  
## An Agent-Based Model Applying the BEN Architecture  

**Authors:** Enrico Sansone, Irene Silvestro, Ilaria Vetrano  
**Course:** Econophysics and MAS Laboratory  
**Date:** September 2025 – Academic Year 2024/25  



##  Project Overview  

This project consists in an Agent-Based Model (ABM) built to simulate the evacuation of the population
during a volcanic eruption of the island of Vulcano (Italy). Our approach integrates emotions and social
structures in the decision-making process of the agents. To further provide a realistic environment, we also
used the real-world road network of Vulcano island. The model was developed in GAMA (version 1.9.3).
During a simulation run, the volcano agent acts as a trigger with its “boom”-events that are perceived by
people on the island and changes the decisions of agents. The Civil Defence (CD) agent manages and
coordinates Law Enforcement Agents (LEAs), the issuing of evacuation order to civilian population and the
evacuation resources such as ferries, helicopters and ports as well as monitoring volcanic activity and
evacuation status. Only when the civilian population is evacuated, LEAs can leave the island and as soon as
they reach Milazzo’s port the simulation is terminated.
Our research aim is to assess the impact that the emotional and social engine have on the evacuation time
and to evaluate the effectiveness of a broadcast alert system (IT-Alert) in this crisis scenario by comparing it
to a point-to-point one.



## Report Structure  

1. **Project Overview**  
2. **Literature Review**  
3. **Model Overview**  
   - Environment
   - Agents Architecture 
     - *Civil Defense*  
     - *Volcano*  
     - *Evacuation Infrastructures (Ports, Heliports, Waiting Areas)*  
     - *Evacuation Vehicles (Ferries, Helicopters)*  
     - *Humans (People, Law Enforcement Agents – LEAs)*  
   - Input Data  
4. **Experimental Setting**  
   - Initialization
5. **Results**  
6. **Future Developments**  
7. **Conclusions**




##  Implementation Details  

- **Modeling Platform:** GAMA 1.9.3  
- **Approach:** Agent-Based Modeling (ABM)  
- **Focus:** Integration of emotional dynamics and social structure using BEN architecture  
- **Case Study:** Vulcano Island (Italy)  
- **Main Agents:**  
  - Volcano  
  - Civil Defense (CD)  
  - Law Enforcement Agents (LEAs)  
  - Civilians (People)  
  - Evacuation infrastructures and vehicles  



##  Code Repository  

The full implementation of the model is available here:  
 [https://github.com/erriho/Vulcano_Evacuation_ABM](https://github.com/erriho/Vulcano_Evacuation_ABM)



##  Research Objectives  

- Analyze how **emotional states** and **social relationships** influence evacuation behavior and timing.  
- Compare the **IT-Alert broadcast system** with a **point-to-point alert mechanism** under emergency conditions.  
- Assess which and how **non-rational behaviors of agents** affect overall evacuation efficiency.


