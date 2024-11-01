## Task-1:LTspice and KIcad
  The objective of this task was to figure out how simulation software works and is advantageous. I learnt basic features and got familiar with its user interface as i designed a multivibrator in astable mode using a 555 IC.The goal was to configure the circuit so that the output continuously oscillates between high and low states, producing a square wave.

  In KiCad, a simple LED blinking circuit was designed. The circuit consisted of an LED, a current-limiting resistor, and a power source. The schematic was created.
  
    
  Results:
  ![](https://i.imgur.com/wYMGE9W.png)

  
  ![](https://i.imgur.com/DAaPNV2.jpeg)
  ***
  ## Task 2:Speed control of DC motor
  The objective of this task was to learn about the dual H-Bridge L298D motor driver and to control the speed of a DC motor using PWM

  The L298D motor driver allows control of two DC motors. It uses an H-Bridge configuration,enabling the motor to rotate in both directions. The key feature for speed control is the enable pin, which is used to apply a PWM signal to control the motor speed.
  Results: two dc motors are controlled.
 
  [ link to the video](https://youtu.be/8QKm3JpX9DQ?si=Pcde7WJtFUFkycR-)
  ***
  ## Task 3: Direction control
  The objective of this task was to to control the direction of a DC motor using the L298D driver with  Arduino. This task was pretty muchsimilar to the previous task but changes in the code were made.
  ![](https://i.imgur.com/MaU0kS8.jpeg)
  ![](https://i.imgur.com/kAdNTUJ.jpeg)

  ## Task 6: Temparature Detection
   LM35 temparature sensor was used with arduino.I learnt how it works. it produces analog output voltage that increases by 10mV for every rise in centigrade.
  Result: temparature was detected and read on the serial monitor of Arduino IDE.
  ![](https://i.imgur.com/DEz1B5p.jpeg)
    ![](https://i.imgur.com/nzZjP7a.jpeg)
    ![](https://i.imgur.com/m9bUH5a.jpeg)
  ***
   ## Task 7: Temparature and Humidity Detection
   DHT11 sensor was used in this task along with arduino. It uses a capacitive measurements and converts into digital signalsand thermistor for temparature detection. the working range of this is 0to 50 degrees.    
   Result: Temparature and humidity readings were displayed on the serial monitor.
   ![](https://i.imgur.com/SSANrip.jpeg)
    ![](https://i.imgur.com/nzZjP7a.jpeg)
    ![](https://i.imgur.com/GViljyP.jpeg)
   ***
   ## Task 8 - BLDC Motor And Hall Effect Sensor:
   speed of a brushless dc motor was supposed to be determined in this task. For this, output from a Hall effect sensor was used. The A3144 sensor senses a magnet on the bldc motor and 
   the output of the sensor is high .Arduino serial monitor reads the speed in the unit of rpm.
    ![](https://i.imgur.com/tx8j343.jpeg)
    ![](https://i.imgur.com/mVoalJI.jpeg)
    ***
   ## Task 10: Battery charging:
   A 3 volt Lithium ion battery was charged using a solar panel with a charging board interfacing between the battery and the panel.
   Initial voltage andthe voltage after charging were observed on a multimeter.The TP4056 charging module acts as an interface. it follows the CC/CV method for effective charging.
    ![](https://i.imgur.com/3UINs50.jpeg)
    ![TP4056 charging module](https://i.imgur.com/1OQPnde.jpeg)
   ***
   ## Task 11:Understanding 555 Timer And LDR
   this task involved using a 555 ic and a Light-dependent resistor.It has a resistance of almost 1 mega ohm when it is in total darkness, but its resistance is about 5k ohms when 
  exposed to full brightness. 555 IC is used as a comparator. Output goes high when the non inverting output is greater than inverting output and vice versa.
   ![](https://i.imgur.com/y6IAFZO.jpeg)
   ![](https://i.imgur.com/LvL3sGK.jpeg)
   ***
  ## Task 12: Solar panel
  The objective of this task was to understand the working principle of a solar panel. Semiconductor diodes were used in forward biased condition and connected parallely and checked for 
  voltage produced across the setup.It was experimentally noticed that voltage output was higher when diodes were connected in series than in parallel. 
  ![](https://i.imgur.com/ZTMEzT7.jpeg)
  ***
  ## Task 13 - Solar Tracker
  The objective of this task was to create a sysetem which increases the efficiancy of power generation using a solar panel. Outputs of 2 ldrs were used to turn the solar panel which was 
  mounted on a servo motor,taking inputs from Arduino. The servo moter moves in the direction of the LDR which recieves more light.if condition was used in the code to execute this task.
  The yellow line indicates the shift according to 
  ![](https://i.imgur.com/vL7yoQu.jpeg)
  ![](https://i.imgur.com/HFZC2xk.jpeg)
  ## Task 16: Automatic door opener system.
  PIR sensor which is used in this task works on the principle of Passive infrared detection. it uses a fresnel lens that focuses IR energy onto the sensor.It basically detects heat and 
  a trigger is generated.Arduino is connected to the sensor and helps in the rotation of the servo motor according to the signal generated by the PIR sensor.
  ![](https://i.imgur.com/IwxJArZ.jpeg)
***
## Task 17:  Auto Night Lamp Using LED for Electric Vehicles (EVs)
A BC547 Transistor was used with a LDR and a voltage biasing network. BC547 is a BJT with NPN configurtion. This is a power transistor with a heat sink. It takes input from the LDR and swithes the signal accordingly. 
 ![](https://i.imgur.com/dGA4D9N.jpeg)
