---
title: "Electric Longboard Hanger + Motor Mount"
excerpt: "As a critical component of the DIY electric longboard, the hanger and motor mount was created mostly through use of generative design, and it was created while keeping in mind the various forces that may destroy it. ."
header:
  image: /assets/img/Paris1Render.png
  teaser: /assets/img/Paris1Render.png
   
---
## Introduction and Generative Design
&nbsp;&nbsp;&nbsp;&nbsp;Generative Design is a CAD modeling method in which an AI creates bodies given the user defined obstacle and preserve geometries. Simply, obstacle geometries are places where the AI must avoid putting material into (i.e. holes for screws) while preserve geometries are those that must be included within the model. Although the whole generating process is one that takes countless hours, often over night, the generative design feature allows users to end up with different possible outcomes, or geometries, for the same givens, which mmay provide them with inspiration on how to go about a certain component. 

&nbsp;&nbsp;&nbsp;&nbsp;As for our project, we were to work with an electric longboard; more specifically, we were tasked to come up with a design for the hanger and motor mount component through use of generative design. Below are two different components (Nylon 12 and AlSi10Mg) created based on the same given obstacle and preserve geometries. 

##### Nylon 12 Component

![alt text](https://ChanwooLe2.github.io/assets/img/Paris1Render.png "Paris 1")

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e8d0b23bf95bdbd57?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

##### AlSi10Mg Component

![alt text](https://ChanwooLe2.github.io/assets/img/Paris2Render.png "Paris 2")

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e7609e01854733bbb?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

## Discussion

&nbsp;&nbsp;&nbsp;&nbsp;As could be observed in the two examples above, the generated components included plenty of rounded edges and/or unpredictable geometries that may be difficult to print via filament printing. Filament printing would be inefficient way to manufacture these components since an overall curved surface will require way more support material than desired (because otherwise bed adhesion would be poor and printability decreases significantly without supports). Not only are breakaway support materials not desirable, but these curved edges are difficult to create with such precision on filament printing due to a fixed print height, meaning that print resolution would be undesirable. Resin printing would be an undesirable method because of the cost and the size of the print (which at max is 210 mm). 

&nbsp;&nbsp;&nbsp;&nbsp;Powder bed fusion was our main manufacturing processes for its great resolution across any axis, print strength (physical properties), and most importantly the support-less print process. Though powder printing may be a bit costlier than filament printing, these comparative advantages of doing so proves its worth over all other manufacturing methods available at the Digital Fabrication lab.

&nbsp;&nbsp;&nbsp;&nbsp;Paired with generative design, powder bed fusion will allow for a great way to manufacture and test components in industries like aerospace and automotive where precision, creativity, and complexity is highly required. The ability to place key components (preserve geometries) and plenty of obstacle geometries to then let the AI do all the work is seemingly an efficient way to go about generating components that work in plenty of different ways. Even if they don't work, the generative design processes may provide certain key features that do work and may inspire future designs to include those specific features because of the advantages they provide. 

#### Real Life Image of Component with Respect to Longboard

![alt text](https://ChanwooLe2.github.io/assets/img/20240424_165112.jpg "RealLife")

## Limitations

&nbsp;&nbsp;&nbsp;&nbsp;If paired with highly detailed load cases and a multitude of obstacle geometries that prevents the AI from generating restrictive models (or even incompatible models) generative design has the potential to produce multiple high-quality parts that would take more hours to design by hand. Even if the generated model cannot be used for actual use, some of its favorable attributes may be recycled for the next sets of generative design model or even built upon by hand. Whether or not this technology is an efficient method to design, some degree of success may be achieved, given that it is paired with a spotless load cases and obstacles geometries.

&nbsp;&nbsp;&nbsp;&nbsp;Problem arises when it is difficult to provide the AI with a specific and accurate load case and/or the obstacle geometries leave too much space for the AI to venture into model concepts that are considered incompatible. In the case of our electric longboard, load cases were, for the most part, common sense loads, and the others were mere approximations of loads that the board might face. Without delving deep into force analysis and multiple calculations, it is difficult to provide the AI such loadcases that may be more suited for our needs. The fact that the AI was able to generate working models itself is impressive, but considering the amount of time that was put into generating parts may take away from the usefulness of generative design. 

&nbsp;&nbsp;&nbsp;&nbsp;Furthermore, the whole generative design process requires much more than you would expect when it comes to providing the AI obstacle geometries. Not only do these geometries have to be in specific locations, the bodies themselves must not be detailed since the AI takes longer to create designs which may lead to failures. Much of our struggles, as a class, came from the AI placing much more material in places we did not want any in, leading to bulky outcomes (see image below).

![alt text](https://ChanwooLe2.github.io/assets/img/Paris3Fail.png "Paris 3")

&nbsp;&nbsp;&nbsp;&nbsp;Even if the preview reveals models that look perfect, the actual outcomes may fall short in detail, and the wait time needed for each generative design iteration is too significant to the point you would expect to start a generative design iteration overnight or early in the day for it to finish hours later. When considering all the drawbacks to generative design, it is likely that one may consider it an inefficient method to go about CAD modeling. Nearly all drawbacks point to the fact that the generative design is not a timely efficient process which is ironic given that the AI is supposed to design the whole model itself rather than humans needing to spend time designing the part by hand.

&nbsp;&nbsp;&nbsp;&nbsp;To maximize the balance between labor put into setting up generative design and the usefulness of the outcomes, one may find it moer useful to use generative design as a process to get inspiration from rather than relying on it for the main model. Even if the generative design provides invalid models, one may find some aspects of the component useful and may build upon that aspect or add it onto their current model. However one may go about using generative design, it is important to consider the amount of time required to go through the whole process if it is expected of the AI to generate a perfectly working model within the first attempt, provided that they are not lucky.
