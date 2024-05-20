Name : ADHL HAMEED
Reg. No: 212223050002

Aim:
To design and simulate a traffic light controller for an intersection of three main roads, where each road has equal priority. The controller should regulate the traffic flow efficiently, ensuring safety and smooth movement of vehicles while diverting the traffic to path 1 direction and disabling control in other directions.
Apparatus Required:
1.	Hardware Description Language (HDL) simulation environment such as Verilog or VHDL.
2.	Simulation software like ModelSim for testing and verification.
3.	FPGA development board (optional) for hardware implementation.
Procedure:
1.	Define the State Machine
2.	Implement the State Machine in HDL
3.	Simulate the Design
4.	Test the Design
5.	Optimize and Refine

State Table :
•	To define the states, inputs, outputs, and state transitions. 
•	Let's denote the three main roads as MR1, MR2, and MR3. 
•	Each road can have three possible states for its traffic light: Red, Yellow, and Green. Here's the state table:
   
•	Each row represents a state transition along with the corresponding outputs for each main road.
•	The "Counter" column indicates the counts for each state before transitioning to the next state.
•	The "Current State" column represents the current state of the state machine.
•	The "Next State" column indicates the state to transition to after completing the counts.
•	The "MR1", "MR2", and "MR3" columns specify the traffic light states for each main road in the current state.
•	"Red", "Yellow", and "Green" denote the states of the traffic lights.
•	The counter counts from 0 to 9, where each count corresponds to one clock cycle.
Code:
![image](https://github.com/adhlhameed/Hackathon/assets/168260238/8a6af1b4-564a-40b5-ba3b-12cac1e384e3)
![image](https://github.com/adhlhameed/Hackathon/assets/168260238/29fef600-f135-41f9-935c-c55a1253c9fd)
![image](https://github.com/adhlhameed/Hackathon/assets/168260238/aef50836-8ee7-432f-bb20-81d34bc985ed)
![image](https://github.com/adhlhameed/Hackathon/assets/168260238/e6e616e1-f238-454f-82ca-4fde1d30526b)
![image](https://github.com/adhlhameed/Hackathon/assets/168260238/44b08204-4287-4582-af83-0412117014c5)





RTL Schematic View

![image](https://github.com/adhlhameed/Hackathon/assets/168260238/5525ef08-9b20-4128-a671-389bbb31e0f6)


 


Output Waveforms

![image](https://github.com/adhlhameed/Hackathon/assets/168260238/9d1aac82-8658-4304-add6-66665864a287)


