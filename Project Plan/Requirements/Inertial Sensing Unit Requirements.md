<div align="center">
<h1 style="font-size:10vw">Requirement Analysis Document</h1>

<div align="left">
  
  
**Subsystem:** Inertial Sensing Unit
  
**Last date of revision:** 02-02-2023
  
**Document status:** Draft
  
**Authors:** Thiruvarulselvan K

_**Revision history:**_
  
_1. First draft completion- 02/02/2023_
  
_2. Addition of system model - 10/02/2023_

**Abbreviations:**
  
CPM - Central Processing Module

**Purpose of the subsystem:**
  
Measure the essential parameters of the rocket and communicate with the CPM 


| Type  | Requirement | Priority |
| ------------- | ------------- | ------------- |
| Functional  | Measure the rocket kinetic parameter such as Velocity, Acceleration, Attitude (roll, pitch, and yaw), Altitude. | Core |
| Functional  | Measure the Airspeed on the airframe, Vibration on the airframe, Motor temperature, and System Voltage and Current  | Core |
| Functional  | Acquire the real-time location of the rocket | Core |
| Operational  | Measures the parameters in the appropriate range associated with the rocket’s range of capabilities | Essential |
| Operational  | Should provide required signal resolution and sampling rate | Essential |
| Technical  | Should be powered with the CPM’s output power supply | Essential |  
| Technical  | Sampling rate of each sensor should be relative to each other to maintain data sync | Desired |  
| Technical  | The sensing units should withstand the effect of changes in the physical parameters during the entire mission | Desired |  
  

**System Model:**
  
  ![ISU Model](https://user-images.githubusercontent.com/109530150/218327323-2ffa277a-8629-460c-acb1-b67c4c3606ad.png)
  
[Requirement Analysis Document ISU.docx](https://github.com/the-indie-engineer/Data-Acquisition-and-Recovery-System-for-sounding-rockets-Dutah-/files/10716772/Requirement.Analysis.Document.ISU.docx)
