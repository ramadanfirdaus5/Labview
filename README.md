# Labview
Control Temperatur With LABVIEW
WHAT you NEED
n making PID-based room temperature control systems using Labview there is a design that must be done starting with the design of PID controls using Labview, and electronic system design.

In designing electronic systems or hardware components needed include:

Arduino Uno
L298N Motor Driver
Dc With Propeller Motor
Incandescent lamps
Personal Computer / Laptop / PC
Battery LiPo
The applications needed include:

Labview 2016 Or least
Arduino IDE
Lifa <BR>
Lvifa BASE
Visa
For Lifa and Lvifa Base can be downloaded here

After all the components are available, the next thing is to make a room prototype, here we make a room with the size of 17X17 cm by placing an incandescent lamp in the middle of the room which serves as the temperature effector of the system. sensor inside, for flexing sensors you can place as you like in this case we store it right behind the propeller.

To set the rotational speed of the DC motor It takes a driver motorbike that is connected to Arduino, the motor driver must be given an input voltage of 5v and 12v for a voltage of 5V we take from Pin Arduino While 12 comes from LiPo battery

For sensors used in this system we use LM35, this sensor has 3 foot pins, VCC, Ground, and data

pin position

VCC pin DC motor ---------------- >>> mot pin 1 Motor Driver (can be changed as desired)

Gnd pin DC motor ---------------- >>> mot pin 2 Motor Driver (can be changed as desired)

Pin 12V Motor Driver ------------- >>> VCC Lipo Battery

GND Motor Driver Pin ------------- >>> GND Lipo Batery + Gnd Arduino

Pin 5V Motor Driver ---------------- >>> Pin5v ARDUINO UNO

Pin IN Motor Driver ---------------- >>> Pin 9 ARDUINO UNO

Pin EN1 Motor Driver ---------------- >>> Pin 8 ARDUINO UNO

pin VCC Sensor lm35 --------------- >>> 3.3 Pin Arduino

pin lm35 Sensor Data --------------- >>> Pin A0 Arduino

pin GND Sensor lm35 --------------- >>> Arduino GND Pin
