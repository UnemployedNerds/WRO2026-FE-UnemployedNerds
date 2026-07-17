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
| Type | Smart Vision Sensor |
| Microcontroller | NXP LPC4330 (Dual-Core ARM Cortex-M4/M0) |
| Resolution | 1296 × 976 (processed internally at 640 × 480) |
| Frame Rate | Up to 60 FPS |
| Field of View | 80° Horizontal, 40° Vertical |
| Operating Voltage | 5 V |
| Current Consumption | 130–170 mA |
| Communication | Custom I2C (Port 4) |
| Color Signatures | Up to 7 programmable signatures |
| Features | Color Recognition, Object Tracking, Line Tracking, Barcode Detection |

### Overview

The Pixy2 Vision Sensor performs real-time image processing internally, allowing our robot to detect colored obstacles without placing additional computational load on the EV3 Brick. This enables fast and reliable obstacle detection while maintaining high driving speeds.

### Implementation

For the Obstacle Challenge, the Pixy2 detects:

- **Red Pillars** – Signature 1
- **Green Pillars** – Signature 2

The camera operates at up to **60 frames per second**, providing rapid detection and tracking of obstacles. Before making steering decisions, detected objects are filtered using their X and Y coordinates to eliminate false detections and improve reliability.

### Advantages

- High-speed image processing
- Up to 60 FPS
- Supports seven programmable color signatures
- Onboard image processing reduces EV3 CPU usage
- Supports line tracking and barcode recognition
- Easy integration using I2C

### Limitations

- Sensitive to lighting conditions
- Requires calibration using PixyMon
- Similar colors may occasionally produce false detections

### Lessons Learned

During development, we found that proper calibration using **PixyMon v2** significantly improved detection accuracy. Consistent lighting conditions also played an important role in achieving reliable obstacle recognition.

### Performance

During testing, the Pixy2 achieved approximately **97% detection accuracy**, resulting in smoother steering corrections, fewer collisions, and more consistent autonomous runs.

### Why We Chose Pixy2

We evaluated several vision solutions before selecting the Pixy2. It provided the best balance between speed, simplicity, and reliability for the EV3 platform.

Key advantages include:

- Built-in image processing
- Minimal CPU usage
- Low communication latency
- High frame rate (60 FPS)
- Reliable color tracking
- Compact and lightweight design
- Excellent compatibility with the EV3 platform

---

## LEGO EV3 Ultrasonic Sensor
![ultrasonic](images/ultrasonic.jpg)
### Overview

The LEGO EV3 Ultrasonic Sensor measures the distance to nearby objects without physical contact by emitting ultrasonic sound waves and measuring the time required for the echo to return.

This sensor is one of the primary components used for wall following and navigation during both competition challenges.

### Operating Principle

The sensor operates using the following process:

1. An ultrasonic pulse is emitted.
2. The sound wave travels through the air.
3. The wave reflects off nearby objects.
4. The reflected signal returns to the sensor.
5. The EV3 calculates the distance using the measured travel time.

### Features

- Measurement range: **3–250 cm**
- Contact-free distance measurement
- Fast real-time updates
- Wide detection angle
- Fully compatible with LEGO EV3

### Typical Applications

- Wall following
- Obstacle detection
- Distance measurement
- Autonomous navigation

### Advantages

- Reliable distance measurements
- Easy to integrate and program
- Operates in both bright and dark environments
- Independent of ambient lighting

### Why We Use It

The ultrasonic sensor continuously measures the robot's distance from the surrounding walls, allowing precise wall-following and stable navigation throughout the course.

---

## Why We Combine the Compass and Ultrasonic Sensors

Neither sensor is sufficient on its own for reliable navigation.

### Using Only the Ultrasonic Sensor

Although the ultrasonic sensor accurately measures the distance to nearby walls, it provides no information about the robot's orientation. Additionally, ultrasonic readings may occasionally fluctuate due to reflections, angled surfaces, or environmental noise.

### Using Only the Compass Sensor

The compass accurately measures the robot's heading but cannot determine its position relative to the walls. As a result, the robot could maintain the correct heading while gradually drifting away from the desired path.

### Our Solution

We combine both sensors to take advantage of their complementary strengths.

- The **compass** maintains the robot's heading.
- The **ultrasonic sensor** maintains a constant distance from the wall.

This sensor fusion approach provides significantly more stable navigation than either sensor could achieve independently. Throughout testing, it greatly improved wall-following accuracy and reduced cumulative positioning errors.

---

# Robot

# Robot Mechanical Design

## Rear Wheel Drive Mechanism

Our robot uses a rear-wheel differential drive system powered by a single EV3 Medium Motor.

![diffrencial](images/diffrencialrobo.png)

The differential is connected through a **24:8 gear ratio**, increasing the rotational speed by a factor of three before transferring power to the rear wheels.

This configuration allows the robot to achieve higher speeds while maintaining sufficient torque for acceleration.

### Why We Chose the Medium Motor

A common question is why we selected the EV3 Medium Motor instead of the Large Motor.

#### Comparison

| EV3 Medium Motor | EV3 Large Motor |
|------------------|-----------------|
| Higher speed | Higher torque |
| Smaller size | Larger size |
| Better for lightweight robots | Better for heavy-duty applications |

### Speed

Speed is a critical factor in both the Open Challenge and the Obstacle Challenge.

Although the Large Motor produces greater torque, it rotates more slowly. The Medium Motor's higher rotational speed, combined with our gear ratio, enables the robot to complete the Open Challenge in approximately **36–40 seconds** during testing.

### Compact Design

The Medium Motor is significantly smaller than the Large Motor, allowing us to keep the robot within the WRO size constraints while simplifying the drivetrain layout.

---

## Steering Mechanism

Our steering system uses a simple but reliable gear reduction mechanism.

The steering motor drives a **16-tooth gear**, which meshes with a **64-tooth gear** attached to the steering linkage.

This reduction provides:

- Increased steering precision
- Greater steering torque
- Smooth and repeatable steering movements

The simplicity of this mechanism also improves reliability and makes maintenance easier during competitions.

---

## Mobility Management

Our robot's mobility system was designed to maximize speed while maintaining precise and stable navigation. Throughout development, we focused on three key engineering objectives:

- Optimizing drivetrain efficiency
- Improving steering precision
- Increasing overall chassis stability

### 1. Drivetrain Optimization

Early testing showed that extremely aggressive gear ratios produced high theoretical speeds but poor acceleration. The motors frequently stalled during starts and after sharp turns.

After testing multiple gear ratios, we selected the configuration that provided the best compromise between acceleration, torque, and maximum speed.

This optimization resulted in:

- Faster acceleration
- More consistent lap times
- Reduced motor stress
- Improved controller stability

### 2. Steering Precision

Our first steering design used a rack-and-pinion mechanism.

Although compact, testing revealed excessive backlash, causing steering inaccuracies and oscillations during high-speed driving.

To solve this issue, we redesigned the steering linkage with a custom mechanism that significantly reduced mechanical play.

As a result, we achieved:

- More accurate steering angles
- Better return-to-center performance
- Reduced overshoot
- Smoother obstacle avoidance

### 3. Chassis Stability

Maintaining a low center of gravity was one of our primary design goals.

The EV3 Brick and battery pack were mounted as low as possible to reduce body roll during cornering.

Heavy components were also positioned close to the center of the chassis, reducing rotational inertia and allowing the robot to change direction more quickly.

Finally, the chassis was reinforced using cross-bracing to minimize structural flex and maintain consistent wheel alignment throughout each run.
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


