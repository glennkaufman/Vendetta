# Vendetta Toolhead Assembly Guide

Welcome to the official assembly guide for the **Vendetta Toolhead**—designed to deliver fully functional ability to use your V400 with Box Turtle!
Fully fuctional toolhead cutting, filament sensors, lighting, Canbus or USB, CPAP or stock cooling.

---

## 🔧 Tools & Materials Required

* Original V400 effector for base parts
* Allen wrenches (1.5mm to 4mm)
* M3 screws (various lengths)
* Heat inserts
* Soldering iron (for inserts)
* BOM Hardware
* Your full set of Vendetta STLs

---

## 📦 Bill of Materials (STLs)

*All STL files are organized in subfolders within `/models/STLs/`*
*Hardware BOM coming soon!*

### Main Body

* [`main_body_front_enable_supports.stl`](models/STLs/main_body_front/main_body_front_enable_supports.stl)
* [`main_body_rear.stl`](models/STLs/main_body_rear/main_body_rear.stl)

### Cutter Arm

* [`cutter_arm.stl`](models/STLs/cutter_arm/cutter_arm.stl)
* [`cutter_arm_button.stl`](models/STLs/cutter_arm/cutter_arm_button.stl)
* [`cutter_arm_button_v2.stl`](models/STLs/cutter_arm/cutter_arm_button_v2.stl)

### Shroud

* [`shroud.stl`](models/STLs/shroud/shroud.stl)
* [`shroud_fan.stl`](models/STLs/shroud/shroud_fan.stl)
* [`shroud_logo.stl`](models/STLs/shroud/shroud_logo.stl)

### CPAP Adapter

* [`cpap_upper.stl`](models/STLs/cpap/cpap_upper.stl)
* [`cpap_mid_left.stl`](models/STLs/cpap/cpap_mid_left.stl)
* [`cpap_mid_right.stl`](models/STLs/cpap/cpap_mid_right.stl)
* [`cpap_low_left.stl`](models/STLs/cpap/cpap_low_left.stl)
* [`cpap_low_right.stl`](models/STLs/cpap/cpap_low_right.stl)

### Idler

* [`idler_with_supports.stl`](models/STLs/idler/idler_with_supports.stl)

### Fan Duct Covers

* [`Fan_Duct_Covers.stl`](models/STLs/fan_duct_covers/Fan_Duct_Covers.stl)

---

## 🧠 Assembly Overview

The Vendetta Toolhead is a modular, high-performance design tailored for Box Turtle Automated Filament Changer.

![Overview Front](assembly/images/overview/overview_front.png)
![Overview Back](assembly/images/overview/overview_back.png)
![Overview Perspective](assembly/images/overview/overview_top.png)

---

## 🧱 Main Body (Front)

Secures to the effector via the heatsink. Houses cutting blade, filament sensor, and EBB42.

![Main Body Front](assembly/images/main_body_front/main_body_front_perspective.png)

---

## 🧱 Main Body (Rear)

Secures to the main body front. Mounts the stock stepper for the extruder.

![Main Body Rear](assembly/images/main_body_rear/main_body_rear_perspective.png)

---

## ⚙️ Cutter Arm

Used for filament cutting. Options for cutting your own chisel blades or purchasing bambu cutter blades.

![Cutter Arm Perspective](assembly/images/cutter_arm/cutter_arm_perspective1.png)

---

## 🌬️ Shroud

Ability to integrate Knomiv2 or strictly run heatbreak fan with nose cone.

![Shroud Front](assembly/images/shroud/shroud_front.png)
![Shroud Perspective](assembly/images/shroud/shroud_perspective1.png)

---

## 🫁 CPAP Adapter

Optional component for integrating an external CPAP high-flow fan.

![CPAP Front](assembly/images/CPAP/CPAP_front.png)
![CPAP Perspective](assembly/images/CPAP/CPAP_front_perspective.png)

---

## 🛞 Idler

Extruder tension arm for filament path.

![Idler Front](assembly/images/idler/idler_perspective.png)

---

## ✅ Final Assembly Checklist

* [ ] All bolts torqued
* [ ] Threadlocker applied where needed
* [ ] Fan and CPAP tested
* [ ] Belt alignment verified
* [ ] Hotend wired and verified

---

## 📹 Assembly Video

*Coming soon to YouTube — stay tuned!*

---

## 🧠 Notes

* For firmware configurations, PID tuning, and offsets, refer to your printer’s mainboard documentation.
* Contributions welcome. Submit pull requests or file issues as needed.

---

## 🔗 License

MIT License. Build, remix, and share—with attribution.
