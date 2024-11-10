[Interactive Pinout](https://rusefi.com/docs/pinouts/stim/)

## User Manual

![WhatsApp Image 2024-11-09 at 19 40 01_332a49eb](https://github.com/user-attachments/assets/d9948c5b-21ab-4139-89ac-f6e2a08bd654)

![image](https://github.com/user-attachments/assets/e0727842-1a35-4fec-a06a-08bea15601e5)

![image](https://github.com/user-attachments/assets/3ded6972-6040-4ec6-b87b-4cbae825868f)


* [Download Putty](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html)
* bottom microUSB is required for operation
* top microUSB is sometimes needed for firmware updates
* blinking blue LD2 means "alive"
* red LD3 means "board has failed test
* green LD1 next to blinking blue means "test successful"




See https://github.com/rusefi/rusefi-hardware/tree/main/digital-inputs for firmware

Part of https://github.com/rusefi/rusefi infrastucture

https://github.com/rusefi/rusefi/wiki/dev-hardware-quality-control

![image](https://github.com/rusefi/stim/assets/48498823/09e251f0-d577-47c5-908c-776eeab344c3)



# Digital Inputs
- 48 channels of high/low digital inputs
- pin requirment: 4 ADC inputs and 9 GPIO


GPIO:
* output: x4 address pins
* output: x4 test control pins
* output: mux off




See https://github.com/rusefi/stim/issues/6

![x](overview.png)


# Changelog

## rev C

* CAN board fix
* second CAN board added
* OUT0 pin moved from PA11 to PD8
* https://github.com/rusefi/stim/issues?q=label%3Arev-C+is%3Aclosed

## rev 0.2

* CAN bus
* superseal header

##  rev 0.1
* it works!



