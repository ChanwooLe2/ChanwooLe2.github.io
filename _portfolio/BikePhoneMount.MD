---
title: "Bike Handle Phone Mount"
excerpt: "While safely securing your phone onto the bicycle, this phone mount allows cyclists to easily mount and dismount the phone for both vertical and horizontal orientations."
header:
  image: /assets/img/HolderFrontPic.jpg
  teaser: /assets/img/HolderFrontPic.jpg
   
---
## Introduction and Top-down Modelingp

&nbsp;&nbsp;&nbsp;&nbsp;Contrary to regular methods to model components, Fusion 360 offers a facilitated method to design models (or components) ontop one already existing component. So called Top-down modeling, users are able to create new components in relation to eachother without having the need to open a new document to create and adjust dimensions according to related components. For our project specifically, a phone model of choice and the bicycle handle were first imported onto a file then top-down modeling was utilized to model a phone mount, handle to phone link, and handle mount all within one document, all in relation to one another.  

![alt text](https://ChanwooLe2.github.io/assets/img/Components.jpg "Comp")

## Phone mount components

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e39efe4a51325739d?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

#### Phone Mount

&nbsp;&nbsp;&nbsp;&nbsp;Using the imported phone model (that has been grounded), a separate component was created to utilize the top-down modeling method. First, a rigid base was extruded with plenty of tolerance (~0.2 mm), and then extrude remove was utilized to enable flexibility while decreasing material needed to print such a model. 

![alt text](https://ChanwooLe2.github.io/assets/img/PhoneMount.jpg "Mount")

&nbsp;&nbsp;&nbsp;&nbsp;To account for potential failures, where the phone doesn't fit nicely, the top part of the phone mount was designed to allow for flexibility compared to the bottom. The reasoning behind the bridging component near the bottom was to prevent the phone from falling off the mount too easily when placed onto the bicycle in a vertical orientation. As labled, however, the bottom does include a break-off from the bridging structures to allow for a limited flexibility.

![alt text](https://ChanwooLe2.github.io/assets/img/Bridges.jpg "Bridges")

#### Handle to Phone Link

&nbsp;&nbsp;&nbsp;&nbsp;Starting a model ontop of the phone mount, the handle to phone link was easily created via top-down approach for easy attachment using M3 fasteners and a dovetail joint to mount and dismount the phone from the handle mount without difficulty. Simplicity was the main objective for this component.

![alt text](https://ChanwooLe2.github.io/assets/img/Link.jpg "Link")

#### Handle Mount

![alt text](https://ChanwooLe2.github.io/assets/img/HandleMount.jpg "Handle")

&nbsp;&nbsp;&nbsp;&nbsp;The last component of the bicycle phone mount is the handle mount. It was designed to allow for a comparatively easy way to secure onto a 25 mm diameter handle using a M5 allen wrench, and in terms of connecting onto the link, a plus sign-shaped extrude removes were utilized to allow for the phone to be in a horizontal and vertical orientation.

![alt text](https://ChanwooLe2.github.io/assets/img/PlusSign.jpg "Plus")
<p style="text-align: center;">Note that the bottom was blocked off to prevent the phone from slipping through the handle mount with ease.</p>

## Other information

#### Assembly Instructions

1) First secure the handle mount onto the handle of diameter 25 mm using a M5 allen wrench.

2) Attach the handle to phone link using four M3 fasteners onto the phone mount. No allen wrench is necessary for such procedure.

![alt text](https://ChanwooLe2.github.io/assets/img/Step1.jpg "Step2")

3) Slide the dovetails into each other in an orientation of choice (vertical or horizontal).

![alt text](https://ChanwooLe2.github.io/assets/img/Step2.jpg "Step3")

#### Material Selection and Gallery

* TPU was utilized for the phone mount to allow for a flexible, easy and quick way to attach the phone onto the mount.
* PLA was utilized for the other two components for its structural integrity.

![alt text](https://ChanwooLe2.github.io/assets/img/Working.jpg "Working")

![alt text](https://ChanwooLe2.github.io/assets/img/Iteration.jpg "Iteration")
<p style="text-align: center;">Iterations of Link component due to realization that parts will collide with M3 bolts</p>


