
# _Automatic Water Level Controller_

# Table Of Content:

   # ABSTRACT

Water Monitoring System is an IoT based Liquid Level Monitoring system that has the mechanism to keep the user alerted in case of liquid overflow or when tank depletes. The water tanks can be fixed with ultrasonic sensors that is placed over the container. Ultrasonic sensor is used to measure, compare container depth and liquid level.

The status of the system could be monitored by a LCD screen or a web page that provides a brilliant graphical representation. Colours are used to depict various scenarios with respect to the amount of liquid in the tanks or containers and the buzzer buzzes when the limit exceeds the permissible quantity of fill.

# Identifying features:

  * Living in an era where we need to save more electricity, a water level controller is ideal at saving power.
  * A water level controller helps save money by limiting the waste of water and electricity.
  * Another notable advantage with these devices is that they regulate on their own.

 # JUSTIFICATION:
 
 Automatic water level monitor came into existence because of human error and inconsistence that is associated with manually operated waterpumping machine. This is because it takes time for individual who is manually operating the water pump to turn off the pumping machine and this may cause water spillage and at times the individual might not know that the water level has drop so low until the tank is completely empty.This was the problem that leads to the development of the ideal of anautomatic water level control and automatic pump short down.
 
#  CONSTRAINS:

 The biggest setback experience during the course of this project is difficulties in finding the design of the project,
 secondly sourcing of material and component I used for the project.

# Advantages:
  * Easy installation. 
  * Low maintenance. 
  * Compact and elegant design.
  * Users can control the required level of water in over head tank. 
  * Avoids wastage of water from tanks.  It can maintain exact preset water levels. 
  * The  system  is  very  versatile,  a  numbers  of  tailor  made  variations  like  control  of multiple tanks or multiple pumps are possible. 
  * Being automatic saves man power.

# Applications:
  
  * Used in buildings where the manual monitoring is difficult. 
  * Used in industries to control the water level and in chemical mixing etc. 
  * It can be installed in metro cities where the drinking water is the only water used for all purposes which keeps the drinking water from being wasted.
  
* # Requirement for this device :
   * Good water supply  
* # Hardware Requirements/ Components :

   * AVR MICROCONTROLLER:
     * it contain on chip central processing unit (CPU), Read only memory (ROM), Random access memory (RAM), input/output unit, interrupts controller etc. Therefore a microcontroller is used for high speed signal processing operation inside an embedded system.
     
   * TRANSISTOR:
     * A transistor is a semiconductor device used to amplify or switch electrical signals and power. The transistor is one of the basic building blocks of modern electronics. It is composed of semiconductor material, usually with at least three terminals for connection to an electronic circuit

   
   * DIODE AND LED:
      * A Diode is the simplest two-terminal unilateral semiconductor device. It allows current to flow only in one direction and blocks the current that flows in the opposite         direction. The two terminals of the diode are called as anode and cathode. The characteristics of a diode closely match to that of a switch. An ideal switch when open does 	not conduct current in either directions and in closed state conducts in both directions. Ideally, in one direction that is indicated by the arrow head diode must behave short  circuited and in other one that opposite to that of the direction of arrow head must be open circuited. By ideal characteristics, the diodes is designed to meet these features    theoretically but are not achieved practically. So the practical diode characteristics are only close to that of the desired
     
   * BUZZER:
      * An audio signaling device like a beeper or buzzer may be electromechanical or piezoelectric or mechanical type. The main function of this is to convert the signal from         audio to sound. Generally, it is powered through DC voltage and used in timers, alarm devices, printers, alarms, computers, etc. Based on the various designs, it can generate     different sounds like alarm, music, bell & siren.
   
   * RESISTOR:
      * A resistor is a passive two-terminal electrical component that implements electrical resistance as a circuit element. Resistors act to reduce current flow, and, at the         same time, act to lower voltage levels within circuits. Resistors may have fixed resistances or variable resistances, such as those found in thermistors, trimers, photo           resistors and potentiometers. The current through a resistor is in direct proportion to the voltage across the resistor's terminals. This relationship is represented by Ohm's     law in I is the current through the conductor in units of amperes, V is the potential difference measured across the conductor in units of volts, and R is the resistance of       the conductor in units of ohms (symbol: Ω). 
      * Fixed value resistor:
        Fixed value resistors are those types of resistors whose value is fixed already while manufacturing and cannot be changed during its usage
        
       * HOW TO READ RESISTORS VALUES
        #  
       | Brown | Red  | Orange | Yellow | Green |  Blue | Violet | Gray | White |
       |-------|------|--------|--------|-------|-------|--------|------|-------|
       |   1   |  2   |   3    | 4      |  5    |   6   |  7     |  8   |   9   |

       
       Must resistor have four bands1.
 
        * The first band gives the first digit2. 
 
        * The second band gives the second digit3. 
 
        * The third indicate the4. 
 
        * The fourth band is use to show the tolerance of the resistor. 

   * RELAY:
      * Relays are most commonly used switching device in electronics. There are two important parameters of relay, first is the Trigger Voltage, this is the voltage required to       turn on the relay that is to change the contact from Common → NC to Common → NO. The other parameter is your Load Voltage & Current, this is the amount of voltage or current       that the NC, NO or Common terminal of the relay could withstand, in our case for DC it is maximum of 30V and 10A. Make sure the load you are using falls into this range 
      
   * POWER SUPPLY:
     * A power supply is an electrical device that supplies electric power to an electrical load. The main purpose of a power supply is to convert electric current from a source to the correct voltage, current, and frequency to power the load. As a result, power supplies are sometimes referred to as electric power converters.

   * LIQUID CRYSTAL DISPLAY(LCD):
     * LCD modules are very commonly used in most embedded projects, the reason being its cheap price, availability and programmer friendly. Most of us would have come across these displays in our day to day life, either at PCO’s or calculators. The appearance and the pinouts have already been visualized above now let us get a bit technical.
     * 16×2 LCD is named so because; it has 16 Columns and 2 Rows. There are a lot of combinations available like, 8×1, 8×2, 10×2, 16×1, etc. but the most used one is the 16×2 LCD. So, it will have (16×2=32) 32 characters in total and each character will be made of 5×8 Pixel Dots.  A Single character with all its Pixels is shown in the picture.
     * Now, we know that each character has (5×8=40) 40 Pixels and for 32 Characters we will have (32×40) 1280 Pixels. Further, the LCD should also be instructed about the Position of the Pixels. Hence it will be a hectic task to handle everything with the help of MCU, hence an Interface IC like HD44780is used, which is mounted on the backside of the LCD Module itself. The function of this IC is to get the Commands and Data from the MCU and process them to display meaningful information onto our LCD Screen. You can learn how to interface an LCD using the above  mentioned links. If you are an advanced programmer and  would like to create your own library for interfacing your Microcontroller with this LCD module then you have to understand the HD44780 IC is working and commands which can be found its datasheet.

   * HC-SR04 Ultrasonic Sensor:
     * 	Ultrasonic Sensor Pinout Configuration
 #
