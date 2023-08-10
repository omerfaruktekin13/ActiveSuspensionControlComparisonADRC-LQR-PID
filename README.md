# ActiveSuspension Control Comparison ADRC (Active Disturbance Rejection Control), LQR (Linear Quadratic Regulator) and PID
In progress...
## Project Media
![Dxxxxx]( "Deneme ")
|:--:|
| *Simscape Simulation* |
![Dxxxxx]( "Deneme ")
| *Simulink Model* |
![Dxxxxx]( "Deneme ")
| *Control Algorithm Comparison* |


## Description
<p>This project is designed to test and control the vehicle suspension with 3 different control algorithms: ADRC, LQR, and PID. I draw the Cyber Truck on Autodesk Fusion 360 and connected the parts on Simulink Simscape for simulation.</p> 
<p>ADRC estimates and compensates for system uncertainties in real-time, providing disturbance rejection performance similar to PID controllers but with less tuning effort.</p> 
<p>The theory of LQR optimal control is concerned with operating a dynamic system at a minimum cost. The case where the system dynamics are described by a set of linear differential equations and the cost is described by a quadratic function is called the LQ problem. </p>
<p>A PID controller continuously calculates an error value e(t) as the difference between a desired setpoint and a measured process variable and applies a correction based on proportional, integral, and derivative terms, hence the name.</p> 
I sent three disturbances (road height) to the system with different heights. According to the plot, sort of the control algorithm success can be: ADRC, LQR and PID.

# Equation of Motion of the Vehicle
![Dxxxxx](https://github.com/omerfaruktekin13/ActiveSuspensionControlComparisonADRC-LQR-PID/blob/main/Media/Equations/e_1.png "Deneme ")
|:--:|
| *Front Suspension Force on Bounce* |
![Dxxxxx](https://github.com/omerfaruktekin13/ActiveSuspensionControlComparisonADRC-LQR-PID/blob/main/Media/Equations/e_2.png "Deneme ")
| *Pitch Moments* |
![Dxxxxx](https://github.com/omerfaruktekin13/ActiveSuspensionControlComparisonADRC-LQR-PID/blob/main/Media/Equations/e_3.png "Deneme ")
| *Forces and Moments in Body Motion* |

## Tools and Languages
<a href="https://www.mathworks.com/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" alt="matlab" width="40" height="40"/> </a>
<p> * MATLAB 2023a </p>
<p> * Simulink </p>
<p> * Simulink Simscape </p>
<p> * Simulink Desktop Real-Time </p>
<p> * Simulink Control Toolbox </p>

## Installation
> 1. Download CarModel.slx in the FirsPart folder and observe the effect of the qualifications on the vehicle speed interactively.
> 2. Download SecondPart folder into your MATLAB path.
> 3. Be sure that your MATLAB path is chosen SecondPart folder.
> 4. Open VehicleSystemControl.slx file. MATLAB will automatically combine the other Simulink files.
> 5. You can create your C++ code using Code Generator to implement it to your hardware.

## Open to Development
Please share your comments and ideas about the project with me. Thank you for your time.
