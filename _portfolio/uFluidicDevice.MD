---
title: "uFluidic Device"
excerpt: "Designed through Fusion 360 CAD software, the microfluidic device provies a much more effeicient way to "
header:
  image: /assets/img/uFluidicDeviceTitlePicture.jpg
  teaser: /assets/img/uFluidicDeviceTitlePicture.jpg
   
---

## Introduction to microfluidic devices?

* Of the current methods that allow for people to analyze various properties of fluids, microfluidic devices provide one of the most effective ways to gather information about a given fluid in small volumes at a time. Fluids in a micro-scale behave differently than they do at a macro-scale where surface tension becomes a dominant force and, more importantly, turbulent flow does not occur naturally making mixing more difficult. Due to such difficulty in homogeneous mixing, processes like a normal blood test may require specially designed microfluidic devices to facilitate the testing process so that the patient’s health may be more easily determined.

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
| M3 x 8 mm Thread forming screws | 4 |
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
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6ea01e91e10068fdc5?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

* **How to operate the pump**
  1. Load the syringe with the necessary liquid into the barrel. Mount the syringe into the pump through the support beams on the carriage and end support.
  2. Press the red button with a metal outline to turn on the pump. A green light indicates that the syringe pump is extruding the given liquid at a steady rate.
  3. The pump will continue to push out liquid from the syringe until empty. When empty, the limit switch will pause the pump and the LED will turn red.
  4. To pause the pump, press the same red button while the pump is active, and the LED will turn yellow to signal that the pump has been paused.
  5. To change the volumetric flow rate of the pump, you must visit the code and alter the flow rate manually.