|Pin Number	|Pin Name	|Description                                                                                                                                   |
|:--------------|:--------------|:---------------------------------------------------------------------------------------------------------------------------------------------|
|   1		|Vcc	        |The Vcc pin powers the sensor, typically with +5V|
|   2		|Trigger	|Trigger pin is an Input pin. This pin has to be kept high for 10us to initialize measurement by sending US wave.|
|   3		|Echo	        |Echo pin is an Output pin. This pin goes high for a period of time which will be equal to the time taken for the US wave to return back to the                                    sensor.|
|   4		|Ground	        |This pin is connected to the Ground of the system.|

   * As shown above the HC-SR04 Ultrasonic (US) sensor is a 4 pin module, whose pin names are Vcc, Trigger, Echo and Ground respectively. This sensor is a very popular sensor used in many applications where measuring distance or sensing objects are required. The module has two eyes like projects in the front which forms the Ultrasonic transmitter and Receiver. The sensor works with the simple high school formula that
Distance = Speed × Time
   * The Ultrasonic transmitter transmits an ultrasonic wave, this wave travels in air and when it gets objected by any material it gets reflected back toward the sensor this reflected wave is observed by the Ultrasonic receiver module 

*_etc_*...

* # HIGH LEVEL REQUIREMENTS
#
| ID   | DESCRIPTION                                           |
|------|-------------------------------------------------------|
|HL1   | Sensor to detect the water level in the tank          |
|HL2   | sensor to send high medium low level info to arduino  |
|HL3   | buzzer to alert the macchine to sart n stop           |

* # LOW LEVEL REQUIREMENT
#
| ID  |  DESCRIPTION                                          |
|-----|-------------------------------------------------------|
|LL1  | Machine to work according to instructions             |
|LL2  | LED to show the message on display                    | 
|LL3  | Easy to use and save water & electricity              |

# System Flow Chart:

   ![System flow chart](https://user-images.githubusercontent.com/98880912/156942110-8f4ee244-3416-49c7-93b9-bb268ebe4a68.png)
   
# System Block Diagram:

# 4W'S & 1H
 * # WHY
     * A water level controller helps save money by limiting the waste of water and electricity
 * # WHO
   * Everyone can use this device as for their commercial aur domestic use 
 * # WHEN
   * Whenerver the tank level gets low high it starts and stops according to the requirements
 * # WHAT
   * Result's into less manual work which saves human time and energy.
 * # HOW
   *  By setting these devices as per the requiement so as to save the loss of water and and save the motor from dry run and manual work load.
# SWOT Analysis:
  
  * STENGTH:
    * Regulates water flow &  optimizes machine performance.
    * Rduces man power which gives human a relief. 
    
  * WEAKNESS:
    * Due to lack of short circuit protection it can lead to burning.
    * Needs to be changed After 6-7 years gap.
    
  * OPPORTUNITIES:
    * Ease at mannual work & money as well as power saver.
    * In future we can get a best market value for this product.

  * THREATS:
  
# Test Plan & Output:

* The water level is full – Nothing happens
* Water level drops to the reference probe – Alarm is triggered
* Fill start is triggered automatically turning on the water to fill the tank
* Once the water is full, fill stop is triggered and the system automatically stops the pump
* The system resets and waits for water levels to drop again

# Goals of this project :
  * _To reduce the wastage of water across the city_
  * _To provide better water supply to the people_


```js
  ____                   __        __    _
 / ___|  __ ___   _____  \ \      / /_ _| |_ ___ _ __
 \___ \ / _` \ \ / / _ \  \ \ /\ / / _` | __/ _ \ '__|
  ___) | (_| |\ V /  __/   \ V  V / (_| | ||  __/ |
 |____/ \__,_| \_/ \___|    \_/\_/ \__,_|\__\___|_|
  ____                    _     _  __
 / ___|  __ ___   _____  | |   (_)/ _| ___
 \___ \ / _` \ \ / / _ \ | |   | | |_ / _ \
  ___) | (_| |\ V /  __/ | |___| |  _|  __/
 |____/ \__,_| \_/ \___| |_____|_|_|  \___|

```
