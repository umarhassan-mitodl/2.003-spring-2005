---
content_type: page
description: ''
learning_resource_types:
- Laboratory Assignments
ocw_type: CourseSection
parent_title: Labs
parent_type: CourseSection
parent_uid: fbc55028-b2c1-01c5-c62c-62ab407df92b
title: 'Lab 3: Translational 2nd-order Spring/Mass/Damper System; Natural Response;
  Fitting Models'
uid: 25155917-3a3b-bdbb-e7a3-db6c7794f661
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

Pre-Lab ({{% resource_link bc9e16c5-a134-62aa-4400-a4f3c4515399 "PDF" %}})  
Lab 3 Description ({{% resource_link 9dbe80ba-2002-3f62-4f29-c63172ff5fd5 "PDF" %}})

In this lab, the dynamics of a second-order system composed of a spring, mass and damper are examined. As shown in figure 1, the system consists of a cylindrical shaft riding on air bearings. A voice coil is attached at the left side to add variable damping. The voice coil armature is wound on an aluminum cylinder. If the coil is open-circuited, some damping is still present due to eddy currents in the aluminum. If we short-circuit the voice coil the damping is increased significantly, because of resistive losses in the wire. In the middle between the two air bearings, an adjustable spring is attached to the shaft. By decreasing the length of the spring, the natural frequency of the system is increased and the damping ratio is decreased. By adjusting the length of the spring, one can demonstrate overdamped, critically damped and underdamped behavior. A pulse can be applied to the system by allowing a small brass ball hanging on a piece of string to impact the plate attached to the shaft at the right. To measure the motion, an LVDT (Linear Variable Differential Transducer) is fixed on the right side of the shaft. See Prelab3 page 5 for an explanation of LVDT operation.

{{< resource "3b40b703-d670-62c6-efbf-37a3b2f4996f" >}}

Figure 1. The second order system with voice-coil, air bearings, adjustable spring, shaft mass, and LVDT sensor. (Image by Prof. Trumper.)

Figure 2 shows the drawing of this system.

Note the schematic detail in figure 2 that shows the off-center attachment of the spring to the collar on the shaft. The reason for this is to allow for axial displacements of the end of the spring by free rotation of the shaft. If the spring is bend, it shortens a distance d, as shown in figure 2 on the bottom right. If the spring was not attached this way, the actual stiffness would be much larger. More importantly, the linearity of the stiffness would be much less because of the unwanted axial pulling force on the spring rod.

{{< resource "7557814d-8880-ebd4-5ead-84d2ee2b6f11" >}}

Figure 2. Drawing of the first-order rotary system. (Image by Prof. Trumper.)

Figure 3 shows the idealization of its dynamics.

{{< resource "11dad6d1-583e-df92-db3c-2d0b2a31edb3" >}}

Figure 3. A Brass ring can be added to increase the inertia. (Image by Prof. Trumper.)

Figure 4 shows the Close-up spring collar attachment.

{{< resource "65642777-21b6-50ea-bdbf-8b25814da615" >}}

Figure 4. Close-up spring collar attachment. (Image by Prof. Trumper.)

The signal passes through a signal conditioner and is made visible on an oscilloscope in Figure 5.

{{< resource "61a99f52-7e2c-1e15-f4ed-ca3aa5aa66ca" >}}

Figure 5. Overdamped impulse response. (Image by Prof. Trumper.)

The signal passes through a signal conditioner and is made visible on an oscilloscope in Figure 6.

{{< resource "86d4ff4f-583e-b231-5855-7f898908863d" >}}

Figure 6. Underdamped impulse response. (Image by Prof. Trumper.)

Materials and Notes: Practical Info and Comment
-----------------------------------------------

*   Adjustable spring clamp
    
*   Air bearings from New Way, see Lab 2. They do not mount directly to optical breadboard, so we made special adaptor plates from Pelrin. Another simpler option to attach the bearings to the baseplate would be to use toeclamps.
    
*   Angle plate 3X3X3 inch ground steel (flat surfaces) from Suburban Tool, inc.
    
*   Collars see Lab 2.
    
*   Optical breadboard
    
*   LVDT (Linear Variable Differential Transducer) Schaevitz HR-1000 ($450 each) was the best choice, because of the large clearance through the hole in the body of the sensor. LVDT's with smaller clearance caused problems with alignment. This sensor has a hole all the way through. It is unguided, i.e. does not use bearing surfaces, to avoid friction.
    
*   Separate signal conditioner ($167) is needed for this LVDT.
    
*   Shaft Thompson shafting, necessary threading can be specified, precision ground stainless steel, diameter 3/4 inch to match the air bearings.
    
*   Spring
    
*   Stand
    
*   Voice coil LA24-33 BEI-Kimco seems to be the only manufacturer for this type of part. Prices are much lower when ordering in large quantities ($315 each when ordering 30).