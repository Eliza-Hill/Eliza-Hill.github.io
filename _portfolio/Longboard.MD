---
title: "Electric Longboard"
excerpt: "Designed a longboard deck and truck using generative design, SLS printing, and large format 3D printing."
header:
  image: assets/img/Skateboard Rendering 2.png
  teaser: assets/img/Skateboard Rendering 1.png
gallery:
  - image_path: assets/img/SLS Printed Truck Pic 1.jpg
  - image_path: assets/img/SLS Printed Truck Pic 2.jpg
  - image_path: assets/img/Resin Printed Scale Skateboard.jpg
  - image_path: assets/img/Final Deflection Pic.jpg
   
---

# Description of Project

The first objective for the electric longboard was to design the truck hanger and motor mount. The truck hanger connects the wheels to the longboard deck while the motor mount holds a brushless DC motor. Generative design was utilized to combine these two features into one part, as well as aid in making it as lightweight and effective as possible. The second objective for the electric longboard was to design an aesthetic longboard deck that would be able to hold the weight of a person.

# Generative Design of the Truck

After modeling the preserve and obstacle geometries that couldn’t be changed, I then assigned the forces that would ensure the truck would be able to withstand normal riding conditions. This included loading the weight of a 200-pound person, the weight of the motor, which was 10 N, a moment force on the motor of 8 N m, based on the maximum torque that was reported by the motor manufacturer, and shear forces of 200 N on the wheels in case of impact. 

**Aluminum Truck CAD Model**

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6eb022c10e4900198f?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>


As for the materials, I experimented with both Nylon 12, which is the material used in the powder printer, and ALSi10Mg, a commonly printed aluminum alloy that would be closer to the typical material that you would use for longboard truck hangers. The CAD model of the aluminum truck is shown above, while the CAD model of the nylon truck is demonstrated below. Since the aluminum is stronger the nylon, the main difference between the two models is that the aluminum truck is lighter and uses less material. Nonetheless, the nylon truck is still very compact and effectively achieves the first goal of the longboard. 

**Nylon Truck CAD Model**

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e87fe0f92f44e2cd4?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>


# Utilizing Powder SLS Printing with Generative Design

In powder SLS printing, there are no limitations on the geometries that can be printed because the loose powder acts a support material. With generative design, models can be optimized, but it usually leads to irregular shapes and geometries. Therefore, pairing powder bed fusion with generative design can be incredibly rewarding. Regardless of the geometries that are modeled, the powder SLS printer is most likely able to successfully print the part. So, after finalizing the models using generative design, I SLS printed the nylon truck, and the printed part can be seen below. 

# Aerospace Applications

The benefits of powder bed fusion and generative design can be seen widely in the Aerospace industry. At GE Aerospace, additive manufacturing has been able to consolidate 300 parts into just 7 3D printed parts. At Jacobs, the use of generative design was able to optimize the design of the NASA life-support backpack. While maintaining the same high standards of safety and reliability, the use of generative design was able to make the final part 50% less mass. In addition to making more lightweight parts, generative design is able to reduce assembly costs and time, improve functionality, and increase aircraft energy efficiency. 

# Gallery
{% include gallery caption="" %}
