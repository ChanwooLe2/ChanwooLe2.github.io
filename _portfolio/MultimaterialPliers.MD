---
title: "Multimaterial Pliers"
excerpt: "Multimaterial pliers, showcasing the perfect cooperation between rigid PLA and elastic TPU, is able to pick up things as small as a resistor."
header:
  image: /assets/img/MultiMaterialPliersRendering.jpg
  teaser: /assets/img/MultiMaterialPliersRendering.jpg
   
---
## Printing with multiple materials?

&nbsp;&nbsp;&nbsp;&nbsp;Of the several techniques involving multimaterial FFF, the print-in-place is a technique in which within one print, multiple materials may cooperate to achieve a desired feature. This way of printing multiple materials allows for the user to utilize this desired feature right after printing without an assembly since all parts are printed within one print session (note that materials are assigend accordingly). 

## Material selection with multimaterials

#### TPU and PLA

&nbsp;&nbsp;&nbsp;&nbsp;Given that a printer is able to print multiple materials, it is also important to know its applications. One of the common ways to utilize this technology is through use of TPU and PLA.

<img style="float: left;" src="https://ChanwooLe2.github.io/assets/img/MultiMaterialEx.png" alt="MultiMaterial Example1" width="422"/> 
<img style="float: right;" src="https://ChanwooLe2.github.io/assets/img/MultiMaterialEx2.png" alt="MultiMaterial Example2" width="458"/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<small> [**Image Reference**](https://community.ultimaker.com/topic/42890-ultimaker-cura-53-beta-released/) </small>

&nbsp;&nbsp;&nbsp;&nbsp;Displayed in the image, TPU, with its elastic property, acts as a spring component in the aligator clip, and the rigid PLA structure is able to clip certain objects. As could be imagined, the possibility of printing both elastic and rigid components all within one print opens the door for all sorts of mechanical systems where an assembly to reach the same system may be an impossible task. 
&nbsp;&nbsp;&nbsp;&nbsp;Skipping ahead, my pliers were made with two parts PLA and one part TPU all printed separately, but it should be noted that this approach was an easier, or "cheat", way of going about making a set of multimaterial pliers. To truely exercise the ability of multimaterial printing, a design similar to that shown below is common.

![alt text](https://ChanwooLe2.github.io/assets/img/pliars.jpg "Multimat Pliars")
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<small> [**Image Reference**](https://all3dp.com/3d-printed-flexible-pliers/) </small>

#### Soluble/Dissolvable Supports

&nbsp;&nbsp;&nbsp;&nbsp;When there is an overhang is greater than 45°, breakaway supports are usually used to prevent prints from failing, and these breakaway supports tend to get annoying in situations where it may be physically difficult to remove them. Printing multimaterial, however, enables users to print soluble/dissolvable supports. A common combination of material is PLA and PVA or ABS and HIPs.

[![Watch the video](https://img.youtube.com/vi/_PhN_3ijv8I/maxresdefault.jpg)](https://youtu.be/_PhN_3ijv8I)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<small> [**Video Reference**](https://www.youtube.com/@3dprintlife253) </small>

&nbsp;&nbsp;&nbsp;&nbsp;The video showcases PVA soluble supports in action, and as can be seen, complex geometries, especially internal features, that inhibit the removal of supports may benefit greatly from use of water soluble or dissolvable supports. 

## Multimaterial Pliers

<iframe src="https://giphy.com/embed/7tUbr1NVhyq3XBHtzr" width="480" height="480" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/7tUbr1NVhyq3XBHtzr"></a></p>

#### Design Features

&nbsp;&nbsp;&nbsp;&nbsp;My pliers minimize number of necessary printed parts with a pair of male and female components each attached with a compartment on the inner sides to hold the spring component. 

![alt text](https://ChanwooLe2.github.io/assets/img/MultiMaterialTwistLock.png "Lock Mechanism1")
![alt text](https://ChanwooLe2.github.io/assets/img/20240402_202115.jpg "Lock Mechanism2")

&nbsp;&nbsp;&nbsp;&nbsp;The pliers utilize an internal twist-lock joint that holds the female and male components together, and through section analysis and topdown modeling on Fusion 360, the spring component was created. Overall, the pliers were modeled parametrically, and different variables, such as the joint radius, angle between radius to handle or jaw, etc., were experimentally determined to maximize gripping capabilities. 
<img style="float: right;" src="https://ChanwooLe2.github.io/assets/img/20240402_210026.jpg" alt="Jaw" width="300"/>
A critical flaw within my model may be the gripping method. Albeit my plier was able to grip resistors without much struggle, the gripping round gripping end with a noticeable difference in gripper height contributed to the struggle in gripping small round surfaces and/or thin materials on a flat surface.

![alt text](https://ChanwooLe2.github.io/assets/img/20240402_210156.jpg "Jaw2")

&nbsp;&nbsp;&nbsp;&nbsp;Lastly, the spring component was modeled at the plier's maximum extension, keeping in mind that the twist-lock joint was not susceptible to falling off at that point. Squishing the pliers to grab a material would cause the spring to exert forces into the pliers, meaning that when after releasing the squeezing force, the pliers would revert back to their position of maximum extension.

###### CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e52489135c91e2e3a?mode=embed" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

#### Plier Capability

| Feature | Dimension |
| --- | --- |
| Jaw Length | ~48 mm |
| Handle Length | ~107 mm |
| Joint diameter | 30 mm |
| Plier Thickness | 12.5 mm |
| Spring Thickness | Max: ~6.5 mm, Min: 4.2 mm |

#### Print Settings
 * Female part infill: 20
 * Male part infill: 50
   * The male component has a higher infill to increase the strength of the joint insert

#### More Media

![alt text](https://ChanwooLe2.github.io/assets/img/20240402_163049.jpg "Male and female")
<p style="text-align: center;">Failed male plier components due to lack of strength and tolerance</p>

<div style="width:100%;height:0;padding-bottom:100%;position:relative;"><iframe src="https://giphy.com/embed/tB21vDEj1QC6LjuEWU" width="100%" height="100%" style="position:absolute" frameBorder="0" class="giphy-embed" allowFullScreen></iframe></div><p><a href="https://giphy.com/gifs/tB21vDEj1QC6LjuEWU"></a></p>
<p style="text-align: center;">Pliers picking up pencil case</p>

