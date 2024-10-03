---
title: "Dual Locomotion Swimming Robot using Undulating Motion"
excerpt: "A new research project aimed at developing a swimming robot capable of diving underwater, docking on the inner walls of a pipe, and sensing liquids flowing through."
header:
  image: /assets/img/AF2_png.png
  teaser: /assets/img/AF2_png.png
   
---
## Introduction and Project Goals
&nbsp;&nbsp;&nbsp;&nbsp;The project goals are as follows. We plan to create a robot that is (1) capable of swimming underwater using biomimetic locomotion (undulating motion) and then (2) dock onto the inner surfaces of a pipe to (3) provide information about the fluids flowing through the pipe.

&nbsp;&nbsp;&nbsp;&nbsp;As of Fall 2024, I was tasked with starting the project while my partner, a junior undergraduate student, was finishing up his research paper, but I will speak on behalf of the project's current progress as a whole. As for my part of the project, I have been tasked with the mechanical module whereas my partner has been tasked with the electrical module.

# CAD Model
<iframe src="https://vanderbilt1072.autodesk360.com/shares/public/SH30dd5QT870c25f12fc53809d601e140a44?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

## _Mechanical Systems_
#### Locomotion Module:
&nbsp;&nbsp;&nbsp;&nbsp;The undulating motion is achieved using 6 sets of four-bar linkage combined with a crankshaft (two in total). The motion as a whole, y-displacement for each member, and tolerancing were all tested and modified using CAD software (Fusion 360), and it is an understatement to mention how important this assembly has been all throughout the project so far. All parts of the mechanical components have been printed using PLA material.

**insert image of fully assembled robot**

**diagram for each component along with label**

#### Swimming membrane:
&nbsp;&nbsp;&nbsp;&nbsp;The swimming membrane (or fins) were created using Ecoflex30 (A and B), and the mold used to create such swimming membrane was initially a rectangular mold; modifications, however, have been recently made for a prototypical fin that better suits the inner and outer maximum stretch and shrink in the y-direction of the membrane along with tolerancing. The fin has been mounted onto the leg through suturing (nylon) and secured onto each member. 

**image of fin, video of undulating locomotion**

* Prototype for Swimming Membrane Version 2

&nbsp;&nbsp;&nbsp;&nbsp;Briefly mentioning the prototypical fin systems, two tiny slits were made within each leg so that the membrane may "weave" into each leg thus reducing the work needed to suture each leg and membrane together except for the ends. The lack of a rigid joint allows for a more flexible fin and thus reduces work input since tension within the fin is reduced. SLS printing was used for its ability to print small dimensions (~60 microns) due to the use of selective sintering methods onto small plastic powder particles (PA12). 

**image of prototype fin working onto robot**

#### Magnetic Coupler:
&nbsp;&nbsp;&nbsp;&nbsp;To ensure complete physical isolation between the electrical and mechanical modules, sets of magnetic couplers were used to transmit rotational energies from a motor to the four-bar linkage. The magnetic couplers utilize 6, 3 mm diameter x 10 mm height magnets in alternating polarities. The alternating polarities ensure that even if the magnetic couplers decouple, they can easily couple back.

**video/image of couplers**

#### Buoyancy Control Unit (BCU):
&nbsp;&nbsp;&nbsp;&nbsp;To control the pitch of the robot, a BCU has been designed to change the center of gravity for the robot and tilt it forward, allowing the robot to swim deeper underwater. A 20N linear actuator with 50 mm reach motion paired with a syringe with 12.8 mm ID makes the foundation for the BCU. The idea for a BCU has been added to the assembly and is currently being worked on.

#### Magnetic Docking:
&nbsp;&nbsp;&nbsp;&nbsp;As one of the key components of the project, the idea for magnet docking has been made, but have yet to be developed upon as of now.









