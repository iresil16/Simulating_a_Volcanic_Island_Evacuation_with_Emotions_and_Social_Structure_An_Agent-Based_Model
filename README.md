# Simulating a Volcanic Island Evacuation  
### with Emotions and Social Structure:  
#### An Agent-Based Model Applying the BEN Architecture  

**Authors:** Enrico Sansone, Irene Silvestro, Ilaria Vetrano  
**Course:** Econophysics and MAS Laboratory  
**Date:** September 2025 – Academic Year 2024/25  



##  Project Overview  

This project presents an **Agent-Based Model (ABM)** designed to simulate the evacuation of the population of the island of **Vulcano (Italy)** during a volcanic eruption.  
The model integrates **emotions** and **social structures** into the agents’ decision-making processes to reproduce realistic evacuation dynamics.  

To ensure environmental realism, we used the **real-world road network** of Vulcano Island.  
The simulation was developed in **GAMA Platform (version 1.9.3)**.  

During a simulation run:
- The **Volcano agent** acts as a trigger, generating “boom” events perceived by people on the island, which alter their emotions and decisions.  
- The **Civil Defense (CD)** agent supervises and coordinates **Law Enforcement Agents (LEAs)**, issues evacuation orders, manages evacuation resources (ferries, helicopters, ports), and monitors volcanic activity and evacuation status.  
- The simulation ends once the civilian population and LEAs safely reach **Milazzo’s port**.  

Our research aims are:
- To **evaluate the impact of emotional and social mechanisms** on total evacuation time;  
- To **assess the effectiveness of the broadcast alert system (IT-Alert)** compared with a point-to-point notification system in a crisis scenario.  



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
- **Focus:** Integration of emotional dynamics and social structure within the BEN architecture  
- **Case Study:** Vulcano Island (Aeolian Islands, Italy)  
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


