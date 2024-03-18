---
title: "uFluidic Device"
excerpt: "Designed through Fusion 360 CAD software, the microfluidic device provies a much more effeicient way to "
header:
  image: /assets/img/uFluidicDeviceTitlePicture.jpg
  teaser: /assets/img/uFluidicDeviceTitlePicture.jpg
   
---

## Introduction to microfluidic devices?

⋅⋅⋅Of the current methods that allow for people to analyze various properties of fluids, microfluidic devices provide one of the most effective ways to ⋅⋅⋅gather information about a given fluid in small volumes at a time. Fluids in a micro-scale behave differently than they do at a macro-scale where ⋅⋅⋅surface tension becomes a dominant force and, more importantly, turbulent flow does not occur naturally making mixing more difficult. Due to such ⋅⋅⋅difficulty in homogeneous mixing, processes like a normal blood test may require specially designed microfluidic devices to facilitate the testing ⋅⋅⋅process so that the patient’s health may be more easily determined.

## Design Specifications

* **Device Overview**

![alt text](https://ChanwooLe2.github.io/assets/img/uFluidicDeviceDesignOverlook.jpg "Overview")

Some of the decisions regarding the dimensions of the geometries we used to create chaotic advection relied on the size constraints of the device. Specifically, the resolution of the printer was limited to 25 micrometers, there had to be two primary mixing sections in the device (by each team member), the aspect ratio had to be less than 4:1, and all geometries had to be at least 4 mm from the edge of the device. Nevertheless, our device utilizes multiple unique geometries to maximize surface area and chaotic advection of the fluid. 


* **[Syringe pump code](https://github.com/ChanwooLeee/SyringePumpCode)**

# CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6ea01e91e10068fdc5?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

* **How to operate the pump**
  1. Load the syringe with the necessary liquid into the barrel. Mount the syringe into the pump through the support beams on the carriage and end support.
  2. Press the red button with a metal outline to turn on the pump. A green light indicates that the syringe pump is extruding the given liquid at a steady rate.
  3. The pump will continue to push out liquid from the syringe until empty. When empty, the limit switch will pause the pump and the LED will turn red.
  4. To pause the pump, press the same red button while the pump is active, and the LED will turn yellow to signal that the pump has been paused.
  5. To change the volumetric flow rate of the pump, you must visit the code and alter the flow rate manually.
