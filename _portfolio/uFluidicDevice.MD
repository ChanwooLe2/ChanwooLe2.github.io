---
title: "uFluidic Device"
excerpt: "Designed through Fusion 360 CAD software, the microfluidic device provies a much more effeicient way to "
header:
  image: /assets/img/uFluidRendering.png
  teaser: /assets/img/uFluidicDeviceTitlePicture.jpg
   
---

## Introduction to microfluidic devices?

   Of the current methods that allow for people to analyze various properties of fluids, microfluidic devices provide one of the most effective ways to gather information about a given fluid in small volumes at a time. Fluids in a micro-scale behave differently than they do at a macro-scale where surface tension becomes a dominant force and, more importantly, turbulent flow does not occur naturally making mixing more difficult. Due to such difficulty in homogeneous mixing, processes like a normal blood test may require specially designed microfluidic devices to facilitate the testing process so that the patient’s health may be more easily determined.

## Design Specifications

* **Device Overview**

![alt text](https://ChanwooLe2.github.io/assets/img/uFluidicDeviceDesignOverlook.jpg "Overview")

   Some of the decisions regarding the dimensions of the geometries we used to create chaotic advection relied on the size constraints of the device. Specifically, the resolution of the printer was limited to 25 micrometers, there had to be two primary mixing sections in the device (by each team member), the aspect ratio had to be less than 4:1, and all geometries had to be at least 4 mm from the edge of the device. Nevertheless, our device utilizes multiple unique geometries to maximize surface area and chaotic advection of the fluid. 

* **Section 1 Overview**

![alt text](https://ChanwooLe2.github.io/assets/img/uFLuid7.png "Sect1Overview")

   Section 1 of our microfluidic device utilizes 4 primary design choices: branched paths, obstacles, paths with ridges, and sharp corners. Given the two major mixing techniques, diffusion and chaotic advection, the four provided design attributes are all effective ways to induce mixing. At first glimpse (starting from left to right), section 1 includes a serpentine path followed by a branched structure that splits into 8 paths at most. The extent to which section 1 provides paths of various widths collectively contribute to increasing the cross-sectional area which then allows for a greater rate of diffusion.

![alt text](https://ChanwooLe2.github.io/assets/img/uFluid1.jpg "SerpentinePath")

   The serpentine path, although the fluid wasn’t able to travel through the upper section, had a width of 800 micrometers, second to largest in our device, and it also included ridged channels with a height of 250 micrometers to induce chaotic flow. The large width in itself heightens the rate of diffusion, but more importantly, the ridged channels allow for the fluid to split up, mix through both diffusion and chaotic advection, and join back for the next section in the device. One design flaw within our device was that the intersecting channels were too wide, preventing the fluid to travel parallel to the main path, creating a deadzone.

![alt text](https://ChanwooLe2.github.io/assets/img/uFluid2.jpg "BranchedStructure")

   Moving onto the branched structure, apart from the amount of paths the structure provides, the key attribute is its obstacles. With around 20 obstacles in each of the 8 paths, our microfluidic device makes sure to induce chaotic flow to ensure mixing. The only drawback to having multiple paths or ineffective fluid dividing features is that not all of the paths were utilized for mixing, nevertheless, for the fluid that did travel down the obstacle path, mixing was induced effectively.

![alt text](https://ChanwooLe2.github.io/assets/img/uFluid3.jpg "InclineGeometry")

   The first geometry the second section of the mixing device contains is an inclined twisting geometry. This geometry works in three dimensions and consequently causes the fluid to simultaneously flow from side-to-side and up-to-down as it travels forward throughout the device. This multiaxial motion induces chaotic mixing of the fluid. This geometry then diverts into the major two-part mixing section of this side of the device. 

![alt text](https://ChanwooLe2.github.io/assets/img/uFluid45.jpg "IntersectingChannels")

   One piece of this primary mixing section utilizes intersecting channels. The intersecting channels geometry splits, rearranges, and recombines component streams. The design has a 1 mm thick rectangular boundary with small 0.25 mm parallel channels orthogonally dissecting it. Most of the fluid traverses the wider rectangular border path; however, small portions of it travel through the orthogonal channels, thereby enhancing chaotic advection. On the other side of this primary mixing section, the device uses an obstacle-based geometry. Specifically, wide extrusions that disrupt smooth forward flow greatly slow the mixing process and force the fluid to move through channels of varying widths.

![alt text](https://ChanwooLe2.github.io/assets/img/uFluid5.png "ZigZag")

   Finally, the ultimate mixing geometry of this side of the device is a simple zig-zag pattern, which is a common passive geometry in microfluidic devices due to its efficiency and simplicity. For this geometry the ratio between the width and step size of the pattern determines the mixing efficiency. An optimal ratio of 4:1 between these parameters maximizes mixing efficiency.

## CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e4cdffd816f228146?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

## How to go from 3D Mold to Final Device 
##### Reference[1^]

* **Print and Cure Mold**
  1. Create a mold on a CAD software and print via Form 3 SLA resin printer (for its precision)
  2. Wash the mold for 5 minutes on the print bed and 5 minutes again off the print bed, facing down, using isopropanol alcohol.
    * Make sure to NOT touch inside of the mold.
  3. Let the device dry for 30 minutes away from sunlight, and confirm that there are no shiny sections or debris.
  4. Cure the device for 5 seconds withot heat.
* **Parylene Device, PDMS, and Plasma Bond glass slide**
  1. Place the cured prints into a Labcoter PDS 2010 machine to coat the molds with 2 grams of parylene-C. This protects the inner molds from outside contaminants that may corrode parts.
  2. Place the prints in a plastic petri dish. Mix PDMS (polydimethyl siloxane) elastomer and curing agent in a 10:1 weight ratio and pour onto the print.
  3. Place the mixture in a vacuum chamber to remove any air bubbles then cure in an oven at 80 ^o^C for 3 hours.
  4. Using PlasmaFloo PDC-FMG plasma cleaner, bond the PDMS devices and glass coverslips together then sterilize before use.

## Videos of uFluidic Device Testing
[![Watch the video](https://img.youtube.com/vi/9JpSWnpcBZc/maxresdefault.jpg)](https://youtu.be/9JpSWnpcBZc) 



[1^]: https://pubs.rsc.org/en/content/articlelanding/2021/lc/d1lc00744k

