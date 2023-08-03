# ActiveSuspension Control Comparison ADRC (Active Disturbance Rejection Control), LQR (Linear Quadratic Regulator) and PID

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
This project consists of 2 different parts:
<p>In the first part, I've created the car system in the 1st picture using Simulink/Simscape. I declared the parameters of the wheels with the Magic Formula algorithm. While the system is running, you can interactively observe how the speed of the car is affected by changing the incline of the road, the throttle position and the wind speed in the opposite direction.</p>
In the second part, I explained how to create a throttle position in accordance with AUTOSAR and ISO26262 standards and make it ready for hardware. The 2nd picture shows the I/O inputs, the State Chart section that sorts the hierarchy in the server-client system and the composition block of the whole system. The 3rd picture shows the Software Architecture Model, which includes Adaptive Software Components. You can examine the ports and the event sequences assigned to them in the AUTOSAR Dictionary section. At this stage, you can generate your C++ Code and ARXML files for your hardware with MATLAB Code Generator. If you wish, you can change the table values such as HBridge in the system with the LookUp Table Editor as in the 4th picture. In the 5th picture, there is the function-call Subsystem, which is required to create the Adaptive Software Component and is triggered by the functions we have created in the State Chart. In the last picture, you can see the PID Controller.

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
