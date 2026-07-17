# WRO2026-FE-UnemployedNerds

Repository of **Team UnemployedNerds** for the **2026 World Robot Olympiad (WRO) Future Engineers – Iran National Competition**.

---

# Table of Contents

- [The Team](#the-team)
  - [Araz Abbasi](#araz-abbasi)
  - [Radin Mirsarvestani](#radin-mirsarvestani)
  - [Benyamin Nikvarz](#benyamin-nikvarz)
  - [Golo](#golo)
  - [Our Team Photo](#our-team-photo)
  - [Fun Photo](#fun-photo)

- [Quick WRO Future Engineers Challenge Overview](#quick-wro-future-engineers-challenge-overview)
  - [Open Challenge](#open-challenge)
  - [Obstacle Challenge](#obstacle-challenge)

- [Robot Photos](#robot-photos)

- [Videos](#videos)

- [Platform and Components Used](#platform-and-components-used)
- [Robot](#robot)
- [Robot Software](#robot-software-aspect)

---

# The Team

## Araz Abbasi

- **Role:** Programmer
- **Age:** 15

Hello! I'm **Araz Abbasi** from Iran. This is my fifth year participating in the World Robot Olympiad. I have a strong passion for mathematics, physics, electronics, and programming. Outside of robotics, I enjoy playing chess and currently hold a **1500 FIDE Classical** rating.

- **Instagram:** araz.abbasi.3
- **Email:** arazabbasi830@gmail.com

![MyPhoto]()

---

## Radin Mirsarvestani

- **Role:** Mechanical Designer & Builder
- **Age:** 15

Hello! I'm **Radin Mirsarvestani** from Iran. This is also my fifth year competing in the World Robot Olympiad. I enjoy designing and building robots, and in my free time I like playing War Thunder.

- **Instagram:** Not Available
- **Email:** radin.mirsarvestani1030@gmail.com

![MyPhoto]()

---

## Benyamin Nikvarz

- **Role:** Coach
- **Age:** 20

I'm currently studying Electrical Engineering and have been involved in robotics since 2016. This is my second year coaching Team UnemployedNerds. Before becoming a coach, I also competed in the World Robot Olympiad, which allows me to share valuable experience with the team.

- **Instagram:**
- **Email:** benyamin.nikvarz@gmail.com

![MyPhoto]()

---

## Golo

- **Role:** Team Mascot
- **Age:** Unknown

Golo is the official mascot of Team UnemployedNerds and provides emotional support during long building and programming sessions.

- **Instagram:** golo_lovers
- **Email:** arazabbasi830@gmail.com

![golophoto]()

---

## Our Team Photo

![MyPhoto]()

---

## Fun Photo

![MyPhoto]()

---

# Quick WRO Future Engineers Challenge Overview

## Open Challenge

The objective of the Open Challenge is to complete **three autonomous laps** around the track without obstacles. The robot must demonstrate accurate wall-following, reliable line detection, and smooth navigation while maintaining consistent speed.

**Goal:** Successfully complete 3 laps.

![OpenChallenge]()

---

## Obstacle Challenge

In the Obstacle Challenge, the robot must complete multiple autonomous laps while avoiding **green** and **red** pillars placed throughout the course. Green pillars must be passed on the **left**, while red pillars must be passed on the **right**. After completing the required laps, the robot must finish by parking inside the designated parking zone.

**Goal:** Complete all laps and perform a successful autonomous parallel parking maneuver.

![ObstacleChallenge]()
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

- obstacle challengee
(place vid here)

- YouTube Explanation Video  
https://www.youtube.com/watch?v=XXXX


# Robot Photos

Below are photographs of our robot from different angles to provide a complete overview of its mechanical design and construction.

### Front View

![frontpic]()

### Rear View

![backpic]()

### Left Side

![leftpic]()

### Right Side

![rightpic]()

### Top View

![toppic]()

### Bottom View

![bottompic]()

---

# Videos

### Open Challenge

*(Insert Open Challenge video here.)*

### Obstacle Challenge

*(Insert Obstacle Challenge video here.)*

### Full Robot Explanation

https://www.youtube.com/watch?v=XXXX

---

# Platform and Components Used

## Why We Chose the LEGO EV3 Brick

![medmotor](images/ev3brick.jpg)

The LEGO Mindstorms EV3 Brick serves as the central controller of our robot. Although it is an older platform, we selected it because of its reliability, simplicity, and excellent compatibility with LEGO hardware and third-party sensors.

The EV3 allowed us to rapidly prototype, test, and improve our robot throughout the development process while maintaining a stable and dependable control system.

### Advantages

- Reliable and stable platform
- Easy integration with LEGO and third-party sensors
- Precise motor control
- Supports multiple programming languages
- Large robotics community with extensive documentation
- Fast development and debugging
- Built-in display, buttons, and speaker
- Expandable using external microcontrollers such as Arduino or Raspberry Pi Pico

### Disadvantages

- Limited processing power
- Only 64 MB of RAM
- Limited Flash storage
- No built-in Wi-Fi
- Limited number of sensor and motor ports
- Discontinued by LEGO
- Not suitable for advanced AI or computer vision applications

### Technical Specifications

The LEGO EV3 Brick features:

- ARM9 Processor
- 64 MB RAM
- 16 MB Flash Storage
- Linux-based Operating System
- USB and Bluetooth Connectivity
- Four Sensor Ports
- Four Motor Ports

Despite its hardware limitations, the EV3 provides everything required for reliable autonomous navigation in the WRO Future Engineers competition.

---

# Components and Sensors

## Motors

### LEGO EV3 Medium Motor

![medmotor](images/mediummotor.jpg)

### Specifications

- **Type:** Medium DC Servo Motor
- **Operating Voltage:** 9 V
- **Maximum Speed:** 160 RPM
- **Maximum Torque:** 20 N·cm
- **Effective Torque Under Load:** Approximately 15 N·cm
- **Weight:** 120 g

### Purpose in Our Robot

We use three EV3 Medium Motors:

- Steering the front wheels
- Driving the rear differential
- Rotating the ultrasonic sensor during wall-following

The medium motor provides an excellent balance between speed and torque, making it more suitable than the large EV3 motor for our lightweight robot.

---

# Sensors and Modules

## HiTechnic Compass Sensor

![compass](images/compass.jpg)

### Overview

The HiTechnic Compass Sensor is a digital compass designed for LEGO EV3 and NXT robots. It measures the Earth's magnetic field using an internal three-axis magnetometer, allowing the robot to determine its heading accurately.

### Operating Principle

The sensor continuously calculates the robot's heading and returns an angle between **0° and 359°**.

- **0°** → North
- **90°** → East
- **180°** → South
- **270°** → West

Unlike wheel encoders, the compass remains accurate even if wheel slippage occurs during turns.

### Advantages

- High heading accuracy
- Excellent long-term stability
- Real-time heading updates
- Compensates for wheel slip
- Easy integration with EV3

### Limitations

- Sensitive to nearby magnetic fields
- Can be affected by electric motors
- Measures magnetic north rather than true north

### Implementation

The compass sensor is mounted away from the drive motors to minimize magnetic interference. During autonomous operation, it continuously provides heading feedback, allowing our robot to perform accurate turns and maintain a stable driving direction.

### Why We Use It

The compass sensor enables the robot to maintain precise orientation throughout both challenges, even after collisions or wheel slip.

---

## HiTechnic Color Sensor

![color](images/colorsensor.jpg)

### Overview

The HiTechnic Color Sensor detects colors and reflected light intensity using integrated RGB LEDs and photodiodes. It is primarily responsible for detecting the blue and orange field markings used throughout the competition.

### Operating Principle

The sensor illuminates the surface with red, green, and blue light before measuring the reflected intensity. The measured values are then used to classify the detected color.

### Advantages

- Accurate color recognition
- Fast response time
- Measures reflected light intensity
- Easy integration with EV3

### Limitations

- Performance depends on lighting conditions
- Sensor accuracy varies with distance
- Reflective surfaces can affect readings
- Requires calibration before competition

### Implementation

The sensor is mounted close to the ground to maximize detection accuracy. It detects colored markers that indicate turning points and navigation events.

### Why We Use It

The color sensor reliably detects the blue and orange strips on the competition field, allowing the robot to determine when to perform turns and other navigation actions.
## Pixy2 Vision Sensor
![pixycam](images/pixy2.jpg)
### Specifications

| **Property** | **Value** |
|--------------|-----------|
| Type | Vision Sensor |
| Microcontroller | NXP LPC4330 (Dual-Core ARM Cortex-M4/M0) |
| Resolution | 1296×976 (processed at 640×480) |
| Frame Rate | Up to 60 FPS |
| Field of View | 80° Horizontal, 40° Vertical |
| Power Supply | 5 V, 130–170 mA |
| Interface | Custom I2C (port 4) |
| Color Signatures | Up to 7 programmable |
| Features | Object Detection, Color Tracking, Line Tracking, Barcode Detection |

### Overview

The Pixy2 Vision Sensor provides real-time object recognition and color tracking while processing images internally, reducing the computational load on the EV3 Brick. It is mounted above the robot and connected through a custom I2C interface to the EV3 sensor port (`port 4`).

### Implementation

For the Obstacle Challenge, Pixy2 detects:

-  **Green Pillars** – Signature 2
-  **Red Pillars** – Signature 1

The camera operates at up to **60 FPS**, providing fast and reliable object detection. Objects are filtered using their **X** and **Y** coordinates to eliminate false detections before generating steering corrections for obstacle avoidance.

### Advantages

- High-speed processing (up to 60 FPS)
- Detects up to seven programmable color signatures
- Built-in image processing reduces EV3 CPU usage
- Supports line tracking and barcode detection
- Easy integration through I2C

### Limitations

- Performance depends on lighting conditions
- Requires color calibration using PixyMon
- Similar colors may occasionally be misidentified

### Lessons Learned

Accurate color calibration in **PixyMon v2** was essential for reliable detection. Maintaining consistent lighting conditions significantly improved performance. Future versions of the robot may utilize Pixy2's built-in line-tracking mode for the Open Challenge.

### Implementation Impact

Pixy2 achieved approximately **97% detection accuracy** during testing, resulting in smoother steering corrections, more reliable obstacle avoidance, and fewer collisions throughout autonomous operation.


### why we use the pixy2 camera insted of other vision sensors
- **Onboard Processing** – Reduces the computational load on the main controller.
- **Fast Performance** – Up to 60 FPS for quick object detection and tracking.
- **Low Latency** – Provides fast response for real-time robotics applications.
- **Easy Integration** – Supports I2C, SPI, UART, and USB communication.
- **Reliable Color Detection** – Accurately tracks pre-trained color signatures under varying lighting conditions.
- **Compact & Efficient** – Lightweight, low-power, and designed specifically for robotics.
## Ultra sonic sensor 
The LEGO Mindstorms EV3 Ultrasonic Sensor measures the distance to objects without making physical contact. It works by emitting high-frequency ultrasonic sound waves (above the range of human hearing) and measuring the time it takes for the sound to bounce off an object and return to the sensor. Using the speed of sound, the EV3 calculates the distance between the sensor and the object.

### How It Works

1. The sensor emits a short ultrasonic pulse.
2. The sound wave travels through the air.
3. When the wave hits an object, it reflects back to the sensor.
4. The sensor measures the time between sending and receiving the pulse.
5. The EV3 calculates the distance using the speed of sound.

### Features

- **Measurement Range:** Approximately **3–250 cm**
- **Contact-Free Detection:** Measures distance without touching objects.
- **Real-Time Measurements:** Provides fast updates for autonomous navigation.
- **Wide Detection Angle:** Detects objects within a broad field of view.
- **Easy Integration:** Fully compatible with the LEGO Mindstorms EV3 platform.

### Common Applications

- Obstacle detection and avoidance
- Wall following
- Distance measurement
- Autonomous robot navigation

### Advantages

- Accurate and reliable for most robotics applications.
- Simple to program and integrate.
- Works in both bright and dark environments since it uses sound instead of light.

### Why we use the ultra sonic sensor
We use the ultrasonic sensor for wall following and navigation throughout the challenge 

## Importance of using compass and ultrasonic coombined
### What happens if we only use ultrasonic :
the reason we dont use only ultrasonic for navigation is that the sensor alone isnt reliable bcz the waves can scatter etc
### What happens if we only use compass :
the reason we dont use only compass for navigation is : we can only see the direction were heading not how far we are from the walls
### our solution :
we combine both the sensor so we can keep our distance with the wall and also move in the direction we want
## Robot 
## Robots mechanical aspect 
### Rear wheels mechanism 
we use a diffrencial mechanism like this to move the robot forward or backwards:


![diffrencial](images/diffrencialrobo.png)

the diffrencial is connected to a rod that is spinning at a gear ratio of 24:8 so its prodoucing 3x the speed that the motor is inputing

we used a lego EV3 medium motor for spinning the diffrencial , why not use a large motor u may ask?
### difrence between the large and medium motor and why we used the medium over the large? :
- diffrence :
  the large motor is slower but it prodouces more power
  
- speed :
  speed is a huge factor in both the open and obstacle test while the large motor prodouces alot of power it isnt useful for the speed factor bcz its slower than medium motor
  the medium motor is faster than the large motor and our gear ratio for the diffrencial combined with the medium motor allows us to finish the tests faster , our avg time completing the open challenge is 36-40 secs   thanks to this
- size :
- size is also a huge factor , a large motor is almost twice the size of a medium motor we cannot easily fit the motor  on our robots structure bcz it will excueed the length limit
### Steering mechanism :
we use a simple steering mechanism like this :
the motor spins a 16 ridged gear to spin a 64 ridged gear which spins the wheels
## Mobility Management

Our robot’s mobility architecture is designed to balance the non-holonomic constraints of a car-like platform with the need for high-speed, precision path-tracking. The design process focused on three critical areas: drivetrain efficiency, steering geometry, and dynamic stability.

### 1. Drivetrain & Gear System Optimization
The drivetrain was developed to optimize the torque-to-speed ratio, ensuring consistent performance across varying track segments.

*   Engineering Challenge: Initial experiments with a high-speed 40T to 8T gear ratio revealed that while peak theoretical velocity was high, the robot struggled to overcome static inertia. The motors frequently reached their stall torque limit during acceleration, leading to poor start times and delayed recovery after sharp turns.
*   Iterative Optimization: We shifted from a focus on "top speed" to "accelerative efficiency." By testing a range of gear ratios, we selected a configuration (Final Ratio: **[insert ratio here]**) that provides sufficient torque to overcome drivetrain losses while maintaining high cruise velocity.
*   Result: This balance ensures the robot maintains constant acceleration throughout the course, prevents the motor driver from overheating under load, and improves the consistency of the robot’s PID controller by providing a more predictable speed curve.

### 2. Steering System & Control Precision
Steering accuracy is fundamental for a non-holonomic vehicle. Any mechanical error in the steering system introduces noise into our path-following algorithms.

*   The Rack-and-Pinion Limitation: We initially implemented a rack-and-pinion system for its compact profile. However, empirical testing identified backlash as a critical failure point. This mechanical play caused the steering angle to deviate from the commanded value, leading to oscillations in our trajectory and significant path-tracking errors.
*   Custom Linkage Redesign: To solve this, we developed a custom linkage mechanism. This design provides higher structural stiffness and a near-linear relationship between motor PWM and steering angle.
*   Impact on Control: By minimizing backlash, we achieved more reliable "return-to-center" behavior. This allows our control loop to function with higher gain without inducing instability, resulting in smoother obstacle avoidance and significantly reduced overshoot during high-speed maneuvers.

### 3. Chassis & Dynamic Stability
To maintain traction and minimize sensor noise, we engineered the chassis with a focus on center-of-mass and structural rigidity.

*   Mass Centralization: We systematically lowered the Center of Gravity (CoG) by mounting the EV3 Brick and battery pack at the lowest possible point. This configuration minimizes body roll during rapid direction changes and ensures the tires maintain optimal contact with the track surface.
*   Reducing Polar Moment of Inertia: Heavy components were centralized longitudinally. By reducing the polar moment of inertia, we decreased the torque required by the steering motor to yaw the chassis. This makes the robot's directional response faster and more repeatable.
*   Structural Integrity: The chassis frame is cross-braced to prevent structural flex. This rigidity is essential for consistent geometry, ensuring that wheel alignment remains stable regardless of acceleration or cornering forces, which is vital for long-term path-tracking accuracy.

***
## Robot Software aspect
### Code platform
we use lego mindstorm ev3 for coding the robot
- pictures of lego mindstorm ev3 :
  ![]()

### libraries
- all the libraries used will be uploaded
## Code explained

### Open challenge
so the code for our open challenge is 3 parts
- part 1 : the setup
  ![setup](images/setup)
 what setup does is that first it moves the all the way to the right then all the way to the left then it measures how much the wheels have traveled the takes the value and divides the value in 2 and gives it to the steering value in servo to straighten the wheels
- part 2 : Servo , servo handles everything
  ### rearwheel code
  ![rearwheels](images/rearwheels)
  -
  so here we handle the robots speed
  we take a power value multiply it by -1 ( why -1? cuz we messed up with the gears and stuff) and give it to the rotation speed of motor D
  -
  ### steering code
  ![steering](images/steerPD)
  so for steering the robot we dont just give a number to the motor and call it steering , we use a PD algorithm like the picture is showing
  -
  ![servo](images/servo)
  heres servo fully, the two codes run simultaneously together creating the servo
  
- part 3 : open challenge management
  
  
  ![openchallenge](images/openchallenge.png)
  -
  so the area circled in purple are the starting variables, the variables named kp and kd are the constants multiplied in the steering PD formula , the variable named 4 is storing the value that the ultrasonic sensor reads in cm , power is basically speed and steer is the steering value in general
  ### CCW and CW
  so areas circled in blue and orange are our main blocks for handling the open challenge
  the area circled in blue , CCW or Counter Clock Wise is in the job of handling the round when its counter clock wise
  ### CCW
  so each CCW and CW blocks are mainly 2 parts
  - first part :
  
  ![CCW](images/rlccw)
  - the part circled in red :
   this part basically the motor in control of the ultrasonic sensor in left so the ultrasonic can follow the non changable wall ( the outside wall)
  - the part circled in green :
    this part measures how much the ultrasonic sensor is reading and makes a desicion for steering the wheel based on that and its connected to a switch for the desicion making (like the switches in C++)
  - the part circled in blue :
    this block basically gives a steering value and tells the D motors how much to move forward or backwards
    ![move](images/motordriver.png)
 
    
    the part circled in blue are the input values
    the green one resets the d motor value to zero
    the brown one is the steering value variable
    and the other one basically says wait until the motors moved X( the input value) degrees and then do what ever is left
  ### 2nd part of CCW
    ![ccw](images/ccwpart2.png)
  - the area circled in purple :
    this is a loop that runs 11 times , our piece of code is only for 1/4th of a round so we put it in a loop that runs 11 times for 3 rounds ( why 11 and not 12? at the first part it goes 1/4th of a round so that counts as 1)
  - the area circled in orange :
    this is the part where we follow the walls and turn when we detect a line
    for tracking the walls we use a PD controller like this
    ![wf](images/WF4.png)
    its the same as the compasss PD which i exlpained but with the diffrence of that when we enter a CCW block the boolean variable named CW turns false and the Kp and Kd constants signs are the opisite of the CW block
    so here the CW variable is false so it enters the false switch
  - the rest of the area circled in purple :
    so the action of the loop circled in orange goes on until the color sensor sees the color blue and then it escapes the loops and goes onto the next task
    which uses a move block to steer the wheels and move


## Obstacle Challenge Code

The obstacle challenge code is divided into seven main sections. Separating the program into independent modules makes the code easier to understand, debug, and improve. Each section is responsible for a specific task during the robot's autonomous run.

### 1. Setup

*Write your explanation here.*

---

### 2. Servo

*Write your explanation here.*

---

### 3. Getting Out of the Parking Zone

*Write your explanation here.*

---

### 4. Deciding the Compass Numbers

*Write your explanation here.*

---

### 5. CCW and CW Blocks

*Write your explanation here.*

---

### 6. Obstacle Management Strategy

This section explains the overall strategy used to detect, classify, and avoid obstacles while completing the challenge.

*Write your explanation here.*

---

### 7. Getting Into the Parking Zone

*Write your explanation here.*


