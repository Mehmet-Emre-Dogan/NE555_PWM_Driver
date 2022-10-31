# NE555_PWM_Driver
NE555 precision timer based IRFZ44N LED/motor driver design.
- No feedback loop
- Just open loop control
- No filter
- Bare PWM output
 
## PCB Design (DIP)

<div align="center">
 
### Schematic
 
![schematic](./sch.png)
 
 
### Front
 
![front](./top.png)
 

### Back
 
![back](./bottom.png)
 
 </div>

## PCB Design (SMD)

<div align="center">
 
### Schematic
 
![schematic](./NE555_PWM_Driver_smd/sch.png)
 
 
### Front
 
![front](./NE555_PWM_Driver_smd/top.png)
 

### Back
 
![back](./NE555_PWM_Driver_smd/bottom.png)
 
 </div>

## PCB Images (SMD)

<div align="center">
 
### With Lamp
 
![with load](./withLoad.jpeg)
 
 
### Front
 
![front](./topPcb.jpeg)
 

### Back
 
![back](./bottomPcb.jpeg)
 
 </div>

## Oscilloscope Waveforms

<div align="center">

### General

![scope](./smdScopePics/scope.BMP)

### Whole Swing

![scope](./smdScopePics/wholeSwing.BMP)

### Ripple

![scope](./smdScopePics/ripple.BMP)

### Noise

![scope](./smdScopePics/noise.BMP)

 </div>

 ### Conclusion

 - The theoratical frequency is consistent with experimental frequency
 - There is small discrepancies between the theoratical ripple and experimental ripple

## Simulation on LTSpice
  
 <div align="center">
 
### Circuit
 
![cct](./SPICE/sim_sch.png)
 

### Waveforms
 
![wvf](./SPICE/sim_wvf.png)
 
 </div>
 
 ## Prototype on Breadboard
  
 <div align="center">
 
 ### [Watch the video](https://youtu.be/RiIcqe25NVU)
 
![prototype](./prototype.jpg)
 
 </div>

 ## References
https://circuitdigest.com/electronic-circuits/555-timer-pwm-generator-circuit
