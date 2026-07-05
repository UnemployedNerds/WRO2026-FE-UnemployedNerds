

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


## Platform and Components
#### Why we chose EV3
- we chose EV3 for its simplicity and versitality , easy sensor integration and fast development and built in safty features
### PROS AND CONS
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

#### Components and sensors :
### Motors 
-Lego EV3 Medium motor :
![medmotorpic]()
## EV3 Medium Motor

### Specifications
- **Type:** DC Motor (Medium)
- **Voltage:** 9 V
- **Speed:** 160 RPM
- **Torque:** 20 N·cm (effective torque ≈15 N·cm under the robot's 1.2 kg load)
- **Weight:** 120 g
- **Feature:** Provides propulsion (rear wheels) and steering (front wheels)

### Interface
| **Motor** | **Port** | **Function** |
|-----------|----------|--------------|
| Steering Motor | `OUTPUT_B` | Controls front-wheel steering via rack-and-pinion |
| Primary Drive Motor | `OUTPUT_D` | Drives the rear wheels through the differential |
| Secondary Drive Motor *(Open Challenge only)* | `OUTPUT_C` | Mechanically coupled to the differential for additional torque and speed |

### Configuration for Challenges

#### Obstacle Challenge (Final Submitted Version)
- One Medium Motor on `OUTPUT_D` drives the differential.
- The gear of the second drive motor is physically removed.
- Optimized for reliable torque and precise parking.

#### Open Challenge
- A second Medium Motor is connected to `OUTPUT_C`.
- Both motors are mechanically coupled to the same differential gear.
- Motors are synchronized in software.
- This configuration complies with WRO regulations because both motors drive a **single mechanical output** (the differential).

---

## Gear Train

Both 20-tooth motor gears drive a shared 12-tooth gear.

The 12-tooth gear shares an axle with a 20-tooth gear, which drives the 24-tooth differential gear.

**Final Gear Ratio**

```text
(20 : 12) × (20 : 24)
= 25 : 18
≈ 1.39 : 1
```

Result:
- ≈39% speed reduction
- ≈39% torque increase compared to direct drive

---

## Description

The ShahroodRC robot uses one or two EV3 Medium Motors for propulsion.

- `motor_b` (`OUTPUT_D`) is always used for propulsion.
- `motor_c` (`OUTPUT_C`) is installed only during the Open Challenge.

The compound gear reduction increases available torque while maintaining a high driving speed.

Steering is performed by a single Medium Motor (`motor_a` on `OUTPUT_B`) connected to a rack-and-pinion mechanism.

Medium Motors were chosen over Large Motors because of their significantly lower weight (120 g vs 170 g) while still providing sufficient torque for our 1.1–1.2 kg robot.

---

## Lessons Learned

Early tests using near-direct drive occasionally resulted in motor strain and stalling during tight parking maneuvers.

The final **20–12–20–24** compound gear train, combined with the dual-motor configuration in the Open Challenge:

- Increased available torque
- Reduced peak current from approximately **600 mA** to **400 mA** during parking
- Eliminated motor stalling

Adding the second drive motor for the Open Challenge further reduced strain at higher speeds.

---

## Implementation Impact

- Precise encoder-based functions (`on_for_degrees()` and `on_for_rotations()`) enabled parking in under **10 seconds** with almost zero wheel slippage.
- The modular single/dual motor design allowed independent optimization for:
  - **Obstacle Challenge:** Maximum torque
  - **Open Challenge:** Higher speed
- No hardware redesign was required between challenges.



why we use compass sensor

why we use piximoon camera insted of other camera

why we use ultra sonic

why we use color sensor

importance of using compass and ultra sonic 
the reason we dont use only ulyrasonic for navigation
we could have use two ultra sonic but we use hitech color sesnsor for 
\diffrance between large motor and meduim motor

