# ActiveSuspension Control Comparison ADRC (Active Disturbance Rejection Control), LQR (Linear Quadratic Regulator) and PID
In progress...
## Project Media
![Dxxxxx](https://github.com/omerfaruktekin13/ThrottlePositionControlwithSimscapeandAUTOSARStandards/blob/main/Media/VehicleDesign.png "Deneme ")
|:--:|
| *Vehicle Model* |
![Dxxxxx](https://github.com/omerfaruktekin13/ThrottlePositionControlwithSimscapeandAUTOSARStandards/blob/main/Media/Architecture.png "Deneme ")
| *Overall System* |
![Dxxxxx](https://github.com/omerfaruktekin13/ThrottlePositionControlwithSimscapeandAUTOSARStandards/blob/main/Media/Composition.png "Deneme ")
| *Software Architecture* |
![Dxxxxx](https://github.com/omerfaruktekin13/ThrottlePositionControlwithSimscapeandAUTOSARStandards/blob/main/Media/LookUpTable.png "Deneme ")
| *LookUp Table* |
![Dxxxxx](https://github.com/omerfaruktekin13/ThrottlePositionControlwithSimscapeandAUTOSARStandards/blob/main/Media/PIDControl.png "Deneme ")
| *Function-Call Subsystem* |
![Dxxxxx](https://github.com/omerfaruktekin13/ThrottlePositionControlwithSimscapeandAUTOSARStandards/blob/main/Media/function-call.png "Deneme ")
| *PID Control Unit* |

## Description
The theory of optimal control is concerned with operating a dynamic system at a minimum cost. The case where the system dynamics are described by a set of linear differential equations and the cost is described by a quadratic function is called the LQ problem. ADRC estimates and compensates for system uncertainties in real-time, providing disturbance rejection performance similar to PID controllers but with less tuning effort. 

## Tools and Languages
<a href="https://www.mathworks.com/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" alt="matlab" width="40" height="40"/> </a>
<p> * MATLAB 2023a </p>
<p> * Simulink </p>
<p> * Simulink Simscape </p>
<p> * Simulink Desktop Real-Time </p>
<p> * Simulink AUTOSAR Blockset </p>

## Installation
> 1. Download CarModel.slx in the FirsPart folder and observe the effect of the qualifications on the vehicle speed interactively.
> 2. Download SecondPart folder into your MATLAB path.
> 3. Be sure that your MATLAB path is chosen SecondPart folder.
> 4. Open VehicleSystemControl.slx file. MATLAB will automatically combine the other Simulink files.
> 5. You can create your C++ code using Code Generator to implement it to your hardware.

## Open to Development
Please share your comments and ideas about the project with me. Thank you for your time.
