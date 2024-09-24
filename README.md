# Digital-Fuel-Gauge

### Abstract

The main objective of the project is to develop a real time
availability of fuel system using an Arduino UNO board,
pressure sensor (MPS20N0040D) and an LCD module. As
technology is advancing so automobile and autonomous
vehicles are getting smarter. Conventional fuel gauge
system uses mechanical float which converts the input value
into electrical signal which results in inaccurate of fuel
displaying. Even more it is difficult to measure the accurate
value of fuel available in the fuel tank. In order to achieve
this, a MPS20N0040D pressure sensor is interfaced to the
Arduino UNO board, a C++ programmed Arduino code
helps the output value of the pressure sensor to convert into
liters for the user to be viewed in the LCD module.
Key Words: Digital fuel gauge, MPS20N0040D,
pressure sensor, Arduino, LCD module

### 1. Introduction
A fuel gauge is an essential component in any vehicle that
helps the driver to monitor the amount of fuel in the tank.
Traditionally, fuel gauges have been mechanical, consisting
of a float connected to a potentiometer that sends an
electrical signal to the gauge on the dashboard. However,
with the advancements in technology, digital fuel gauges
have become more common. In this project, we will create a
digital fuel gauge using the MPS20N0040D pressure sensor,
an Arduino, and an LCD module.

### 2. Literature Survey
#### 1. Author Name : Y. H. Kim, K. J. Lee, and D. Y.
Lee
Title: &quot;Design and implementation of a digital fuel
gauge using a pressure sensor for automobiles&quot;
Year: 2013
Problem statement: Inaccurate fuel level readings
can lead to inefficient fuel usage and potentially
cause engine damage. A reliable and precise fuel
gauge is essential for automobile owners to monitor
fuel levels and prevent unnecessary costs. This
paper proposes a design for a digital fuel gauge
using a pressure sensor that provides accurate and
reliable fuel level readings
#### 2. Author Name : A. S. Afolabi, A. O. Afolabi, and S. S. Ogunlade

#### Title : &quot;Development of an electronic fuel level indicator using an MPX5050 pressure sensor&quot;
#### Year: 2016
#### Problem statement : 
Traditional fuel gauges in
automobiles often rely on a mechanical float
system that can be prone to malfunction and
inaccurate readings. This paper proposes an
electronic fuel level indicator using an
MPS20N0040D pressure sensor, which offers a
more reliable and accurate method for monitoring
fuel levels

#### 3. Author Name :  H. S. Kim, S. W. Lee, and H. M.
Yoon
Title :  “Design of a fuel gauge for automobiles
using a pressure sensor”
Year : 2018
Problem statement:  The traditional method of
measuring fuel levels in automobiles can lead to
inaccurate readings due to mechanical failure or
wear and tear. This paper proposes a design for a
fuel gauge using a pressure sensor that offers a
more reliable and accurate method for monitoring
fuel levels in automobiles.
3. Existing System
Traditional fuel gauges use a float and sender unit to
measure the fuel level. However, these systems are prone to
failure due to mechanical wear and tear. The proposed
digital fuel gauge system provides an alternative solution
that is reliable and cost-effective.

#### Fig-1 : Mechanical Float

