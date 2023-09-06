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

* **Interchangeable Syringe Sizes** This syringe pump accommodates two different syringe sizes, a 5 mL syringe and a 20 mL syringe. There is a small piece that can easily be attached when using the smaller syringe.
* **CAD Modeling** Six different parts were designed in Fusion 360 to create an effective and stable syringe pump. Then, a complete syringe pump design was modeled to simulate its capabilities and to ensure each part would fit together properly once 3D printed.
* **Wiring** An LED light, button, stepper motor, and power supply were wired to a breadboard with all electrical connections properly soldered and protected. 
* **Arduino Programming** An Arduino was then programmed to rotate the motor, push the syringe plunger forward, and flash a green, yellow, or red light depending on the status of the pump. [Arduino Code](Arduino Code.pdf)

# Operating the Syringe Pump

* Once the syringe has been inserted into the device, the button is pressed once to start the motion of the pump. The button can be pressed again to pause the syringe pump. Once the syringe is completely emptied, a switch is triggered and the pump stops.

# Off-the-Shelf Parts

| Part | Quantity | Specifications |
| ---- | -------- | -------------- |
| Flexible Coupling | 1 | 1/4" x 8mm |
| Lead Screw | 1 | 250 mm length x 2 mm pitch x 2 mm lead
| Linear Rod | 2 | 200 mm length x 8 mm diameter |
| LM8UU Linear Bearing | 2 | for 8 mm diameter rod |
| 2040 Aluminum Extrusion | 1 | 1 ft |
| Stepper Motor | 1 | Nema 17 |
| Power Supply | 1 | Quad Output 5V 12V 24V 12V 4 Amps |
| Arduino Uno | 1 | None |
| Stepper Motor Driver | 1 | 5V |
| Small Breadboard | 1 | None |
| Panel Mount Latching Push Buttons | 1 | 0.5 Amps |
| Limit Switch | 1 | 5 Amps |
| RGB Common Cathode LED | 1 | 10 mm |

# 3D Printed Parts

| Part | Link |
| ---- | ---- |
| Interchangeable Front Barrel Stabilizer | [Part 1](https://a360.co/3R3PZmG) |
| Plunger Holder | [Part 2](https://a360.co/3Evrrvn) |
| Motor Mount | [Part 3](https://a360.co/3LdhPcf) |
| Enclosure | [Part 4](https://a360.co/3LdHh1s) |
| Top of Enclosure | [Part 5](https://a360.co/4816DJH) |
| Back Barrel Stabilizer | [Part 6](https://a360.co/480DwpU) |

# CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH35dfcQT936092f0e4396a787ea53f9a532?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>


# Gallery
{% include gallery caption="Side by side images of the real life syringe pump with the 3D rendering." %}
