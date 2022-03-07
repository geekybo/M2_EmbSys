# Microcontroller-Based-LPG-Gas-Leakage-Detector-using-GSM-Module
![Gas](https://user-images.githubusercontent.com/98813646/155738299-52cb1792-8b15-4ba1-8810-879c6197d066.PNG)
# CODE ANALYSIS.
![M2_Emb](https://user-images.githubusercontent.com/98813646/156938928-fa034589-aa74-4ad4-88e9-b5f8a8d117ad.PNG)

| Code Quality Score | Code Grade | Codacy | Cpp Check |
| -- | -- | -- | -- |
| ![code quality](https://api.codiga.io/project/31606/score/svg) | ![Code Grade](https://api.codiga.io/project/31606/status/svg) | [![Codacy Badge](https://app.codacy.com/project/badge/Grade/d2c0b11de0c04752b68999beaa36ed50)](https://www.codacy.com/gh/geekybo/M2_EmbSys/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=geekybo/M2_EmbSys&amp;utm_campaign=Badge_Grade) | [![Cpp check](https://github.com/geekybo/M2_EmbSys/actions/workflows/cppcheck.yml/badge.svg)](https://github.com/geekybo/M2_EmbSys/actions/workflows/cppcheck.yml)


## Table of Contents.
1. About the gas leakage
      1. Description.
      1. Features.
      1. State of art.
2. Swot Analysis.
      1. Strength
      1. Weakness
      1. Opportunities
      1. Threats.
      1. 4W & 1H.
3. Block Diagram.
      1. Components in Block Diagram.
4. High Level Requiremnts.
5. Low Level Requiremnets.
      
 
## Description
   The presence of dangerous LPG leakage in the cars, service station or in the storage tank environment can be detected using the Ideal Gas Sensor. This LPG gas leakage detector unit can be easily integrated into a unit that can sound an alarm or give a visual suggestion of the LPG concentration. The sensor has both admirable sensitivity and rapid response time. This sensor can also be used to sense other gases like iso-butane, propane, LNG and even cigarette smoke.
 
   The output of the sensor goes LOW as soon as the LPG sensor senses any gas leakage from the storage. This is detected by the microcontroller and the LED & buzzer is turned ON. After the delay of few milliseconds, the exhaust fan is also turned ON for throwing the gas out and it continues sending message as ‘GAS LEAKAGE’ to a mobile number which is pre-defined.

## FEATURES

*  The sensor has both admirable sensitivity and rapid response time.
*  This sensor can also be used to sense other gases like iso-butane, propane, LNG and even cigarette smoke. 
*  The output of the sensor goes LOW as soon as the LPG sensor senses any gas leakage from the storage.
*  Easy to use.


## STATE OF ART/RESEARCH

![image](https://user-images.githubusercontent.com/94245015/144088408-5831066c-a48d-4419-8517-bab65da67e2d.png)


## SWOT ANALYSIS

## STRENGTH 

 - Detection and Prevention of any sort of gas leakage.

- Cost Efficient and less Complex circuit.

- No environmental effect or no effect of physical conditions.

- It is use in vehicles and as well as in houses as LPG leakage detection.

## WAEKNESS

- It work only when at 5v power supply.

- It's sensitivity depends on Humidity and temperature.

## OPPORTUNITIES

- Gas detectors can be used to detect combustible, flammable and toxic gases, and oxygen depletion. 
- This type of device is used widely in industry and can be found in locations, such as on oil rigs, to monitor manufacturing processes and emerging technologies such as         
  photovoltaic. 
- They may be used in firefighting.

## THREATS
- Inhaling leaked gas in an indoor space, such as your home can result in a lack of oxygen in the air and lead to hypoxia.
- That can, in turn, lead to severe headaches, fatigue, decreased vision, short breaths, and even loss of consciousness.
## 4W & 1H
## WHY
- The purpose of this system is to detect gas leakage, neutralize it, and prevent the explosion.
## WHEN
- Gas detectors can be used to detect combustible, flammable and toxic gases, and oxygen depletion.
## WHERE
- They are commonly used to detect toxic or explosive gases and measure gas concentration.- When gas leaks do occur, they pose serious risks of carbon monoxide poisoning in       people and animals. 
## WHO
- Gas sensors are employed in factories and manufacturing facilities to identify gas leaks, and to detect smoke and carbon monoxide in homes and also in vehicles.
## HOW
- If it detects a gas leak, the LED will light up, the buzzer will activate, then the system will send a notification message stating that there has been an LPG gas leak. If       no LPG gas leak is detected, the system will continue to detect the gas level through the LPG gas sensor until it detects an LPG gas leak.

![image](https://user-images.githubusercontent.com/94245015/144033489-b0d1b180-5273-4bca-8828-fed46b83cd5b.png)

# Components in Block diagram.
## AVR MICROCONTROLLER
 - It contain on chip central processing unit (CPU), Read only memory (ROM), Random access memory (RAM), input/output unit, interrupts controller etc. Therefore a microcontroller is used for high speed signal processing operation inside an embedded system.

## Gas Sensor
 - Gas sensors also known as gas detectors are electronic devices that detect and identify different types of gasses. ... It includes all MQ series gas sensors this module Module can be used to sense Carbon Monoxide and Methane Gas, Hydrogen Gas, etc.

## GSM Module
 - A GSM modem or GSM module is a hardware device that uses GSM mobile telephone technology to provide a data link to a remote network. From the view of the mobile phone network, they are essentially identical to an ordinary mobile phone, including the need for a SIM to identify themselves to the network.

## LED
 - It is a light emitting diode used for the indication.

## Buzzer
 - A buzzer or beeper is an audio signaling device, which may be mechanical, electromechanical, or piezoelectric (piezo for short). Typical uses of buzzers and beepers include alarm devices, timers, and confirmation of user input such as a mouse click or keystroke.

## Exhaust Fan
 - They are used to remove the leaked gas out as a safety measure and are basiclly used to cool places that have suddenly become too hot.


