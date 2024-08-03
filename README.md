# Introduction To Electronics & Robotics

*`updated July 3, 2024`*

TOC
1. [Electrical & Electronics Engineering](#electrical-and-electronics-engineering)
2. [Electronics And Robotics](#electronics-and-robotics)
3. [The Microcontroller](#the-microcontroller)
    1. [Arduino UNO](#arduino-uno)
4. [Circuit](#circuit)      
    1. [Two Basic Types of Circuits](#two-basic-types-of-circuits)
    2. [To Series Or To Parallel](#to-series-or-to-parallel)
5. [Some Common Tech Terms](#some-common-tech-terms)
6. [Voltage Vs Amperage](#voltage-vs-amperage)
7. [Arduino and TinkerCAD](#arduino-and-tinkercad)    

## Electrical And Electronics Engineering
> Electrical and electronics engineering, the branch of 
engineering concerned with the practical applications of 
electricity in all its forms, including those of the field
of electronics. Electronics engineering is that branch of 
electrical engineering concerned with the uses of the 
electromagnetic spectrum and with the application of such 
electronic devices as integrated circuits and transistors.
>
> In engineering practice, the distinction between electrical 
engineering and electronics is usually based on the comparative 
strength of the electric currents used. In this sense, electrical 
engineering is the branch dealing with “heavy current”—that is, 
electric light and power systems and apparatuses—whereas 
electronics engineering deals with such “light current” applications
as telephone and radio communication, computers, radar, 
and automatic control systems.

*source: <https://www.britannica.com/technology/electrical-and-electronics-engineering>*

## Electronics And Robotics
Here are some interesting points:

1. **Microcontroller Integration**:
   - Microcontrollers are versatile components that can manage the operations
     of various electronic devices by executing pre-programmed instructions.
   - They serve as the "brain" of electronic devices, allowing for automation
     and complex functionalities.

2. **Programming Electronic Devices**:
   - Programming involves writing code that the microcontroller executes,
     enabling the device to perform specific tasks.
   - This can include tasks like turning LEDs on and off, measuring
     temperature with sensors, controlling motors, etc.

3. **Transition to Robotics**:
   - When electronic devices are equipped with sensors and actuators, and
     programmed to interact with their environment, they move into the realm
     of robotics.
   - Robotics involves the design, construction, operation, and use of robots
     for various applications, from simple automation to complex tasks like
     navigation and manipulation.

4. **Sensors and Actuators**:
   - Sensors gather data from the environment (e.g., temperature, light,
     distance).
   - Actuators perform actions based on sensor data and programmed
     instructions (e.g., moving a robotic arm, turning a wheel).

5. **Applications of Robotics**:
   - Robotics can be applied in numerous fields, including manufacturing,
     healthcare, space exploration, and everyday consumer products.
   - Examples include robotic vacuum cleaners, automated assembly lines,
     medical robots for surgery, and Mars rovers.

## The Microcontroller
> A microcontroller is a compact integrated circuit designed 
to govern a specific operation in an embedded system. A typical
microcontroller includes a processor, memory and input/output 
(I/O) peripherals on a single chip.
> 
> Sometimes referred to as an embedded controller or microcontroller 
unit (MCU), microcontrollers are found in vehicles, robots, office 
machines, medical devices, mobile radio transceivers, vending machines 
and home appliances, among other devices. They are essentially simple 
miniature personal computers (PCs) designed to control small features of 
a larger component, without a complex front-end operating system (OS).

*source: <https://internetofthingsagenda.techtarget.com/definition/microcontroller>*

### Arduino UNO

The Arduino UNO is a widely used microcontroller board designed for building
digital devices and interactive objects. It features an ATmega328P 
microcontroller with 14 digital I/O pins (6 PWM outputs) and 6 analog inputs. 
Operating at 5V with a 16 MHz clock speed, it provides 32 KB flash memory, 
2 KB SRAM, and 1 KB EEPROM. The board supports USB connectivity, 
a power jack, ICSP header, and a reset button. 

#### Pros:
- user-friendly for beginners
- extensive community support
- versatile with many compatible sensors and shields
- open-source hardware and software

#### Cons:
- limited processing power
- limited memory
- basic built-in connectivity options

The Arduino UNO is perfect for those starting with electronics and 
prototyping, offering a robust platform for learning and development.

![image](https://github.com/user-attachments/assets/a3207b29-0b7a-4472-a237-f30d59abf75b)

*image source: <https://circuitdigest.com/sites/default/files/field/image/Arduino-UNO-Description.png>*

## Circuit
> In electronics, a circuit is a closed path that allows 
electricity to flow from one point to another. It may include various
electrical components, such as transistors, resistors, 
and capacitors, but the flow is unimpeded by a gap or 
break in the circuit.

*source: <https://techterms.com/definition/circuit>*

![basic-electrical-circuit](https://github.com/user-attachments/assets/08221a3f-ab19-4ce8-9d89-1013add1a15b)

*image source: <https://electricalacademia.com/wp-content/uploads/2018/09/tech-lesson-11-5a-electricity-and-circuits-basic-electrical-circuit-diagram-400x300.jpg>*

### Two Basic Types of Circuits
![series-parallel-circuits](https://github.com/user-attachments/assets/f002b18d-406a-42ee-bc71-24d51e959938)

*image source: <https://cdn1.byjus.com/wp-content/uploads/2020/06/series-and-parallel-circuit.png>*

Series Circuit
> a series circuit comprises a path along which the 
whole current flows through each component. 

Parallel Circuit
> a parallel circuit comprises branches so that the 
current divides and only part of it flows through any branch.

*source: <https://www.britannica.com/technology/electric-circuit#ref22644>*

### To Series Or To Parallel
- **Voltage Requirements**:  
  Series circuits are used to achieve specific voltage drops across
  components, while parallel circuits maintain consistent
  voltage across all connected components.

- **Current Handling**:  
  Parallel connections distribute current among multiple paths, making
  them suitable for applications where multiple components need
  to share the load. In contrast, series connections ensure that
  the same current flows through all components.

- **Reliability and Redundancy**:  
  Parallel circuits offer increased reliability and redundancy. If one
  component fails, others continue to operate, which is essential for
  applications needing high availability.

- **Design Goals**:  
  The design choice is driven by the desired characteristics such as
  stability, flexibility, and protection. It’s about meeting the
  specific performance and functional requirements of the device or circuit.

## Some Common Tech Terms
`open circuit` - an electrical circuit that is not complete.

`electric current` -  the rate at which electric 
charge flows past a point on the electric circuit. 

`ground` - In electronics and electrical engineering, it is 
by convention, we define a point in a circuit as a reference
point. This reference point is known as ground (or GND) and
carries a voltage of 0V. Voltage measurements are relative 
measurements. That is, a voltage measurement must be compared
to another point in the circuit. If it is not, 
the measurement is meaningless. 

*source: <https://www.allaboutcircuits.com/technical-articles/an-introduction-to-ground/>*

An earth ground is when a circuit has a physical connection to 
the earth, in order to sink electrons, thereby saving lives.
When an electrical system has a direct connection to
the earth ground (the 3-prong plug: one is positive,
one is negative, one is the earth ground prong),
instead of the flow of charge going 
to our bodies in some instances, it will go directly to
earth ground. 

*source: <http://www.learningaboutelectronics.com/Articles/Why-does-a-circuit-always-have-to-have-ground>*

*FYI - Even though one side of the circuit is the live wire,
you CANNOT simply touch it even there is no apparent neutral wire
completing the circuit: you yourself is standing 
on the earth ground!
A bird will not be shocked by landing on a live wire because
it is not touching the ground, so even if there is the live
wire, there is no return path completing the circuit
and there is no electric shock.*

*source: <https://www.ibiblio.org/kuphaldt/electricCircuits/DC/DC_3.html>*

![electric-shock](https://github.com/user-attachments/assets/a04a9333-a1e2-4870-b7b6-0485ab2014ae)

*image soure: <https://www.ibiblio.org/kuphaldt/electricCircuits/DC/00056.png>*

`hot wire` (electrical term) - carries the electricity, also called `live wire`

`terminal` - is the point at which a conductor from a component, device or 
network comes to an end. It is the point other components can be connected.

## Voltage Vs Amperage

Voltage and amperage are two measures of electrical current or the flow of electrons. 
`voltage` is a measure of the pressure that allows electrons to flow, 
while `amperage` is a measure of the volume of electrons.

*source: <https://www.thespruce.com/amperage-not-voltage-kills-1152476#:~:text=Voltage%20and%20amperage%20are%20two,of%20the%20volume%20of%20electrons.>*

`volt` - The SI unit of electromotive force. It represents the potential
difference that would drive one ampere of current against one ohm of resistance.

`ampere` - The SI base unit of electrical current.

## Arduino and TinkerCAD
Arduino is a prototyping platform consisting of both
hardware and software. When we say `prototyping`,
we want to create a working model first before
we build the actual product, so that we can test
first whether our idea will work and to reduce the
cost of building the product.

TinkerCAD is an online simulator for our circuit
designs. It's just like you are in a Robotics
laboratory and there is the complete setup, but
this time, it's just virtual. And since it is
accessible through a browser, all you need is 
a device with a browser and an Internet connection
and you are good to go: no further setup, 
no additional downloads.

## More Of My Content
- [jdevfullstack Profile](https://github.com/jdevfullstack)
- [jdevfullstack Repos](https://github.com/jdevfullstack?tab=repositories)
- [jdevfullstack Projects](https://github.com/jdevfullstack-projects)
- [jdevfullstack Tutorials](https://github.com/jdevfullstack-tutorials)
