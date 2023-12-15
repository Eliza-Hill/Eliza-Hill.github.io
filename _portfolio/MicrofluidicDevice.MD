---
title: "Microfluidic Device"
excerpt: "Created a microfluidic mixing device that leverages vat photopolymerization printing."
header:
  image: assets/img/Standing Pliers.jpg
  teaser: assets/img/Pliers Flat.jpg
gallery:
  - image_path: assets/img/Exploded Pliers.jpg
  - image_path: assets/img/Iteration.jpg
   
---
# Overview

The purpose of this project was to create a microfluidic device that is able to thoroughly mix multiple samples. By creating various configurations for the channels, turbulent flow is created, which leads to efficient mixing. My device was designed to be applied in covid testing. The patient sample is placed in one inlet post while the testing reagent is placed in the other inlet. The channels are wide enough to support both inlets, but the mixing is thorough enough to make sure that all of the patient’s sample has been mixed with the testing reagent. This means that this device is able to accurately test patients for covid with the outlet mixture that is provided.

![Pliers GIF](/assets/img/Pliers GIF.gif)

# About the Design 

**Rationale**

The focus of my microfluidic device was on passive mixing. In order to create turbulent flow without external forces, the configurations of the channels had to be disruptive. While researching different configurations, the ones that most stood out to me were zigzag microchannels, 3-dimensional half-circles, and parallelogram barriers. Thus, I decided to combine these three features in one device. I first established that the width of the channels would be 2 mm and the height would be 2.5 mm because these channels would be large enough to contain the covid testing samples, but small enough to facilitate mixing. Furthermore, this would ensure that the channels would be able to withstand the post-processing, as the aspect ratio, which is the height to width of the channels, would be less than 3:1. To determine the dimensions and shapes of the specific channel configurations, I then looked to outside research. For the zigzag channels, the optimal geometry was found to have a ratio of s/w of 4, where s is the distance between two consecutive peaks, and w is the diagonal width of the channel. Since the width of the channels had already been determined to be 2 mm, w was 1.414 mm. Therefore, I made the distance between the peaks 5.657 mm to give these features a ratio of 4. In order to incorporate a 3-dimensional feature, I decided to make protruding semi-circles. The height of the channels is 2.5 mm, so I decided to make the radius of the semi-circle 2.125 mm. This meant that the samples would have to be pushed together through a small 0.375 mm channel height, which would encourage further mixing. Finally, for the parallelogram barriers, I determined that the optimal angle of the parallelograms was 45 degrees. Next, papers recommended making the height half of the width of the mixing channel, so I made the height of the parallelograms 1 mm. Finally, for the width of the parallelograms, I decided to make them very small with a width of 0.5 mm. I was slightly worried about whether these small features would be able to hold up during the process, but I was able to successfully demold this section without any issues. 


![Image of Octopus Flexible Gadget](/assets/img/Octopus.jpg)

**Vat Photopolymerization**

Usually, microfluidic devices are made by photolithography. However, photolithography is very expensive, time-consuming, and is limited in the geometries that it can produce. To address these limitations, 3D printing can be used to make microfluidic molds. Although it isn’t quite as high resolution as photolithography, the Form 3 SLA printer that I utilized had a resolution of 25 microns and can create features with a minimum size of 85 microns. Thus, vat photopolymerization was chosen to produce the mold because it is cheaper and can produce complex and high-resolution geometries. There are a few drawbacks to using this vat photopolymerization technique to make microfluidic devices, including the possibility of warping during curing or uncured resin preventing crosslinking with the PDMS. However, the biggest limitation with this technique is the parylene coating step. Although the parylene makes the mold biocompatible and allows it to be cast with PDMS, the parylene coating machine is very expensive. In addition, the coating does not always work, which can lead to even more time and money wasted. 

# Instructions
In order to go from the 3D printed mold to the final device, the microfluidic mold must first be printed in a vat photopolymerization printer. After the print is complete, it must be thoroughly washed. There can’t be any uncured resin remaining on the part, as it will inhibit crosslinking with the PDMS. Then, the part must be cured depending on the resin that was utilized. Since I used high-temp resin, I cured my part for 60 minutes at 60°C. After the mold is printed, washed, and cured, the mold is coated with a thin layer of parylene. Next, the mold is cast with PDMS to create the microfluidic device and channels. After demolding the PDMS device, a glass slide is plasma bonded to the device to create a tight seal that will ensure the fluids remain within the channels.

# CAD Model of the Microfluidic Mold
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e69c0c8c71e462fa7?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

![Image of First Iteration of the Flexible Piece](/assets/img/Flexible Iteration.jpg)

# Gallery
{% include gallery caption="The first image includes all of the separate pieces of the final model. The second picture demonstrates the first iteration of the pliers." %}
