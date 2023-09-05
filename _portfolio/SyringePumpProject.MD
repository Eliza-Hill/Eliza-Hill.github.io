---
title: "Syringe Pump Project"
excerpt: "Built a functional syringe pump driven by a stepper motor coupled to a lead screw."
header:
  image: /assets/img/Syringe Pump.jpg
  teaser: /assets/img/Front Syringe Pump.PNG
gallery:
  - image_path: assets/img/Front Syringe Pump.PNG
  - image_path: assets/img/Back Syringe Pump.PNG
  - image_path: assets/img/Side Syringe Pump.PNG
   
---

# Features

* **Interchangeable Syringe Sizes** This syringe pump accomodates two diffferent syringe sizes, a 5 mL syringe and a 20 mL syringe. There is a small piece that can easily be attached when using the smaller syringe.
* **CAD Modeling** Four different parts were designed in Fusion 360 to create an effective and stable syringe pump. Then, a complete syringe pump design was modeled to simulate its capabilities and to ensure each part would fit together properly once 3D printed.
* **Wiring and Programmming** An LED light, button, stepper motor, and power supply were wired to a breadboard with all electrical connections properly soldered and protected. An Arduino was then programmed to rotate the motor, push the syringe plunger forward, and flash a green light when the button was pressed once. If the button was pressed again, the syringe pump pasued, the motor stopped, and a yellow light flashed. Once the syringe pump was completely emptied, a swicth was triggered that stopped the motor and flashed a red light.

# Off-the-Shelf Parts

|             Part              | Quantity |
| ----------------------------  | -------- | 
| 1/4" x 8mm Flexible Coupling  |     1    |
| 200 mm lead screw with 2 mm pitch and 2 mm lead | 1 |



# 3D Printed Parts

# CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH35dfcQT936092f0e4396a787ea53f9a532?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# Gallery
{% include gallery caption="Side by side images of the real life syringe pump with the 3D rendering." %}
