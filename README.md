# unmapped_robo-Design2026
# Autonomous Tracked Mobile Robot Platform

## Overview

This project is a custom-designed autonomous tracked mobile robot developed from the ground up with a strong focus on precision, modularity, protection of critical components, and future scalability.

The goal was not simply to assemble available components, but to design a robot that could reliably operate in challenging environments while keeping sensitive electronics safe and making maintenance easy.

After several design iterations, the final concept combines:

- Precision mechanical design
- Modular electronic compartments
- Autonomous navigation sensors
- High-traction tracked drive system
- Future autonomous loading and unloading mechanism

---

# Why I Designed It This Way

Most mobile robots expose many of their electronic components. While this makes assembly easier, it leaves expensive sensors and motors vulnerable to:

- Dust
- Water splashes
- Mechanical impacts
- Cable damage
- Dirt entering moving parts

I wanted a cleaner and more professional design where every major component has its own dedicated compartment.

Instead of making everything visible, I chose to integrate most components inside the robot body for protection and aesthetics.

The result is a compact, balanced, and unique robot that looks engineered rather than assembled.

---

# Design Philosophy

The robot was designed around four major principles:

- Protection
- Modularity
- Stability
- Expandability

Every component has its own space, making future upgrades much easier.

---

# Major Components

## 1. LiDAR Compartment

The LiDAR is mounted at the top of the robot.

### Purpose

- 360° environmental scanning
- Obstacle detection
- Mapping surroundings
- Localization
- Autonomous navigation

Placing it on top gives it an unobstructed field of view.

---

## 2. Camera Sensor

The camera provides visual information that complements the LiDAR.

### Functions

- Object detection
- Line following
- QR code recognition
- Color detection
- Human detection
- Visual navigation

Using both LiDAR and a camera makes navigation more reliable because each sensor compensates for the limitations of the other.

---

## 3. Battery Compartment

A dedicated compartment was created for the battery/power bank.

### Why?

- Protects the battery
- Easy replacement
- Better weight distribution
- Cleaner wiring
- Safer operation

Keeping the battery near the center improves balance.

---

## 4. Raspberry Pi Compartment

The Raspberry Pi is the robot's main computer.

### Functions

- Processes camera images
- Runs navigation algorithms
- Controls autonomous behavior
- Communicates with sensors
- Sends commands to motor drivers

The compartment is removable, making maintenance much easier.

---

## 5. Circuit Board Compartment

This houses:

- Motor drivers
- Power distribution
- Voltage regulators
- Control electronics

Keeping electronics together reduces wiring complexity while protecting them from external damage.

---

## 6. Motors with Encoders

Each tracked drive motor includes an encoder.

### Why I Didn't Want the Encoders Exposed

Many robots leave the encoder sticking out from the motor.

I intentionally designed my robot so the encoder remains protected inside the assembly.

Reasons include:

- Prevent accidental impacts
- Reduce dust contamination
- Protect encoder wiring
- Improve durability
- Give the robot a cleaner appearance
- Reduce chances of mechanical damage during operation

Although it required much more precise design work, the final result is stronger and more reliable.

---

# What are Encoders?

Encoders measure how much the motor rotates.

They allow the robot to know:

- Distance travelled
- Speed
- Direction
- Wheel position

Without encoders, the robot cannot accurately determine its movement.

Encoders are essential for:

- Precise navigation
- Odometry
- Path planning
- Speed control
- Accurate turning
- Autonomous driving

---

# Tracked Wheel System

Instead of ordinary wheels, this robot uses tracked wheels.

### Advantages

- Better traction
- Higher stability
- Improved performance on rough terrain
- Easier climbing over obstacles
- Reduced slipping
- Better load carrying capacity

Compared to a two-wheel robot, tracked systems are:

- More stable
- Faster on difficult terrain
- Better suited for carrying heavy loads
- Less likely to get stuck

---

# Why I Normally Prefer a Triangular Track System

Although this prototype uses tracked wheels, my preferred design is a triangular tracked system with multiple wheels supporting the track.

Advantages include:

- Better stair climbing
- Easier obstacle crossing
- Improved weight distribution
- Smoother movement
- Increased stability
- Reduced stress on individual wheels

This design is ideal for industrial and warehouse robots operating on uneven surfaces.
<img width="1920" height="1080" alt="Screenshot (21)" src="https://github.com/user-attachments/assets/15cc21f7-2a06-4257-9431-830302ddf1a0" />
<img width="1920" height="1080" alt="Screenshot (22)" src="https://github.com/user-attachments/assets/789d384e-0ea5-456d-8130-8336d1d2ff8c" />
<img width="1920" height="1080" alt="Screenshot (23)" src="https://github.com/user-attachments/assets/42b5e2b2-aed3-44ed-ad91-c51dab5bbfa0" />


---

# Future Loading and Offloading System

The rear of the robot is reserved for an autonomous loading and unloading mechanism.

### Planned Operation

The robot will:

1. Navigate to a destination.
2. Stop at the unloading point.
3. Raise the rear platform.
4. Tilt the platform.
5. Slide the payload onto the floor.
6. Return to its original position.

This allows goods to be delivered with minimal human intervention.

The mechanism can be modified depending on the application.

Possible payloads include:

- Boxes
- Medical supplies
- Warehouse packages
- Food deliveries
- Industrial materials

---

# Situations the Robot Can Handle

The robot can be adapted for:

- Warehouse automation
- Factory material transport
- Indoor logistics
- Hospital deliveries
- Smart manufacturing
- Research projects
- University robotics competitions
- Autonomous inspection
- Hazardous environments
- Educational demonstrations

---

# Why the Compartments Are Movable

The battery, Raspberry Pi, and electronics compartments were intentionally designed to be removable.

Benefits include:

- Faster maintenance
- Easy upgrades
- Quick battery replacement
- Easier troubleshooting
- Modular customization
- Better cable management

This makes the robot adaptable to future hardware improvements without redesigning the entire chassis.

---

# Challenges Faced During Development

This project required significant patience and precision.

One of the biggest challenges was using Onshape.

Although the design itself progressed well, poor internet connectivity frequently interrupted the workflow because Onshape is cloud-based.

Large assemblies became difficult to manage, slowing productivity.

To overcome this limitation, I exported the completed parts and imported them into SOLIDWORKS.

Once in SOLIDWORKS, assembly became much smoother, allowing the project to progress efficiently.

This experience demonstrated the importance of selecting the right engineering tools while adapting to real-world constraints.

---

# What Makes This Design Unique?

Unlike many educational robot platforms, this design emphasizes:

- Protected encoders
- Dedicated sensor compartments
- Modular electronics
- Integrated battery housing
- Balanced weight distribution
- Compact mechanical layout
- Expandable architecture
- Professional appearance
- Future autonomous loading system

Every design decision was made with long-term reliability, maintenance, and scalability in mind.

---

# Conclusion

This project represents more than a mobile robot—it is a platform designed for future autonomous logistics and intelligent navigation.

By combining LiDAR, computer vision, motor encoders, tracked mobility, and modular electronics, the robot provides a solid foundation for future research and development.

Despite the challenges encountered during the design process, particularly software limitations and internet connectivity issues, the project was successfully completed through persistence, careful engineering, and the effective use of SOLIDWORKS for final assembly.

This robot demonstrates how thoughtful mechanical design and modular architecture can produce a reliable, expandable, and professional autonomous robotic platform suitable for both academic research and real-world applications.
