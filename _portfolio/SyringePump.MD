---
title: "Syringe Pump Project"
excerpt: "Created almost all by hand, the syringe pump exerts stored liquid from 1 uL/min to 10 mL/min."
header:
  image: /assets/img/Rendering-Of-Actuator (1).jpg
  teaser: /assets/img/Rendering-Of-Actuator (1).jpg
   
---

## Features

* **Various extrusion rates.** As far as the code goes, any operator may change the rate at which the liquid exits the syringe.
* **Exchangeable syringe sizes** This pump has two components that can hold bold a 10 mL syringe and a 20 mL syringe. The ability to change syringe sizes has critical implications for different purposes: for example, if more liquid is needed, the operator may utilize a 20 mL syringe to better suit their needs.

## Parts required

* **Off-the-shelf parts**

| Part name | Quantity |
| --- | --- |
| 2040 aluminum extruson | 1 |
| NEMA 17 stepper motor | 1 |
| Arduino Uno | 1 |
| Small breadboard | 1 |
| MEAN WELL RQ-65D AC-DC Power Supply | 1 |
| A4988 stepper driver | 1 | 
| Limit switch | 1 |
| Panel mount latching push buttons | 1 |
| RGB common Cathode LED | 1 |
| LM8UU linear bearing for 8 mm diameter rod | 1 |
| 200 mm linear rod with 8 mm diameter | 1 |
| 1/4'' x 8 mm flexible coupler | 1 |
| 250 mm lead screw with 2 mm pitch and 2 mm lead | 1 | 
| Lock collar | 4 |
| M3 x 8 mm Tread forming screws | 4 |
| Nut-tr8x84 | 1 |
| M5 x 8 mm Bolt | 8 |
| M5 Tee nut | 8 |
| F688ZZ flanged ball bearing | 2 |
| M3 x 10 mm Bolt | 4 |

* **3D printed parts**

| Part name | Quantity |
| --- | --- |
| Motor Mount | 1 |
| End support no top | 1 |
| End support with top | 1 |
| Carriage | 1 |
| Syringe Stabilizer | 1 |

* **[Syringe pump code](https://github.com/ChanwooLeee/SyringePumpCode)**

# CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e973b13afc1f0ea1e?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

* **How to operate the pump**
  1. Load the syringe with the necessary liquid into the barrel. Mount the syringe into the pump through the support beams in the carriage and end support.
  2. Press the red button with a metal outline to turn on the pump. A green light indicates that the syringe pump is extruding the given liquid at a steady rate.
  3. The pump will continue to push out liquid from the syringe until empty. When empty, the limit switch will pause the pump and the LED will turn red.
  4. To pause the pump, press the same red button while the pump is active, and the LED will turn yellow, signaling that the pump has been paused.
  5. To change the volumetric flow rate of the pump, you must visit the code and alter the flow rate manually.
