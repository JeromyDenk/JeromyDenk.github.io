---
layout:     single
classes:    
    - wide
title:      Ice Pyramid Building Machine - Second Year Design Project
date:       2017-02-04 
categories: projects
header:
  image: http://via.placeholder.com/1280x400
---


# Introduction
Every year at the University of Ottawa, students enrolled in MCG2101 - Introduction to Design are tasked with designing and 3D-modeling a machine according to a fictional mandate written by the professor. This year, students were given the choice of either designing:
- a vertical belt-driven rock-climbing machine
- a portable machine that autonomously builds pyramid-shaped lodgings made of ice blocks

My teammates and I decided on the latter option. This is what we came up with:

(Image)

# Design Criteria & Restrictions
As part of the mandate, a number of restrictions and design criteria were placed on the design of the machine. Among some of them, which are detailed in the [full project report](/assets/docs/MCG2101-Final-Project-Report.pdf) are as follows:
- up to five electric motors may be used
- no digital logic may be used (eg: microcontrollers)
- contact switches may be used to activate motors
- the machine may only require on operator to start and stop the machine
- the machine must use an onboard Peltier cooler to create the ice blocks
- the machine should be easily transportable

In order to simplify the design-process for second-year students, the project also contained a number of "suspensions of disbelief":
- assume rotational power inputs have infinite torque
- ice blocks freeze in exactly 30 seconds
- assume rigid body mechanics (no deformation of parts)

## The Ice Pyramid
The lodging constructed by the machine must consist of a hollow square-based pyramid with a 10 x 10 block base. It is made of 181 ice blocks each measuring 60cm x 60cm x 30cm (L x W x H). The door to the lodge is to be cut into the side of the pyramid after it is built and thus doesn't need to be accounted for.

(PICTURE OF ICE PYRAMID)

# Solution

## Overview
The design of the machine is centered around a collapsible gantry-style frame. This style of frame was chosen to minimize the width of the machine allowing it to be easily transported atop a flatbed trailer. Ice blocks are deposited from a sliding door located on the bottom of the peltier cooler. Lateral movement of the peltier cooler is accomplished via the machine's wheels, vertical movement is accomplished by retracting or extending the telescoping box housing the peltier cooler, and longitudinal positioning is accomplished by 

(LABELED DIAGRAM)


## Positioning the Peltier Cooler

# Lateral Positioning
(Animation of wheels moving)

# Longitudinal Positioning
(Animation of carriage sliding)

# Vertical Positioning
(Animation of box telescoping)

## Transmission
- how 2 forward reverse and neutral
	- how the 3 clutch mechanisms work

## Controller/Power Distribution
- most difficult part to design
- Central question: How do you mechanically control the 3 clutches? 
- The inspiration (Gramophone, etc)
  How to encode instructions without a computer
- Barrel cams
- Programming the cam followers
	- Optimal way to travel around pyramid

## Peltier Cooler
- 


Graphics
    - 



Design Restrictions:
- Pyramid
  - shape
  - block size
- Machine
  
