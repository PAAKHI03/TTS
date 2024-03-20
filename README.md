# TTS
#Components:        

1.Arduino board (UNO)          
2.PIR (Passive Infrared) sensor        
3.Speaker      
4.Resistors (for the speaker)    (ig: 220 ohms)      
5.Breadboard      
6.Jumper wires             
7.Capacitor(?) for coupling & filtering           
8. Amplifier (PAM8610 / LM386)     
9.Battery


          +5V -------------- VCC of PIR sensor
           GND -------------- GND of PIR sensor
           Pin 2 ------------- OUT of PIR sensor
           
           Pin 10 ------------ Input of Audio Amplifier
           GND -------------- GND of Audio Amplifier
           Output ------------ Speaker +
           GND -------------- Speaker - via resistor
           
           Vin+ ------------+ 5V from Battery
                             
           Vin- ------------ GND of Battery
                             
           GND ------------ Arduino GND
           +5V ------------ Arduino 5V
