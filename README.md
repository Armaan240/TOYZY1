# TOYZY
TOYZY isn’t just a 3D printer. It’s something I’ve dreamt of building from the ground up — a project that started as a wild idea and slowly turned into reality, piece by piece. I didn’t buy kits, I didn’t clone someone else’s design. I wanted to make my own version, fully custom — with a goal to actually understand every nut, bolt, wire, and line of code that goes into making a 3D printer tick.

The frame is made of aluminum extrusions, connected by joints I modeled and plan to 3D print myself. Inside, it runs on an Arduino Mega and RAMPS board, with a touchscreen display, (NFC potential, and Wi-Fi modules coming soon). It’ll feature a dual Z-motor system for extra stability and a compact, custom-designed extruder I call the TOYZY head, with three fans, sleek aesthetics, and serious performance. I designed every inch of the printer in Fusion 360, from the frame down to the cable mounts.
**Also Please Ignore the missing part in The third Image It may Due to a Techincal Glitch**

![](https://github.com/Armaan240/TOYZY1/blob/main/IMAGES/Screenshot%20(57).png)
![](https://github.com/Armaan240/TOYZY1/blob/main/IMAGES/Screenshot%20(58).png)
![](https://github.com/Armaan240/TOYZY1/blob/main/IMAGES/Screenshot%20(59).png)
![](https://github.com/Armaan240/TOYZY1/blob/main/IMAGES/Screenshot%20(60).png)
## Why I Created It
I’ve always been fascinated with machines that create — CNCs, plotters, robots, 3D printers. But 3D printing stuck with me. I’ve seen people buy off-the-shelf machines and never really learn how they work. I didn’t want that. I wanted to build the machine, not just use it.

It became more than just a printer. It became a challenge to myself: Can I really build something this complex from nothing? Can I figure out the mechanical parts, the electronics, and even the firmware? Can I make it look cool and functional — not just work, but feel like mine?

## The Bucket List Moment
This whole project actually came from a random "bucket list" I wrote for myself one night. I was just thinking about all the things I want to do before I'm too busy to take on big ideas. One of the things on that list was “Build a full 3D printer from scratch.” No pre-made kits, no shortcuts. Just me, my laptop, a soldering iron, and way too many late nights.

I didn’t expect to actually start this so soon — but once I began designing the frame in Tinkercad (and quickly realized its limits), I downloaded Fusion 360 and went all in. From there, it became an obsession. Every part I model or assemble is me crossing off one more item from that list.

## 📦 TOYZY BOM

| Category                      | Part                                                  | Qty | Unit Price | Shipping | Total       | Link                                                                |
| ----------------------------- | ----------------------------------------------------- | --- | ---------- | -------- | ----------- | ------------------------------------------------------------------- |
| **Controller Kit**            | Mega2560 + RAMPS 1.4 + TMC2209 Drivers + 12864 LCD    | 1   | \$24.00    | \$11      | **\$35.00** | [Buy LInk](https://www.alibaba.com/product-detail/SeekEC-CNC-3D-Printer-Kit-with_1600800203589.html?spm=a2700.galleryofferlist.normal_offer.d_title.2e5d13a0pZEiPm) |
| **Stepper Motors**            | NEMA17 Stepper Motors (1.68A, 42mm)                   | 6   | \$3.00     | \$26    | **\$42.00** | [Buy LInk](https://www.alibaba.com/product-detail/SUMTOR-NEMA-17-Stpper-Motor-42HS4013A4CE_62423940277.html?spm=a2700.details.you_may_like.1.78975071uLiSXz)   |
| **Smooth Rods (8mm × 400mm)** | Chrome-polished precision rods                        | 4   | \$5.50     | \$8      | **\$30.00** | Sourced Locally |
| **Nuts and Bolts** | 2-5mm nut and bolts                      | 50   | -    | \$8      | $5 | Sourced Locally |
| **T8 Lead Screws (400mm)**    | With brass nut                                        | 2   | \$3.00     | \$4      | **\$7.00** | [Buy LInk](https://robu.in/product/400mm-trapezoidal-lead-screw-8mm-thread-2mm-pitch-lead-screw-copper-nut/) |
| **GT2 Timing Belt (5m)**      | 6mm width, reinforced                                 | 1   | \$2.00     | \$2      | **\$4.00**  | [Buy LInk](https://www.amazon.in/Robodo-Electronics-PR60-Timing-Printer/dp/B07881N24Q/ref=pd_lpo_d_sccl_1/260-1406153-5055739?pd_rd_w=kLomu&content-id=amzn1.sym.e0c8139c-1aa1-443c-af8a-145a0481f27c&pf_rd_p=e0c8139c-1aa1-443c-af8a-145a0481f27c&pf_rd_r=9J2S7Y3Y0BJTNWSVJ5R4&pd_rd_wg=pJWLU&pd_rd_r=c4c8056b-44a0-4ad3-ac54-c72ab070c158&pd_rd_i=B07881N24Q&psc=1) |
| **GT2 Pulleys (20T)**         | 5mm bore + screws (4 pcs)                             | 4   | \$1.20     | \$2      | **\$6.80**  | [Buy LInk](https://www.flipkart.com/serplex-gt2-pulley-20-teeth-5mm-bore-6mm-width-20t-timing-belt-wheel-aluminum-fitting-connector/p/itm7c58dc564cab2?pid=TDIH2FU4YKUJ8EDH&lid=LSTTDIH2FU4YKUJ8EDHBMAUTT&marketplace=FLIPKART&cmpid=content_three-d-printer-accessories_8965229628_gmc) |
| **LM8UU Bearings**            | Polymer-coated, low noise                             | 10  | \$1     | \$3      | **\$13.00** | [Buy LInk](https://onlineshop.goldenbearingcompany.com/product/lm8uu-8-mm-linear-motion-bearing/?srsltid=AfmBOopL2a7UoDKKg_wbQwxKIWUuEnq-lPPzE1W3I5xxOSaSDe6bE0YX) |
| **Heated Bed MK2B**           | 214×214mm + wiring                                    | 1   | \$14.00    | \$10      | **\$24.00** | [Buy LInk](https://www.alibaba.com/product-detail/235x235mm-200W-24V-Silicone-Heated-Bed_1600133444717.html?spm=a2700.galleryofferlist.normal_offer.d_title.3af113a01s24GU) |
| **E3D V6 Hotend clone **     | All-metal, Volcano-ready                              | 1   | \$18.00    | \$-      | **\$10.00** | [Buy LInk](https://www.amazon.in/Robodo-Electronics-PR46-J-Head-Extruder/dp/B0787KN8BC) |
| **E3D Extruder **     | All-metal, Volcano-ready                              | 1   | \$35.00    |  —     | **\$35.00** | [Buy LInk](https://robu.in/product/e3d-titan-extruder-direct-drive-1-75mm/?gad_source=1&gad_campaignid=17427803012&gbraid=0AAAAADvLFWf3c0f90Vj42PDMoCQ2ah0Z5&gclid=Cj0KCQjw64jDBhDXARIsABkk8J5PemK91RqrIu1bteplkHbeO1IMpQpk6aNlHuobJ0plAKiYbrV38TEaAh8bEALw_wcB) |
| **Heater Cartridge (40W)**    | 12V, ceramic                                          | 1   | \$10.00     | \$1      | **\$11.00**  | [Buy LInk](https://robu.in/product/original-prusa-hotend-heater-cartridge-e3d-24v-40w-mini/?gad_source=1&gad_campaignid=17427803012&gbraid=0AAAAADvLFWf3c0f90Vj42PDMoCQ2ah0Z5&gclid=Cj0KCQjw64jDBhDXARIsABkk8J6UiFKhN4J44pee42mYhR8kFP99nFmTabaENmFLMH_NnWUAFyBuvmYaAv-1EALw_wcB)    |
| **Thermistors (100K)**        | —                                          | 2  | \$1     | \$1      | **\$3**  | [Buy LInk](https://robu.in/product/original-prusa-hotend-heater-cartridge-e3d-24v-40w-mini/?gad_source=1&gad_campaignid=17427803012&gbraid=0AAAAADvLFWf3c0f90Vj42PDMoCQ2ah0Z5&gclid=Cj0KCQjw64jDBhDXARIsABkk8J6UiFKhN4J44pee42mYhR8kFP99nFmTabaENmFLMH_NnWUAFyBuvmYaAv-1EALw_wcB) |
| **4010 Fans**          | 3 pcs for hotend and part cooling                     | 3   | \$2.00     | \$2      | **\$8.00**  | [Buy LInk](https://www.amazon.in/12V-4010-Cooling-Fan-Printer/dp/B09PBW1WCC?th=1) |
| **Mechanical Endstops**       | Pre-wired, pack of 3                                  | 3   | \$0.60     | \$2      | **\$3.80**  | [Buy LInk](https://robu.in/product/cnc-3d-printer-mech-endstop-switch/) |
| **Power Supply (12V 20A)**    | Enclosed SMPS unit                                    | 1   | \$9.00    | \$2    | **\$11.00** | [Buy LInk](https://ebhoot.in/shop-2/power-supply/smps/12v-20a-240watt-smps-dc-metal-power-supply-with-cooling-fan/?srsltid=AfmBOoq04yXPv75jBKuhN5sjb6Wn0EWkAjI5LJw3URiWQbs1_voczo8OKbE) |
| **Wiring & Connectors**       | Heatshrink, Dupont, JST, silicone wire                | —   | —          | —        | **\$12.00** |Sourced Locally                                                                   |
| **3D-Printed Parts**          | Printed from JLC3DP/3Ding (corners, carriage, mounts) | —   | —          | —        | **\$40.00** | —                                                       | CapMountForZaxis      |                     —                                 | 2  |  — | —      | —   | |
| STepMotorMountZaxis       | "                                       | 2  |  —    |  —      |  —  |  — |
| BedMount       | "                                       | 2  |  —    |  —      |  —  |  — |
| Customized Toyzy EXtruder CAse       | "                                       | 1  |  —    |  —      |  —  |  — |
| smoothrod mount       | "                                       | 4  |  —    |  —      |  —  |  — |
| STepMotorMountZaxis       | "                                       | 2  |  —    |  —      |  —  |  — |
| pullyMotorMountZaxis       | "                                       | 2  |  —    |  —      |  —  |  — |
| Stands       | "                                       | 2  |  —    |  —      |  —  |  — |
### ✅ **Grand Total: ≈ \$310 USD**
