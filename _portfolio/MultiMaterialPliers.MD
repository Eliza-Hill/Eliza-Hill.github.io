---
title: "Mutli-Material Pliers"
excerpt: "Created flexible pliers made from a combination of PLA and TPU parts."
header:
  image: assets/img/Standing Pliers.jpg
  teaser: assets/img/Pliers Flat.jpg
gallery:
  - image_path: assets/img/Exploded Pliers.jpg
  - image_path: assets/img/Iteration.jpg
   
---
# Description of Project

In this project, I created needle nose pliers that are able to grip and move through-hole resistors. By using a flexible component in the center that connects to four rigid parts, the pliers can pick up different items when force is applied to the handles. Then, once the handles are released, the pliers return to their original position.

![Pliers GIF](/assets/img/Pliers GIF.gif)

# Print-In-Place Parts

**Overview**

With print-in-place, the different parts of a product are modeled so that they are ready for use once the print is finished. The biggest benefit to this technique is that production can happen much quicker. Final products can be delivered directly from the 3D printers without any additional processing or assembly time. 



**Applications**

For single material extrusions, print-in-place is often utilized to facilitate movement within products. This can be accomplished by incorporating joints, springs, or gears in the product. Print-in-place allows for specific clearances to be achieved when printing these elements. This can be seen in many flexible gadgets and toys, such as the mini octopus pictured below. However, if the desired movement isn’t attainable with single material extrusion, multi-material extrusion can be used to add elements of different materials. Combining print-in-place with multi-material extrusion allows for flexible components to interconnect with different materials, leading to even more potential applications. Not only can joints, springs, and gears be incorporated, but additional geometries can be designed to explore more movement options.  

![Image of Octopus Flexible Gadget](/assets/img/Octopus.jpg)



**Combinations of Materials**

While multi-material parts can be very useful for print-in-place parts, the right combination of materials must be utilized. If multi-material bonding is desired, the following factors must be taken into account: surface energy, chemical composition, shrinkage and cooling rates, and mechanical compatibility. The combination of materials that work most effectively for print-in-place are those that have similar properties. This is because there will be better bonding between and within the layers of the different materials if the properties stated above are similar. If two materials with very different properties want to be used, then the part must be designed to provide mechanical constraints that interconnect the two materials.

# About the Design

**Materials** 

The two materials used in this design were 95A TPU and PLA. The flexible piece was printed with TPU so that it would bend when needed. The other components were printed with PLA because the rigidity gave the handle and pliers the necessary strength to bend the flexible piece.



**Rationale**

Since the materials that were used, PLA and TPU, have very different material properties, bonding between the two materials would most likely not occur. Therefore, the pieces of the pliers were designed to fit together like a puzzle. The first iteration of the flexible piece, pictured below, was created as a repeating square geometry with 3 protruding circles on each side to connect to the other pieces. After printing this piece, it was evident that the layers between the repeating squares were too thick, which meant that the piece was much more rigid than desired. Thus, after reprinting the piece, a thickness of 1 mm was found to have an adequate amount of flexibility. 

![Image of First Iteration of the Flexible Piece](/assets/img/Flexible Iteration.jpg)

After printing the flexible piece of the pliers, the next step in the design process was to find a way to retain that piece in the model. Top-down modeling was utilized to make the designs for the handles and clamps. Then, different clearances were tested and an offset of 0.4 mm was found to create the tight fit that was required to keep the pieces connected. Originally, the two handle pieces were meant to face each other. However, I found that flipping one handle the opposite way allowed there to be more space for the closing motion of the pliers. While this made for less traditional-looking pliers, I found that they worked very effectively.

# Plier Specifications:
* Jaw Length: 31.5 mm
* Jaw Capacity: 20 mm

# Print settings:
While the print-in-place technique can be utilized for this design, these pliers were printed as separate pieces on different printers due to low availability of multi-material 3D printers. Thus, one single material 3D printer was used to make the flexible component and another printer was used for the four rigid parts. The flexible component was printed with normal TPU print settings, and the rigid parts utilized normal PLA print settings.

# 3D Printed Parts

| Part | Quantity | Link |
| ---- | -------- | ---- |
| Handle | 2 | [CAD Model 1](https://a360.co/3Zwqa0H) |
| Top Clamp | 1 | [CAD Model 2](https://a360.co/3rtEp9T) |
| Bottom Clamp | 1 | [CAD Model 3](https://a360.co/3Po1T8j) |
| Flexible Piece | 1 | [CAD Model 4](https://a360.co/3Po1T8j) |

# CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e0e4b09e1ea3c9f7b?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# Gallery
{% include gallery caption="The first image includes all of the separate pieces of the final model. The second picture demonstrates the first iteration of the pliers." %}
