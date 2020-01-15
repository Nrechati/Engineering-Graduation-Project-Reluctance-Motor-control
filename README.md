# Engineering Graduation Project : Reluctance motor synthesis, Sliding Mode and Kalman Filter observers, Fault Tolerant Control command

This project is my **Graduation Project** as a 5th Year **Engineering student at ESTACA**. Me and my team worked on this projet for 4 months during or last engineering year and this was our main grade for this year toward graduation.

## Abstract

Lorem Ipsum

## Table of contents

### 1. Introduction

### 2. The Reluctance motor

- **2.1  Use case context**
- **2.2  Reluctance motor functioning**
- **2.3  Reluctance motor functioning without sensor : Observer addition**

### 3. Replacing sensor by observers

- **3.1  Sliding Mode observer**
	- 3.1.1  Therory
	- 3.1.2  Sliding mode observer equation for position sensor
	- 3.1.3  Simulink implementation for the reluctance motor *Pt/MG*
	- 3.1.4  Robustness test for *Pt/MG*
	- 3.1.5  Simulink implementation for the reluctance motor *MG/MG*
	- 3.1.6  Robustness test for *MG/MG*

- **3.2 Kalman filter**
	- 3.2.1  Therory
	- 3.2.2  Kalman filter method equation for position sensor
	- 3.2.3  Implementation
	- 3.2.4  Robustness test

- **3.3 Observers comparison**

### 4. Fault Tolerant Control command

- **4.1  FTC Command objectives**

- **4.2  FTC command synthesis for a reluctance motor with observers**
	- 4.2.1  Check for observers block output datas refreshing
	- 4.2.2  Check for "Out of Range" output
	- 4.2.3  Watch for large fluctuation in observers output signals
	- 4.2.4  Vote algorithm to detect observers degradations
	- 4.2.5  Raising failure for user

### 5. Conclusion

### 6. Project Management feedback

## Reluctance Motor Model

![power supply full model](./Ressources/MRV_model.png)

## Credits

This work was done with my former school colleagues :

- **Antoine HAMY**
- **Cindy MALARD**
- **Paul MUGNIER**

And our teachers help, **Dr. Ahmed CHAIBET** and ***Dr. Moussa BOUKNIFER**,