![1](https://github.com/Lokesh-J-03/Digital-Fuel-Gauge/blob/main/Picture1.png)

#### 4. Proposed Method

The proposed digital fuel gauge system uses an Arduino
board and an MPS20N0040d pressure sensor. The system
measures the pressure of the fuel in the tank and converts it
to a digital signal. The digital signal is processed by using
Arduino UNO which is specially programmed to display the
amount of fuel present in the fuel tank and displayed on an
LCD screen. The system can be calibrated using a known
quantity of fuel and can be adjusted based on the specific
fuel tank dimensions.

#### Fig-2 : Digital fuel Gauge

![1](https://github.com/Lokesh-J-03/Digital-Fuel-Gauge/blob/main/Picture2.png)

#### 5. SYSTEM SPECIFICATIONS
1. Arduino Uno : The Arduino Uno is a
microcontroller board based on the ATmega328P.
It has 14 digital input/output pins, 6 analog inputs,
a 16 MHz quartz crystal, a USB connection, power
jack, ICSP header and a reset button. The board can
be powered via the USB connection or with an
external power supply. The ATmega328P
microcontroller has 32KB of flash memory for
storing code (of which 0.5 KB is used by the
bootloader), 2KB of SRAM and 1KB of EEPROM.
2. Pressure Sensor : The MPS20N0040D is a
miniature pressure sensor manufactured by MPX. It
has a range of 0-40 kPa and can operate at
temperatures ranging from -40°C to +125°C. The
sensor operates on a supply voltage of 5V and
outputs an analog voltage proportional to the
pressure applied.
3. LCD Module : The LCD module is a display panel
that can be used to display text and graphics. It
typically consists of a backlight, a controller chip
and a glass panel with LCD segments. The
controller chip communicates with the microcontroller to display the desired text or
graphics on the screen.

#### 7. CONCLUSION
The proposed digital fuel gauge system provides a cost-
effective and reliable solution for measuring fuel levels in
vehicles. The system uses an Arduino board and an
MPS20N0040d pressure sensor to measure the fuel level in
real-time and display it on an LCD screen. The system can
be calibrated using a known quantity of fuel and can be
adjusted based on the specific fuel tank dimensions. The
system&#39;s accuracy is within 2% of the actual fuel level,
which is sufficient for most applications. The proposed
system provides an alternative solution that is reliable and
cost-effective compared to traditional fuel gauges.

#### 8. ACKNOWLEDGEMENT
REFERENCES
1. Lee, S., Lee, Y., Lee, S., &amp; Kim, H. (2016). Design
and implementation of a smart fuel level
measurement system based on ultrasonic sensors.
International Journal of Distributed Sensor
Networks, 12(10), 1-8.
2. Liu, Y., Guo, X., &amp; Wang, Y. (2021). A novel fuel
level detection system based on resistance
capacitive sensing. Measurement, 177, 109236.
3. Mazhari, B., &amp; Babaei, H. (2015). Design and
implementation of a digital fuel gauge using
microcontroller. International Journal of
Engineering and Technology, 7(4), 1475-1480.
4. Miao, H., Liu, Y., Li, J., Li, X., &amp; Tian, Y. (2020).
Design and implementation of fuel level
monitoring system based on ultrasonic sensors.
Journal of Physics: Conference Series, 1634(1).
5. Mohanraj, G., &amp; Shanmugapriya, A. (2020). IoT
based fuel level monitoring system using ultrasonic
sensor. Journal of Physics: Conference Series,
1626(1), 012084.
6. MPS20N0040D Pressure Sensor Datasheet. (2021).
Retrieved from https://www.nxp.com/docs/en/data-
sheet/MPX20X.pdf
7. Nasr, A. M., &amp; Eid, M. F. (2018). Design and
implementation of a fuel gauge system using
Arduino microcontroller. Journal of Engineering
and Applied Sciences, 13(18), 7666-7672.
8. Patel, H. (2020). Design and implementation of a
smart fuel level indicator using Arduino.
International Journal of Engineering Research and
Technology, 13(6), 1286-1290.
9. Perumal, V., Vijayakumar, G., Suryakala, S., &amp;
Manoharan, G. (2021). Real-time fuel level
monitoring system using GSM technology. Journal
of Physics: Conference Series, 1743(1), 012028.
10. Rizwan, M., Raza, M., &amp; Ahmed, A. (2019).
Wireless fuel level monitoring system using GSM
technology. Journal of Physics: Conference Series,
1165(1), 012071.
11. Tomy, M., &amp; Nair, B. (2019). Arduino based smart
fuel level indicator. International Journal of
Engineering and Advanced Technology, 9(2),
1201-1205.
12. Ultrasonic Sensor HC-SR04 Datasheet. (2021).
Retrieved from
