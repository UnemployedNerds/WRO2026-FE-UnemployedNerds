

# WRO2026-FE-UnemployedNerds
Repository of UnemployedNerds for the 2026 Future Engineers WRO iran national competition 

## The Team


## Araz Abbasi

 - Role : Coder
 - Age : 15
 - Description : Hello everyonee!! im araz im from iran , its my 5th year competing in WRO tournoments,
 im deeply passionate about math/physics and electronics , i also play chess for a hobby rated 1500 in FIDE classical
 - Instagram : araz.abbasi.3
 - Email : arazabbasi830@gmail.com 


 ![MyPhoto]()

## Radin Mirsarvestani

 - Role : Builder/slave
 - Age : 15
 - Description : Hello I'm Radin I'm from Iran Its my 5th year competing in WRO tournoments, I like building and playing war thunder
 - Instagram : Not available
 - Email : radin.mirsarvestani1030@gmail.com


 ![MyPhoto]()
 
 ## Benyamin Nikvarz

 - Role : Coach
 - Age : 20
 - Description : 2nd year electrical engineer been doing robotics since 2016 and ive been coaching this team for 2 years and former WRO competetor
 - Instagram : 
 - Email : benyamin.nikvarz@gmail.com


 ![MyPhoto]()

 ## Golo

 - Role : Mascot
 - Age : ??
 - Meow
 - Instagram : golo_lovers
 - Email : arazabbasi830@gmail.com


![golophoto]()

  ## Our Team Photo
 ![MyPhoto]()
 ## Fun Photo
 ![MyPhoto]()





 
## Quick WRO Future Engineers challenge overview

#### Open Challenge
- Open Challenge: 
The robot must complete laps on a track without obstacles, demonstrating precision in wall-following and line detection.

- Goals : 3 laps

    ![OpenChallenge]()



#### Obstacle Challenge
- Obstacle Challenge
Robot completes laps while avoiding green (left) and red (right) pillars, then parks in the designated zone.
- Goals :  laps + parallel parking

    ![ObstacleChalleng]()
  
## Robot Photos
- front
![frontpic]()
- back
![backpic]()
- left
![leftpic]()
- right
![rightpic]()
- top
![toppic]()
- bottom
![bottompic]()


## Videos 
- open challenge
(place vid here)

- obstacle challenge
(place vid here)

- YouTube Explanation Video  
https://www.youtube.com/watch?v=XXXX


## Platform and Components used
#### Why we chose EV3 brick for the brain of our robot
![medmotor](images/ev3brick.jpg)
- we chose EV3 for its simplicity and versitality , easy sensor integration and fast development and built in safty features
### PROS AND CONS
The LEGO EV3 Brick is a programmable robotics controller based on an ARM9 processor running a Linux-based operating system. It functions as the central control unit, managing sensor input, motor control, and autonomous robot operation.
| **Pros** | **Cons** |
|-----------|-----------|
| Reliable and stable | Limited processing power |
| Precise motor control | Low RAM compared to modern boards |
| Easy sensor integration | No built-in Wi-Fi |
| Supports multiple coding languages | Limited number of ports |
| Large robotics community | Older hardware |
| Fast to prototype with | More expensive for its performance |
| Built-in screen, buttons, and speaker | Not ideal for AI or advanced vision tasks |
| Expandable with Pico/Arduino | Discontinued by LEGO |
- An ARM9 processor
- 64 MB RAM
- 16 MB Flash storage
- A Linux-based operating system
- USB, Bluetooth, and motor/sensor interfaces

#### Components and sensors :
### Motors :

## EV3 Medium Motor

![medmotor](images/mediummotor.jpg)
### Specifications
- **Type:** DC Motor (Medium)
- **Voltage:** 9 V
- **Speed:** 160 RPM
- **Torque:** 20 N·cm (effective torque ≈15 N·cm under the robot's 1.2 kg load)
- **Weight:** 120 g
- **Feature:** Provides propulsion (rear wheels) and steering (front wheels)
# The usuage of medium motor in our robot : 
- Steering
- Controling the rear wheels
- Moving the Ultrasonic sensor
  
### Sensors and modules :
## Hi-technic compasss :
![compass](images/compass.jpg)
### Overview
The HiTechnic Compass Sensor is a digital compass compatible with LEGO EV3 and NXT robots. It uses a built-in **3-axis magnetometer** to detect the Earth's magnetic field and determine the robot's heading.

### How It Works
The sensor continuously measures the Earth's magnetic field and calculates the robot's orientation, returning a heading between **0° and 359°**.

- **0°** → North
- **90°** → East
- **180°** → South
- **270°** → West

This allows the robot to maintain a consistent heading and perform accurate turns, even if wheel slippage occurs.

### Advantages
- High heading accuracy
- Helps compensate for wheel slip
- Fast real-time heading updates
- Simple integration with EV3 programs

### Limitations
- Sensitive to nearby magnets and metal objects
- Can be affected by motor electromagnetic interference
- Measures **magnetic north**, not true north

### Implementation
The compass sensor is mounted away from the drive motors to minimize magnetic interference. During autonomous operation, it provides continuous heading feedback, enabling precise turns and stable navigation throughout the robot's run.
## why we use compass sensor :
- we use the compass sensor for navigation and making the robot head into the direction we want
  
## HiTechnic Color Sensor
![color](colorsensor)

### Overview
The HiTechnic Color Sensor is a digital sensor compatible with LEGO EV3 and NXT robots. It detects the color and intensity of light reflected from nearby objects using built-in red, green, and blue (RGB) LEDs and photodiodes.

### How It Works
The sensor illuminates the target with its RGB LEDs and measures the reflected light. It then compares the detected values to identify the object's color or light intensity.

### Advantages
- Detects multiple colors accurately
- Measures reflected light intensity
- Fast response for real-time object detection
- Easy integration with EV3 programs

### Limitations
- Performance depends on ambient lighting
- Sensor accuracy varies with distance from the object
- Shiny or reflective surfaces can affect readings
- Requires calibration for the best performance

### Implementation
The color sensor is mounted close to the ground to reliably detect colored field markers and surface changes. Its readings are used to trigger navigation events, identify zones, and improve the robot's decision-making during autonomous operation.




why we use piximoon camera insted of other camera

why we use ultra sonic

why we use color sensor

importance of using compass and ultra sonic 
the reason we dont use only ulyrasonic for navigation
we could have use two ultra sonic but we use hitech color sesnsor for 
\diffrance between large motor and meduim motor

