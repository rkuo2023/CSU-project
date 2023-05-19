---
layout: post
title: Quadruped Robot
author: [Richard Kuo]
category: [Lecture]
tags: [jekyll, ai]
---

創新應用之機器狗

## Content
* **專題題目** (Project Name & Objectives)
* **應用與功能說明** (Key Features)
* **設計考量與所需相關技術** (Design considerations)
* **系統方塊圖** (System Block Diagrams)
* **概念驗證** (Proof of Concept)
* **成果展示** (Demostation)

---
## 機器狗
類別: 四足機器人 <br>

目的: To-Be-Discussed <br>

<iframe width="878" height="494" src="https://www.youtube.com/embed/Kz3gDpoZsoE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---
### 應用功能說明
1. AI視覺辨識
2. 自動導航

---
### 設計考量與相關技術
**系統設計考量：**<br>
1. 移動方式: 四足
2. 供電方式: 鋰電池

**所需相關技術：**<br>
1. AI視覺辨識

---
### 系統方塊圖
TBD

---
### 概念驗證

---
### 開發進度與展示

---
## 參考資料:

### [Philon Wave](https://philon.ai/wave)

### [Github](https://github.com/alexandrospetkos/quad)**<br>
Components:
* 1x Esp32 or an Arduino compatible board.
* 1X Sipeed M1 Dock - K210 Development Board
* 1x **PCA9685** 16-Channel 12-bit PWM Servo Motor Driver I2C Module
* 1x 7805 TO-2205V - 1.5A Linear Voltage Regulator
* 1x Li-Po Battery 7.4V 2600mAh
* 12x JX Servo **PDI-HV5932MG** 30KG Large Torque 180°
* 4x M3 Adjustable Push Rod End Ball Joint Linkage
* 4x 6900zz Ball Bearing 10x22x6mm
* 8x 626zz Ball Bearing 6x19x6mm
* various bolts & nuts
![](https://m.media-amazon.com/images/I/612FwOyJgFL._AC_SX679_.jpg)

---
### Source Code: [Source ESP32](https://github.com/alexandrospetkos/quad/tree/master/source%20code/source_esp32)
* [source_esp32.ino](https://github.com/alexandrospetkos/quad/blob/master/source%20code/source_esp32/source_esp32.ino)
* [kinematics.ino](https://github.com/alexandrospetkos/quad/blob/master/source%20code/source_esp32/kinematics.ino)
* [hardware.ino](https://github.com/alexandrospetkos/quad/blob/master/source%20code/source_esp32/hardware.ino)

---
### Simulation
[Warp_simulation_v5](https://github.com/alexandrospetkos/quad/tree/master/simulation/warp_simulation_v5) using Processing 4.0b7<br>
* Navigation controls:
  mouse, keyboard ['W'], ['A'], ['S'], ['D'], ['Q'], ['E'].
 
* Simulation controls:
  keyboard [KEY_UP], [KEY_DOWN], [KEY_LEFT], [KEY_RIGHT], ['['], [']'], ['1'], ['2'], ['3'], ['4'], ['5'].
  ![](https://github.com/rkuo2000/Robotics/blob/main/images/Philon-Wave_quadruped_simulation.gif?raw=true)

---
### CAD: [design.step](https://github.com/alexandrospetkos/quad/blob/master/resources/CAD/3D%20Models/design.step)
![](https://github.com/alexandrospetkos/quad/blob/master/resources/Photos/thumb.jpg?raw=true)
![](https://github.com/alexandrospetkos/quad/blob/master/resources/Photos/img0.png?raw=true)
![](https://github.com/alexandrospetkos/quad/blob/master/resources/Photos/img1.png?raw=true)
![](https://github.com/alexandrospetkos/quad/blob/master/resources/Photos/img2.png?raw=true)
![](https://github.com/alexandrospetkos/quad/blob/master/resources/Photos/img3.png?raw=true)
![](https://github.com/alexandrospetkos/quad/blob/master/resources/Photos/img4.png?raw=true)
![](https://github.com/alexandrospetkos/quad/blob/master/resources/Photos/img5.png?raw=true)

---
### Demo
<iframe width="878" height="494" src="https://www.youtube.com/embed/Sblo40GJvZc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br>
<br>

*This site was last updated {{ site.time | date: "%B %d, %Y" }}.*

