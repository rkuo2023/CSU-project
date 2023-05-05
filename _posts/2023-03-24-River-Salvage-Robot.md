---
layout: post
title: River Salvage Robot
author: [StudentID]
category: [Lecture]
tags: [jekyll, ai]
---

愛河尋寶趣 - 打撈機器人

---
## Content
* **專題題目** (Project Name & Objectives)
* **應用與功能說明** (Key Features)
* **設計考量與所需相關技術** (Design considerations)
* **系統方塊圖** (System Block Diagrams)
* **概念驗證** (Proof of Concept)
* **成果展示** (Demostation)

---
## 愛河尋寶趣
類別: 打撈機器人 <br>

目的: 落愛河之物品, 辨識搭配光通訊傳送掉落物影像, 並撿取掉落物<br>

---
### 應用功能說明
1. 探測沉落物 (手機) - AI視覺辨識 
2. 命令傳送 - 水下光通訊
3. 水下測距 - 超音波
4. 水下載具 - 打撈夾具之設計

---
### 設計考量與相關技術
**系統設計考量：**<br>
1. 移動方式: 螺旋槳
2. 供電方式: 鋰電池
3. 通訊方式: 水下光通訊 (或有線式水下紅外線攝影機)
4. 拾取方式: 撿取手機之夾具

**所需相關技術：**<br>
1. AI視覺辨識微控制器模組 (AMB82-mini)
2. 水下通訊: 紅外線 (IR-LED + VS1838B)
3. 水下測距: 水下超音波
4. 水下載具: 水下機器人 (TBD)

---
### 系統方塊圖
TBD

---
### 概念驗證
1. AI視覺辨識: [AMB82-mini](https://www.ruten.com.tw/item/show?22308071996883)
![](https://a.rimg.com.tw/s3/ebay/834/619/3rdeye%2A2011%40ebay/2/88/24/ef1e331915aaef772f8a55fa5542723d_30223030550564.jpg)

2. 水下通訊: 紅外線 IR-LED + VS1838B

3. 水下測距: [水下超音波](https://www.ruten.com.tw/item/show?22313324625575)
4. ![](https://img.alicdn.com/imgextra/i1/2818464855/O1CN01xWqDFh1ljdb5LOuOs_!!2818464855.jpg)

4. 水下載具: 打撈機器人

5. 水下撿拾: 撿拾手機之夾具

---
### 開發進度與展示

**AI視覺辨識**<br>

1. 驗證[AMB82-mini](https://www.ruten.com.tw/item/show?22308071996883)<br>
* [AMB82 MINI (Ameba RTL8735B) summary](https://www.amebaiot.com/zh/ameba-arduino-summary/)
* [AI examples](https://www.amebaiot.com/zh/amebapro2-amb82-mini-arduino-peripherals-examples/#ambpro2-arduino-ai)
* [AI Object Detection](https://www.amebaiot.com/zh/amebapro2-amb82-mini-arduino-neuralnework-object-detection/)

**水下通訊**<br>
1. 驗證紅外線水下通訊 IR-LED + VS1838B

---
### 參考資料 (References)
* 打撈機器人
![](https://github.com/rkuo2023/CSU-project/blob/main/images/Salvage-Robot.jpg?raw=true)

* 水下機器人
![](https://github.com/rkuo2023/CSU-project/blob/main/images/Deep-Sea-Rov-Underwater-Robot.jpg?raw=true)

* [水下無人機](https://www.pchomeus.com/item/show?30227110050966)
![](https://a.rimg.com.tw/s3/ebay/db2/83e/koeoep-direct%40ebay/a/c4/96/5cab9ef8953890e6abd0f3ccd68e2b70_30227110050966.jpg)

* [ROV載具機器人](https://www.ruten.com.tw/item/show?21647444445331)
![](https://gcs.rimg.com.tw/g1/9/38/93/21647444445331_110.jpg)

* [ROV系統簡介](https://www.tori.narl.org.tw/TORI_WEB/CTORI/Core_Facility/ROV/index.html)
![](https://www.tori.narl.org.tw/TORI_WEB/CTORI/Core_Facility/ROV/index.files/image002.png)

* [DIY水下推進器](https://www.ruten.com.tw/item/show?22150477584465)
![](https://gcs.rimg.com.tw/g1/7/5c/51/22150477584465_714.jpg)

* [水下推進器](https://www.ruten.com.tw/item/show?21306179172593)
![](https://gcs.rimg.com.tw/g1/e/b0/f1/21306179172593_735.jpg)

* [遙控迷你潛水艇](https://www.ruten.com.tw/item/show?22112275536826)
![](https://a.rimg.com.tw/s5/010/5db/tanqi/1/ef/ba/22112275536826_460.jpg)

* AI視覺辨識: [AMB82-mini](https://www.ruten.com.tw/item/show?22308071996883)
![](https://gcs.rimg.com.tw/g1/0/e5/d3/22308071996883_434.jpg)

* [水下攝像]
- [15m 電線8件 led /紅外線520tvl 12v水下潛艇檢查cctv迷你攝像機](https://www.pchomeus.com/item/show?30223030550564)

* 水下測距器
![](https://www.hnq5188.com/ueditor/php/upload/image/20210615/1623735813455261.jpg)

<br>
<br>

*This site was last updated {{ site.time | date: "%B %d, %Y" }}.*


