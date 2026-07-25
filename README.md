 # Analysis-of-open-loop-and-closed-loop-control-system
## Aim :
  To analyse the open loop and closed loop system having G(S)=1/(S^2+10S+20)  when an unit step input is applied using MATLAB.
## Apparatus Required:
  Computer with MATLAB software
## Theory
  ### Open loop control system
  In this system, the output doesn’t change the action of the control system. It doesn’t have any feedback. It is very simple, needs low maintenance, quick operation, and cost-effective. The accuracy of this system is low and less dependable.
  <img width="652" height="175" alt="image" src="https://github.com/user-attachments/assets/0a9d8129-eb64-40bb-8efd-434edcb2bd5a" />
 ### Closed loop control System
The closed-loop control system can be defined as the output of the system that depends on the input of the system. This control system has one or more feedback loops among its input & output. This system provides the required output by evaluating its input. This kind of system produces the error signal and it is the main disparity between the output and input of the system.
                     <img width="508" height="220" alt="image" src="https://github.com/user-attachments/assets/ad4b9b9e-bf06-4108-a4c0-5320be064b1f" />

Consider a system having plant G(S)=  1/(S^2+10S+20), H(S) = 1(negative unity feedback system) and Controller C(S) = 300.
C(S) and G(S) are in series, 300/(S^2+10S+20)
300/(S^2+10S+20) and H(S) are in negative feedback.
Therefore, Closed loop transfer function, (C(S))/(R(S))=300/(S^2+10S+320)
## Program: 
### Open loop System
<img width="1600" height="900" alt="WhatsApp Image 2026-07-23 at 7 08 18 PM" src="https://github.com/user-attachments/assets/d63930d1-dd15-4a12-9c3e-6c5de7f5a9b0" />

### Closed loop System
<img width="1600" height="900" alt="WhatsApp Image 2026-07-23 at 7 10 05 PM" src="https://github.com/user-attachments/assets/39c22224-3d18-409e-b9a0-7706e33abac6" />

## Simulink:
### Open loop System
<img width="1600" height="848" alt="WhatsApp Image 2026-07-23 at 7 09 44 PM" src="https://github.com/user-attachments/assets/47429896-8bf6-4e9a-a06e-4ee31f38f288" />

### Closed loop System
<img width="1600" height="900" alt="WhatsApp Image 2026-07-23 at 7 05 57 PM" src="https://github.com/user-attachments/assets/66a46c2c-6ade-406b-b3a3-276dfe677235" />

## Procedure:
	Open MATLAB software
	Open a new script file.
	Type the program.
	Save and Execute the program.
	Analyse the result.
## Output:
### Open Loop System:
<img width="1600" height="826" alt="WhatsApp Image 2026-07-23 at 7 06 47 PM" src="https://github.com/user-attachments/assets/acd607b7-76bf-40c6-b23a-fd16db19de3c" />

### Closed Loop System:
<img width="1600" height="900" alt="WhatsApp Image 2026-07-23 at 7 05 00 PM" src="https://github.com/user-attachments/assets/8cd26ad8-c2f2-4873-b253-13b2da9fa42f" />

## Result:
Thus the open loop and closed loop system are analysed and the following conclusions are arrived.
### Open loop system
Steady State Error = 1-0.05=0.95

Settling Time = 2.25s
### Closed loop System
Steady State Error = 0.04

Settling Time = 1.2s





